# cartnest.app

Static GitHub Pages website at https://cartnest.app, published from main.

The default download is the 0.1.1 Android test APK (`app.cartnest.test`, versionCode 2) in Cloudflare R2 bucket `cartnest-downloads`, key `releases/0.1.1/Cartnest-0.1.1-test.apk`. `release.json` records its size and SHA-256. Both download buttons use that immutable version URL.

Login uses individual email accounts with dynamic one-time codes sent through Resend from `no-reply@cartnest.app`. Never publish actual verification codes or SMTP credentials.
