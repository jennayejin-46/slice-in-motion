SLICE / IN MOTION — PORTFOLIO GAME PAGE

FILES
- index.html  : portfolio-style page shell and project information
- sketch.js   : p5.js + ml5.js game, embedded character art, sound, leaderboard

RUN
Serve this folder from HTTPS (or a local development server) so the browser can request camera access.
For p5.js Web Editor, copy index.html and sketch.js into the project.

CONTROLS
- Type nickname + ENTER: continue
- SPACE: start / replay
- M: sound on/off
- N: new player
- D: body-tracking debug view

GAMEPLAY
- Full-body BlazePose tracking
- Both hands can slice
- Fast gestures activate a slice
- Characters cost one life when missed
- Bombs cost one life when sliced
- 3 lives total
- Local Top 5 scores are saved in browser localStorage

PORTFOLIO NOTE
The title and page copy are intentionally brand-neutral. Character art remains embedded in sketch.js.

PORTFOLIO UI UPDATE
- Embedded Jenna logo appears inside the game at bottom-right on a cream tag.
- Bomb size/hit radius increased by 8% relative to the previous build.
