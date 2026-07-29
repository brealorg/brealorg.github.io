# subshell Pages site

Static public site candidate for `https://brealorg.github.io`.

## Identity

- Android application ID: `io.github.brealorg.subshell`
- Production callback: `https://brealorg.github.io/oauth/callback`
- Release certificate SHA-256:
  `52:E9:62:E7:41:2E:25:DA:80:1E:0A:39:06:E0:BF:B4:39:90:0A:1A:A1:5B:A9:F9:3C:95:B4:99:55:BA:F5:84`

## Publication model

- Repository: `brealorg.github.io`
- Publishing source: `main` branch, repository root
- Jekyll processing: disabled by the root `.nojekyll` file
- Custom domain: none
- JavaScript, analytics, forms, cookies, and external assets: none

The file at `/.well-known/assetlinks.json` is the public Android Digital
Asset Links statement. After deployment, HTTPS status, redirect behavior,
content type, and Android domain verification must be tested against the
live host before the app manifest is enabled for production.
