# Key-of-Success
It is only for demo and demonstrative purpose site designed using fronend technologies and local storage suitable for any coaching centre to main Fee Payment Record of Students at local device level . 
# Key Of Success — Fee Portal (Local Demo)

Overview
- Simple single-page Fee Management Portal for local/browser use.
- Designed for a small coaching centre (Nursery — 8th).
- All data stored in browser localStorage (students & fee slips).

Files included
- index.html — Main portal (UI + JS). Keep in same folder with the other files.
- owner.htm — About Owner (AJAX page).
- privacy_policy.html — Privacy Policy (AJAX page).
- term_condition.htm — Terms & Conditions (AJAX page).
- README.md — This file.
- LICENSE — MIT license.

How to use
1. Place all files in the same directory.
2. Open index.html in a modern browser.
   - If the browser blocks local fetch() for .htm files (file://), run a simple local server:
     - Python 3: `python -m http.server 8000`
     - Then open: `http://localhost:8000`
3. Use the left menu:
   - Student Enrollment — add root and sibling records.
   - Fee Entry — load root to compute payable and save a fee slip (admin action).
   - Sibling Preferences — manage sibling records.
   - All Fee Slips — search and view saved slips.
4. Settings (admin only):
   - To change the admin password you must authenticate with the admin password.
   - If you don't have the admin hash/password, open Settings → Request Admin Hash (this prepares an email to akshatpsd2005@gmail.com which you must send manually).

Security & backups
- This is a local demo with no server storage. Make regular backups if the data is important.
- If you need production-grade security or cloud backup, I can suggest architecture and implement server-side storage and authentication.

If you'd like
- A split into app.js / app.css,
- JSON import/export buttons for backup,
- A safer hashed local password storage,
- Or server-based user authentication — tell me which enhancement and I will prepare it.

Other Links 
Email : akshatpsd2005@gmail.com 
LinkedIn : https://www.linkedin.com/in/akshat-prasad-b53936379?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
GitHub Repo : https://github.com/Akshat-881236/Key-of-Success
Give me Feedback at https://akshat-881236.github.io/Portfolio-881236/feedback.htm