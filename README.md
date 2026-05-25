# Micro Budgeting Privacy Policy Site

Static privacy policy for Google Play and Netlify deployment.

## Deploy to Netlify

1. Create a new site in [Netlify](https://app.netlify.com/) and point it at this `MicroBudgeting-pv` folder.
2. Build settings (auto-detected from `netlify.toml`):
   - **Publish directory:** `.` (this folder)
   - **Build command:** (none required)
3. Deploy. Add the live URL to Google Play Console under **App content → Privacy policy**.

## Local preview

```bash
python3 -m http.server 8080 --directory .
```

Open http://localhost:8080

## Customize

- Update contact email in `index.html` (currently `support@microbudgeting.app`).
- Set `CONTACT_EMAIL` and `DEVELOPER_NAME` env vars when re-running the generator.
