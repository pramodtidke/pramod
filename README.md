# pramodtidke.in setup (about 10 minutes, on a laptop)

1. Create a GitHub repo (e.g. `pramodtidke.github.io`) and upload everything in this folder to branch `main`.
2. Open `admin/config.yml` and replace `REPLACE_WITH_REPO_NAME` with your repo name.
3. Repo > Settings > Pages > Source: **GitHub Actions**. Custom domain: `pramodtidke.in` (set DNS at your registrar).
4. GitHub > Settings > Developer settings > Fine-grained tokens: this repo only, **Contents: read and write**, with an expiry date.
5. Open `pramodtidke.in/admin/`, sign in with the token. On your phone, open the same URL and Add to Home Screen.
6. Auto-import: edit `scripts/feeds.json` (add your two YouTube channel IDs, check the Substack URL), then run the workflow once from the Actions tab. Medium RSS only returns the latest posts; add older ones by hand.
7. Entries marked `sample` are demos. Delete them in the dashboard as you add real ones.

Each dashboard save is a commit; the site rebuilds in 1-2 minutes. Lost phone: revoke the token on GitHub.

## New in this version
- Games page with 7 games (no puzzle gates). Riddles are edited in the dashboard under Content lists > Riddles.
- Hero status line, headshot and rotating words: dashboard > Pages and text > Site settings.
# pramod
