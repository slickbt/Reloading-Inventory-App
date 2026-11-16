IPAD INVENTORY VAULT — EASY SETUP

This ZIP contains an installable, offline-capable web app (PWA). It is NOT an IPA file.
You must host the folder on an HTTPS website once to install it on iPad.

EASIEST FREE SETUP (GitHub Pages):
1. On a computer, unzip this package.
2. Create a new GitHub repository (public on the free GitHub Pages plan).
3. Upload ALL files inside the ipad_inventory_pwa folder to the repository root.
4. In repository Settings > Pages, choose Deploy from a branch, main, /(root), Save.
5. Wait for the HTTPS website URL shown in Pages settings.
6. On the iPad, open that HTTPS URL in Safari while connected to the internet.
7. Tap Share > Add to Home Screen > Add.
8. Open Inventory Vault from the Home Screen. Create a strong password.
9. Add a TEST record, close and reopen the app, and test in Airplane Mode.
10. Export encrypted backups to Files regularly.

IMPORTANT:
- GitHub Pages hosting is public: the app's code is public, but inventory data is
  NOT uploaded to GitHub. It stays encrypted in your iPad's browser storage.
- Do not upload backup files or inventory records to the GitHub repository.
- If you prefer private hosting, any static HTTPS host will work.
- The app never sends your inventory records to a server.
- Browser storage can be erased by Safari/iOS, so keep encrypted backups.
- Passwords cannot be recovered. Backup encryption uses the current vault password.
- Installing from a new URL/origin creates a separate local vault.
- AES-256-GCM; PBKDF2-SHA256, 310,000 iterations; automatic lock after 5 minutes.
- No external libraries, analytics, or network API requests are included.
- This software has not received an independent security audit.
