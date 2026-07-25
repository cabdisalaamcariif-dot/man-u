RED DEVILS FC — FAN SITE (DEMO)
================================

An unofficial, fan-made football club website built as a front-end demo.
Not affiliated with any real club — colours and copy are original/generic
so you can freely swap in real branding, text, and photography.

STRUCTURE
---------
index.html    Homepage — hero, club stats, next-match "ticket" card, features
about.html    Club story / history timeline
contact.html  Contact form styled as a ticket stub
login.html    Member login page
images/       Placeholder images (replace with your own):
              logo.png, hero.jpg, stadium.jpg, players.jpg, team.jpg

STYLING
-------
Built with Tailwind CSS only, loaded via CDN (no build step required):
  <script src="https://cdn.tailwindcss.com"></script>

Fonts: Anton (display headlines), Oswald (labels/numbers), Inter (body text)
— loaded from Google Fonts.

Custom Tailwind theme colours (see the tailwind.config script in each page):
  devil      #DA291C   primary red
  devildark  #A31D14   hover/darker red
  ink        #0C0C0C   near-black
  bone       #F5F3EF   off-white background
  gold       #C9A227   accent

HOW TO USE
----------
1. Open index.html directly in a browser — no server or build tools needed.
2. Replace the files in /images with real photos (keep the same filenames,
   or update the <img src="..."> paths in each HTML file).
3. Edit text directly in the HTML — all copy is plain and easy to find.
4. To change colours/fonts sitewide, edit the tailwind.config block that
   appears near the top of each HTML file.

NOTES
-----
- All four pages share the same header/footer markup (copy-pasted, since
  this is a static multi-page site with no templating engine).
- Placeholder images were generated locally as simple labeled graphics —
  swap them out for real photography before publishing.
