PRINS TRUCKING - 4-PAGE WEBSITE PACKAGE
=======================================
Pages: index.html (Home), safety.html, about.html, drive.html. Shared styles.css and images/.
Plain HTML, no build step. Keep all files in the same folder structure.

TO PUBLISH
----------
Netlify (easiest): app.netlify.com/drop -> drag the prins-website FOLDER onto the page.
   You get a free test address right away. Check it on your phone first.
Cloudflare Pages: Workers & Pages -> Create -> Pages -> Upload assets.
GitHub Pages: put the files in a repo, Settings -> Pages.

POINTING prinstrucking.com AT THE NEW SITE (do this last)
---------------------------------------------------------
The domain currently serves the Canva site.
1. Leave MX / TXT records alone: they run company email (adam@prinstrucking.com).
2. Add the custom domain in the host; it shows the exact A/CNAME records.
3. At the registrar, replace only the website A/CNAME records (@ and www).
4. Keep the Canva site until the new one loads on the real domain.
Screenshot the existing DNS records before changing anything.

LEFT OUT OF THE ORIGINAL DESIGN (nothing in the original was real content yet)
------------------------------------------------------------------------------
- Hero truck photo and driver photo (were placeholders)
- Jeff Warren / Daniel Warners photo cards (they are named in the maintenance paragraph on the Safety page)
- Pay / Home time / Benefits detail: kept vague on purpose ("Competitive compensation and benefits", "34-hour resets at home")
- Embedded pre-trip video (a "Watch on YouTube" button links to it instead)

TO CONFIRM
----------
Kurt since 1994 / 32 years; Jeff Warren and Daniel Warners; address; phone.
Request a Quote opens an email to adam@prinstrucking.com. Apply Now opens the Fillio form.
Barlow fonts load from Google Fonts once online (fallback Arial Narrow / Arial).

EDITING
-------
Text is plain text inside the .html files. Colors: variables at the top of styles.css.
