# chopyourbrain.github.io

Developer website for all apps in the AdMob account.

- `app-ads.txt` at the root covers every app in the same AdMob publisher account. Never move it into a subfolder.
- Each app gets its own folder: `/<app>/index.html` and `/<app>/privacy-policy.html`, plus a section in the root `index.html`.
- In Play Console and App Store Connect, set every app's website to `https://chopyourbrain.github.io` exactly.
- The root `privacy-policy.html` and `terms-of-service.html` only redirect to `/cardscout/`; keep them so old links still work.
