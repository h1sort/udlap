# udlap · Carlos Haro's panel deck, 3er Congreso Nacional de Ciencia de Datos (Bourbaki)

Current deck: **Hechos estilizados del mundo de la IA** (panel "El mercado laboral antes y después de OpenAI", Nov 20, 2026, 10:00). Read `PLAN.md` first; it holds the six facts, sources and how the deck is used on a panel.

The deck shell (`deck/engine.js`, `particles.js`, `styles.css`, `tools/`) is copied from `h1sort/cide`, which copied it from `h1sort/datapub` (see `deck/CONTRACT.md` there for the slide API).

## Working rules
- Slide text is in Spanish with correct accents. Code, file names and commit messages in English.
- Every number on a slide needs a source in `PLAN.md` §3 and the `fuentes` slide, or it gets cut. Say which fact is the author's own observation (fact 04).
- Do not name or cite Carlos Ruiz's article on slides; it was background only.
- Speaker notes: Spanish, first person, Carlos's spoken voice, end with the bridge to the next fact, stage directions in `<p class="dir">[…]</p>`.
- No network at runtime. Projector rules: text ≥ 28px on the 1920×1080 stage, labels ≥ 20px, keep the bottom 140px free.

## Run it
- Present: `python3 deck/tools/serve.py`, open http://127.0.0.1:8000/deck/, `P` presenter mirror, `N` notes, `B` black.
- Screenshot: `deck/tools/shot.sh @<slide-id> <step>`; PDF: `deck/tools/pdf.py out.pdf`.

## Publishing to h1sort.com/udlap
Same flow as cide: commit here first; in `h1sort-website`, on a new branch, `deck/tools/public-build.py public/udlap` (strips notes, fails if any remain), add `https://h1sort.com/udlap/` to `customPages` in `astro.config.mjs` and a line to `public/llms.txt`, `npm ci && npm run build`, PR and merge the same day.
