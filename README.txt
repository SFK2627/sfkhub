SFK Hub - Updated Files

Files included:
1. index.html
2. hub.css

Updates made:
- Added KindTrack group/card: Responsibility & Violation Viewer
- Added passcode gate for ClassBoard Admin and KoalaCare Admin
- Kept ClassBoard, Officer View, and KoalaCare Student Report as normal links
- Admin pages open only after entering the SFK Hub passcode
- Links still open in a new tab
- Mobile badge stays clean: SFK PORTAL

Default SFK Hub passcode:
SFK2026

To change the hub passcode:
Open index.html and find:
const HUB_ADMIN_PASSCODE = "SFK2026";

To change the KindTrack link:
Open index.html and find:
https://johnreytubs24.github.io/sfk-kindtrack/

Replace it with the actual KindTrack GitHub Pages link if your repo has a different URL.

Important note:
This hub passcode is only an extra front-door gate because GitHub Pages is a static site. Your actual admin pages should still keep their own passcode/login.
