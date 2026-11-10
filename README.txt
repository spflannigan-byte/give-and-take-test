Give&Take V1.3.2 — Local test application

Open index.html in a desktop browser for testing. On iPhone/iPad, opening local HTML from Files may block browser storage; this release displays a recovery warning rather than leaving a blank screen. It does NOT make local file storage reliable on iOS. Use an HTTPS test site for later mobile testing.

This is a single-device prototype; do not use as authoritative production inventory.

Data storage: This maintenance release intentionally uses the same V1.3.1 browser storage key and schema, to retain existing V1.3.1 test data in the same browser/origin. Keep a JSON backup. File URLs may have different storage origins.

Changes: See CHANGELOG.txt.

Give&Take V1.3.1 — local prototype

Open index.html in a desktop browser for testing. On iPad, local HTML previews may not run JavaScript reliably; HTTPS hosting is preferable for later device testing.

TEST:
1. GIVE and TAKE from a rail; verify Audit / Correction History remains unchanged.
2. Mark initialization complete, edit a rail, and verify one correction History entry.
3. Reopen Audit / Edit without changing anything; verify no new History entry.
4. Export JSON in Setup, change a rail, then restore; verify inventory restored.
5. Export pre-restore copy from Setup and verify it contains the previous inventory.
6. Keep older version folders unchanged; V1.3.1 uses its own browser storage key.

Do not use as authoritative production inventory.
