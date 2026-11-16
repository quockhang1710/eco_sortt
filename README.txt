ECO SORT — WEBSITE PROTOTYPE

WHAT IS INCLUDED
- English-language responsive website
- Sign up and log in demo
- Photo capture/upload interface
- Three sorting bins: Blue / Recyclable, Brown / Organic, Gray / General
- Retry after a wrong answer
- +10 points for a correct answer
- Virtual reward badges
- Local demo leaderboard
- Website QR code appears after deployment on an HTTPS website

IMPORTANT LIMITATIONS — PLEASE READ
This is a working FRONT-END PROTOTYPE, not a production service.
1. The current demo does NOT analyze the uploaded photo with AI. After uploading, the player selects a sample category so the sorting, retry, points and rewards flow can be tested.
2. Accounts and points are stored in this browser's local storage. They are not securely stored online, do not sync between devices, and can be cleared by the user.
3. Passwords in this demo are not securely hashed. Do not use a real password or real personal information.
4. The leaderboard is local to this browser only.
5. Rewards are virtual badges with no cash value.
6. A production launch needs a secure backend, database, password hashing, server-side point validation, image moderation/privacy controls, AI image classification, abuse prevention, and an admin system for rewards.
7. Do not invite the public to upload personal or sensitive images until a privacy policy and secure image-handling process are in place.

HOW TO PREVIEW
- Extract the ZIP.
- Open index.html in a modern browser.
- For camera access and QR code generation, publish the site over HTTPS. Some browser features may not work when opening the file directly.

HOW TO PUBLISH
You can publish the static prototype using a static website host such as GitHub Pages, Netlify, or Cloudflare Pages:
- Upload index.html, style.css, and app.js to the host.
- Set the publish/root directory to the folder containing index.html.
- After deployment, open the HTTPS website URL. The dashboard QR code will encode that URL.
- This only publishes the prototype. It does not add AI or secure online accounts.

NEXT PRODUCTION BUILD
Recommended next stage: connect a backend (for example Supabase or Firebase), implement real authentication and database tables, then connect an image-classification service through a secure server endpoint. Never put secret API keys in app.js.
