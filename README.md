# solar-tracker

Home Solar: see what your rooftop solar saves you, from your TNB bills and your solar app's monthly kWh.

Live site: https://derektanjh.github.io/solar-tracker/

- **Anyone can use it.** Each person's bills are saved on their own device. Nothing is sent to the site's owner.
- **Google Drive sync (optional):** sign in with Google to keep your bills in a `Home Solar data.json` file in your own Drive and see them on all your devices. The site asks only for the `drive.file` permission, so it can see that one file and nothing else in your Drive.
- **Backup file:** save or restore a `.json` backup from the **Your data** panel.
- **Add a month:** tap **Add month**, upload the TNB bill PDF (read on your device) and type the solar kWh from your solar app.
- **Bills supported:** TNB **Domestic Time-of-Use** bills.
- **Actual usage** = Import + Solar generated − Export.
- iPhone: open the site in Safari → Share → **Add to Home Screen**.

Google sign-in uses an OAuth client in the owner's Google Cloud project "Home Solar" (authorized origin `https://derektanjh.github.io`). While that app is in testing, only the test users listed there can sign in.
