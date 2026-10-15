# Escape Chatty Hackville — final trailer and external-tool routes

Upload these files together to the folder Vercel deploys:
- index.html — replaces your existing page; includes the map, styles, and route instructions
- trailer.mp4 — final 82-second Comic Cut, compressed for web playback
- trailer-poster.jpg — trailer thumbnail
- meme-starter.html — copyable starter students open in a new tab
- vercel.json — static deployment settings

Keep the filenames exactly as written. There is no assets folder to upload: the city map is embedded in index.html. Existing style.css and app.js files can remain, but this version does not use them.

Vercel: Framework Other; no build command; output directory .; root directory is the folder containing index.html. No environment variables or server required.

## Student flow
Watch the briefing → choose ONE character/route → follow three stops. All creative tools, message tools, and the CTF open separately. The website provides instructions, links, optional notes and checkmarks only; it does not generate media, decode messages or simulate a hacking terminal. Notes are local and are not sent to Moss.

Worldbuilder: Meshy character → Inkarnate map → Code.org meme.
AI Wrangler: Firefly rescue invention → Mureka music or Blob Opera performance → short rescue pitch.
Ghost Runner: choose laptop/computer OR RJ45 → Morse and ROT13 messages using external tools → beginner picoCTF practice.

## Before class
Check school access and accounts for linked tools. Do not require a purchase. Have physical stations ready with Moss-assigned unplugged equipment, the exact device manual, cable guides, a crimper, connectors and tester. Computer work is supervised; laptop battery preparation is handled by Moss; do not open power supplies.

The Dell link is for the lab's OptiPlex 3040 SFF; use the correct manufacturer's manual for any different computer or laptop. Signal Tower currently links Morse Code World because Moss's own Morse app URL was not supplied. Swap that URL in index.html when available.

For picoCTF, use the practice environment and the official beginner playlist. Individual sign-in, district filtering and credits on creative tools require a student-device check. Linked alternatives are in the route directions.

## Verification
Code checks cover map rendering, three route pages, all nine stops, completion states, invalid-route fallback and record downloads. Local media checks verify the trailer is readable and 82 seconds long. Browser visual QA and student-account access were not available here. Test the deployed site on a student device before class.
