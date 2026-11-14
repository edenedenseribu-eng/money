MONTHLY BILLS TRACKER — PWA

WHAT'S INCLUDED
- Offline-capable installable PWA
- Password-protected encrypted local vault (AES-GCM + PBKDF2)
- Add/edit/delete bills, categories, due dates, notes and receipt photos
- Paid/unpaid status and monthly totals
- Copy bills from previous month
- Encrypted backup and restore
- Monthly report via browser Print > Save as PDF

IMPORTANT SETUP
A PWA must be opened from a secure HTTPS website (or localhost) to install and cache offline.
It cannot be installed as a PWA by opening index.html directly from the phone's file manager.

EASY FREE DEPLOYMENT
1. Create a private or public repository on GitHub and upload all files in this folder.
2. In repository Settings > Pages, choose Deploy from branch, select main and /(root), then Save.
3. Open the published HTTPS address in Chrome on Android.
4. Chrome menu (⋮) > Install app / Add to Home screen.
5. Open it once while online. After that, the app shell works offline.

PRIVACY / LIMITATIONS
- Bills and receipt images are encrypted in browser localStorage on this device.
- No account or cloud sync.
- Your password cannot be reset. If forgotten, data cannot be decrypted.
- Export an encrypted backup regularly and keep it somewhere safe.
- Clearing browser/site storage can erase the vault.
- Browser storage can be cleared by Android battery/storage cleaners; keep backups.
- PDF report excludes receipt images; receipts remain attached to bill records in the encrypted vault.
- Google Fonts import is optional; app uses system fonts if offline.
