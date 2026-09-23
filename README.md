# Careerix

A free career roadmap website for students. Plain HTML, CSS and JavaScript. No install, no build step, no API needed.

## Upload to GitHub from your phone
1. Open github.com in your browser (turn on "Desktop site" if it is easier).
2. Create a new repository (for example: careerix). Make it Public.
3. Tap "Add file" then "Upload files". Upload everything from this folder. All files sit together in one folder, no subfolders.
4. Commit the files.
5. Go to Settings, then Pages. Under "Build and deployment" choose "Deploy from a branch", branch "main", folder "/ (root)". Save.
6. After a minute your site opens at: https://YOUR-USERNAME.github.io/careerix/

## Adding or fixing a career
All career data is in careers.js. Copy an existing career block, change the values, and save. Set verified: true only after you check every fact on the official websites.

## Files
- index.html: home page with class selector
- careers.html: list of careers with search and filter
- career.html: one career page (reads ?id= from the link)
- quiz.html: career quiz
- about.html: about, safety and disclaimer
- style.css and the .js files: design and behaviour
- careers.js: all career information
