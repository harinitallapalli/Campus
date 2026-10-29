# CampusHub

Student and faculty portal with an AI Companion. Static site plus one Vercel serverless function.

## Files
- index.html, styles.css, data.js, app.js: the site
- assets/upi-qr.jpeg: your payment QR image (add this file)
- api/chat.js: AI Companion proxy (keeps your NVIDIA key private)

## Deploy
1. Push this folder to a GitHub repo.
2. In Vercel: Add New > Project > import the repo > Deploy.
3. Project > Settings > Environment Variables: add NVIDIA_API_KEY (from build.nvidia.com). Redeploy.

Demo logins (password campus123): alex.johnson@university.edu (student), sharma@university.edu (faculty).

## Subscription
7-day free trial, then Rs 19/month or Rs 190/year (19 x 10). Payment is by UPI QR: put your QR at assets/upi-qr.jpeg and (optionally) set your UPI ID in PAY.upi near the bottom of app.js.
Because this is a static site, payments are not verified automatically. Users enter their UTR and get access; check your bank/UPI app for matching payments.

Contact: harinitallapalli@gmail.com, 9059142267

By- Harini

After paying, the user taps "Have you paid?" and WhatsApp opens with their details addressed to the owner (they tap Send). An email option and an AI Companion contact answer are shown as fallbacks.
