# Tagalog Comment Assistant — iPhone Web App

This is a static Progressive Web App (PWA), not an iPhone Safari extension. It generates suggestions for manual review and copying; it does not publish comments to Facebook.

## Put it on your iPhone

1. Upload the **contents** of this folder to an HTTPS static web host (for example GitHub Pages, Netlify, or Cloudflare Pages). A ZIP opened directly in Files cannot be added as a functioning web app.
2. On your iPhone, open the hosted HTTPS URL in **Safari**.
3. Tap **Share** → **Add to Home Screen** → **Add** (choose Open as Web App if offered).
4. Open the new icon. Select categories and a count, then Generate. Copy any individual suggestion and paste it manually into Facebook.

The web app can be used offline after the first successful hosted visit and service worker install. It does not request Facebook credentials or access your Facebook account.

## Limitations

- The number field accepts 1–1,000,000 but displays 50 suggestions at a time, generated on demand.
- Large counts are not guaranteed unique: templates repeat.
- Export saves the **current page of 50** to TXT to keep iPhone memory usage low.
- Topic field is a label only.
- Scam warnings are general precautions, not factual accusations about a person.
