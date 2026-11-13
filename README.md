# chopyourbrain.github.io

Developer website for all apps in the AdMob account.

- `app-ads.txt` at the root covers every app in the same AdMob publisher account. Never move it into a subfolder.
- Each app gets its own folder: `/<app>/index.html` and `/<app>/privacy-policy.html`, plus a section in the root `index.html`.
- In Play Console and App Store Connect, set every app's website to `https://chopyourbrain.github.io` exactly.
- CardScout's pages stay at the root (`/privacy-policy.html`, `/terms-of-service.html`) because their URLs are already in use.
