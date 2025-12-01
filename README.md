# Key-of-Success
It is only for demo and demonstrative purpose site designed using fronend technologies and local storage suitable for any coaching centre to main Fee Payment Record of Students at local device level . 
# Key Of Success - Fee Portal (Local Demo)

This README is embedded and loaded via AJAX into the single-file SPA. It explains that:
- All data is stored locally.
- Interfaces 1..6 exist within the portal.
- Settings allow you to change the admin password locally.

How to use:
1. Interface 1 — Register root student and siblings.
2. Interface 2 — Enter fees. Proceed with Root ID; wait 3-7s to simulate processing.
3. Interface 3 — Search and download slips.
4. Interface 4 — Add / remove siblings.
5. Interface 5 — Income analysis and CSV export.
6. Interface 6 — Placeholder for extra tools.

Security note:
- Initial admin password is checked against a hash embedded in the JS.
- When you change the password in Settings it will be saved locally in the browser (not hashed).
