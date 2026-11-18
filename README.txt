PRAYERFLOW PILOT: HOW TO PUT IT ON A WEBSITE

What is in this folder
  index.html            the app
  manifest.webmanifest  lets phones install it on the home screen
  sw.js                 keeps it working with a weak connection
  icon-192.png, icon-512.png   the home screen icon

STEP 1. Upload the folder (helper or tech-savvy member)
  Upload ALL five files, together, to any free static website host. Examples: GitHub Pages,
  Netlify, Cloudflare Pages. Check the host's current free terms first.
  The address must start with https:// and the files must sit in the same folder.
  Open the address on your own phone to test it.

STEP 2. Members install it (no download needed)
  1. Open the address in Chrome on the phone.
  2. Tap the three dots at the top right.
  3. Tap "Add to Home screen" (or "Install app").
  4. Tap Add. A PRAYERFLOW icon appears on the home screen.

STEP 3. The prayer leader sets up the group once
  1. Open the app and tap "Parish" at the bottom.
  2. Under "Prayer group line-up", set the group name, the mystery for each day,
     and the order of prayers (choose from the list, no copying and pasting).
  3. Optional: paste the link to the group's live prayer (https only).
  4. Tap "Make a link", then "Copy link". Post it in the group chat.

STEP 4. Members apply the line-up
  Tap the link in the chat. The app opens and asks "Use this group's line-up?".
  Tap "Use this line-up". Done. When the leader changes the list, post a new link.

UPDATING THE APP LATER
  Replace the files on the website. In sw.js change CACHE='prayerflow-pilot-v1' to v2
  (v3, and so on) so phones pick up the new version.

GOOD TO KNOW
  - Each person's settings and "I prayed today" marks stay on their own phone.
  - Prayer texts are marked "awaiting content review" until your reviewer approves them.
  - Hymn audio and links are never shared. The app does not search for or download music.
  - Prayers a leader writes themselves are not included in a group link.
