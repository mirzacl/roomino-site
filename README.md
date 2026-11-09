# roominogame.com

The website for **Roomino!**, a calm floor-plan puzzle for iPhone and iPad: the landing page, the privacy policy
(`/privacy/`) and the support page (`/support/`). Plain HTML and one stylesheet, no build step, served by GitHub Pages
on the custom domain in `CNAME`. Built like `berryville-site`.

- `index.html`: the landing page. After release, swap the "Coming soon" pill for the App Store link.
- `privacy/index.html`, `support/index.html`: the pages the App Store listing and the game's Settings link to (the
  game's `Share.PrivacyUrl` points at the privacy policy).
- `assets/`: the stylesheet, the app icon, the link-preview image and the English iPhone screenshots, all made from the
  game's own files.
- After release, LevelPlay's `app-ads.txt` goes at the root.

Contact: support@roominogame.com
