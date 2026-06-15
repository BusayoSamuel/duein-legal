# duein-legal

Public privacy policy for [DueIn](https://github.com/BusayoSamuel/duein) (Google Play & App Store).

## Privacy policy URL (after GitHub Pages is enabled)

**https://busayosamuel.github.io/duein-legal/privacy.html**

Short link (root redirects to policy):

**https://busayosamuel.github.io/duein-legal/**

## One-time setup

1. Create a **public** repo on GitHub named `duein-legal` (empty, no README).
2. Push this folder:

   ```bash
   cd /Users/user/Documents/duein-legal
   git init
   git add privacy.html index.html README.md
   git commit -m "Add DueIn privacy policy"
   git branch -M main
   git remote add origin https://github.com/BusayoSamuel/duein-legal.git
   git push -u origin main
   ```

3. **Settings → Pages** → Source: **Deploy from branch** → **main** → **/ (root)** → Save.
4. Wait 1–2 minutes, open the URL above in a browser.

## Updating the policy

Edit `privacy.html`, commit, push. Pages redeploys automatically.
