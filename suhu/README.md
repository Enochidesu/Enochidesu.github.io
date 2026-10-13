# SUHU public information pages

Buildless, static Indonesian homepage/privacy/terms for SUHU — Super Humas.

The support contact is enochi3317@gmail.com, reused from Glacia at the user's request. Brand assets are copied from the current SUHU SVG and its local Inter font; the font license is included. The website uses no client scripts, analytics, external font service, Google login widget or office data.

Proposed publication is a new `suhu/` directory in the existing Enochidesu/Enochidesu.github.io root site: https://enochidesu.github.io/suhu/ . Existing root/Glacia pages and the Google ownership proof must be preserved. This is a planned URL until a deployment is verified, not a claim of live publication.

Publish only this directory's allowlisted public files. Never publish App, private checkpoint ZIPs, Google client configuration, signing keys, tokens, OS profiles, local journals, notification records or Website-Review. Home/privacy/terms currently state that public app access is still being prepared. There is no installer download link; do not add one until the corresponding app release is approved and publicly verified.

Website publication does not verify Google branding/data access, grant Drive permissions, remove SUHU's current account restriction or bundle public sign-in configuration. Those are separate release steps. Google Cloud ownership/audience/verification status have not been inspected live in this preparation step.

Local checks use ../Website-Review/preview.cjs and verify.cjs. The review folder is private tooling/evidence and is outside the publication payload. Start with `node ../Website-Review/preview.cjs`, then pass the printed loopback URL to `node ../Website-Review/verify.cjs`. Stop the local preview when finished. No build or package install is needed to host these files on GitHub Pages.
