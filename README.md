# KeyCraft Studio — Kinetic Type-Deck & Touch Academy

Offline typing practice for PC (or a phone with a physical keyboard).

**Use online / install:** `https://<your-username>.github.io/keycraft-studio/`
Open it in Chrome or Edge and click the **Install** icon in the address bar. After that it works offline.

**Windows app:** go to **Releases** and download `KeyCraft-Studio-Setup-x.x.x.exe` (installer) or the `Portable` one.
Windows may show "Windows protected your PC" because the app is unsigned: click **More info → Run anyway**.

## For the maintainer
1. **Website:** Settings → Pages → Deploy from a branch → `main` / `(root)`.
2. **Build the .exe:** Releases → Draft a new release → create tag `v1.0.0` → Publish.
   The *Build Windows app* action (Actions tab) runs for a few minutes and attaches the .exe files to that release.
3. **Updating:** replace `index.html`, commit, and the site updates itself. For a new .exe, publish a new release tag (`v1.0.1`, ...).
