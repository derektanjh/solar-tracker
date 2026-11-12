# solar-tracker

Home Solar: see what your rooftop solar saves you, from your TNB bills and your solar app's monthly kWh.

Live site: https://derektanjh.github.io/solar-tracker/

- **Anyone can use it, with their own bills.** Nothing is sent to the site's owner.
- **Sign in with Google** to keep your bills in your own Google account (a `Home Solar data.json` file in your Drive), so they show on every device where you sign in. The site asks only for the `drive.file` permission, so it can see that one file and nothing else in your Drive. Each device also keeps a copy so the page opens instantly and works offline.
- **Without signing in,** bills are kept only in that browser on that device.
- **Backup file:** save or restore a `.json` backup from the **Your data** panel.
- **Add a month:** tap **Add month**, upload the TNB bill PDF (read on your device) and type the solar kWh from your solar app.
- **Bills supported:** TNB domestic bills on **Time-of-Use** or the **standard tariff**, with **NEM** or **Solar ATAP**. Time-of-Use maths is checked to the sen against real bills; the standard tariff uses TNB's published July 2025 rates and hasn't been checked against a real standard bill yet. Reading standard and ATAP bill PDFs is best effort, so the numbers can be typed in.
- **Actual usage** = Import + Solar generated − Export.
- iPhone: open the site in Safari → Share → **Add to Home Screen**.

Google sign-in uses an OAuth client in the owner's Google Cloud project "Home Solar" (authorized origin `https://derektanjh.github.io`). While that app is in testing, only the test users listed there can sign in.
