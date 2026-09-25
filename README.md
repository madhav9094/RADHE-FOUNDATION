# RADHE FOUNDATION

આ નવી ZIP આવૃત્તિમાં હાલના Digital Foundation frontend structureને આધારે RADHE FOUNDATION માટે option-wise, editable અને transparent website તૈયાર કરવામાં આવી છે.

## મુખ્ય સુવિધાઓ
- RADHE FOUNDATION branding.
- Home page પર અલગ-अलग option cards; દરેક option click કરતાં માત્ર સંબંધિત માહિતી દેખાય.
- Service photos: multiple upload, full-screen viewer, previous/next arrows, swipe, zoom in/out અને reset zoom.
- Admin panel: મોટા option-wise dashboard cards.
- Donations: donor photo, public visibility, Edit/Delete.
- Campaigns: target + received amount, Edit/Delete.
- Expenses: amount, date, category, place, note; home પર સંપૂર્ણ વિગત.
- Help requests: village + email; Admin Save & Update workflow.
- Donation: Admin QR upload/update; public donation notice form with name, village, mobile, amount, screenshot and details.
- Donation notices: Admin panelમાં અલગ notification count, Edit/Delete, Save & Approve; approved noticeથી donor record બનાવાય છે.
- JSON backup/export.

## Demo Admin
Username: `admin`
Password: `Admin@123`

## મહત્વની વાસ્તવિક-ઓનલાઇન નોંધ
આ ZIP browser `localStorage` આધારિત છે, એટલે data એક જ browser/deviceમાં રહે છે. અલગ-अलग લોકોના ફોનમાંથી public submissions સીધા તમારા admin device સુધી પહોંચાડવા માટે backend/database જરૂરી છે.

Email માટે `config.example.js`માં backend endpoint મૂકવાની જગ્યા છે. Backend endpoint વગર approval વખતે user's mail client માટે pre-filled `mailto` ખુલશે; browser પોતે silently email મોકલી શકતું નથી.

આ ZIPને Hostinger જેવી PHP hosting પર મૂકીને આગળ PHP/MySQL backend જોડવામાં આવી શકે છે. હાલના frontendમાં backend માટે જરૂરી fields/workflow તૈયાર રાખવામાં આવ્યા છે.
