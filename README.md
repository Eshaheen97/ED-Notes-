# ED Note Vault

A static, no-ad, browser-based library of editable ED documentation templates. It is designed for GitHub Pages and requires no paid APIs or backend.

## Publish on GitHub Pages
1. Sign in at https://github.com and create a new repository named `ed-note-vault`.
2. Set it to **Public** (GitHub Pages availability depends on the repository and plan; public repositories are the straightforward free option).
3. On the repository page choose **Add file → Upload files**.
4. Upload `index.html`, `style.css`, `app.js`, and optionally `README.md` from this folder. Upload the files themselves, not the containing folder as a single archive.
5. Click **Commit changes**.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**; select branch `main` and folder `/(root)`, then click **Save**.
8. Wait for deployment. The page will show the website URL, typically `https://YOUR-USERNAME.github.io/ed-note-vault/`.

## Notes
- This is a drafting aid, not a clinical decision support system.
- Custom templates and favorites are stored in the current browser's local storage. They do not automatically sync between devices.
- Do not enter patient-identifying information or store patient records.
- Check all templates against actual findings, local protocols, and approved hospital documentation requirements.


Updated version: includes age/sex, known-case history, allergies, pain score, a standalone general physical examination template, common ED presentations, and ISBAR handover. Default normal examination text is editable and must be verified against the actual examination before entering the hospital record. Do not store patient-identifiable data in this static site.
