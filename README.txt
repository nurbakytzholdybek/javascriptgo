Assignment 5 — Our Favorite Games
Team members: Nurbakyt and Anuar

RUN
Extract the whole ZIP and open index.html in a browser. Keep css, js,
images and audio folders next to the HTML files. No installation required.

CHANGES
All pages: day/night theme, 1–5 star rating, sound on/off, Test sound,
arrow-key navigation (also Home and End). Ratings and theme use localStorage.
Main page (index.html): genre filter and three-step game recommendation form.
Original Assignment 4 content and functions are retained.

CODE MAP FOR DEFENSE / REPORT
js/advanced.js:
- setTheme: DOM classes, textContent, style and attribute changes.
- displayRating: querySelectorAll, dataset, forEach and aria-pressed.
- menuLinks keydown listener: switch, keyboard focus and wraparound.
- gameLibrary: object, method and array of game objects.
- getByGenre: filter callback (higher-order function).
- renderGames: switch, for...of, createElement, image src and link href.
- changeStep(direction, callback): explicit callback and preserved form state.
- playSound: Audio playback, pause/currentTime to avoid overlapping effects.
css/style.css: night theme, reveal keyframes, transitions and mobile rules.
Rating click also runs a short Web Animations API animation.
js/script.js: previous assignment's features.

This is a static student project. Existing registration/subscription forms
validate input locally; they do not create accounts or send email.

DEPLOYMENT
Upload the contents of Assignment5 to your shared GitHub repository.
Commit/push changes, enable GitHub Pages for the relevant branch/root,
and use the resulting real URL in your own report. This ZIP is not deployed.
