# Sreshta Portfolio

Personal portfolio of **Gaddam Ganga RaagaSreshta Reddy** — B.Tech CSE (AI & ML) student at JAIN (Deemed-to-be University).

Highlights: an interactive 3D red-particle portrait (Three.js / WebGL) that follows the cursor and dissolves into the real photo on **Reveal**, plus Home, About Me, Technical Skills, Education, Projects (FairShare), Certifications and Contact sections.

## Tech
Plain HTML, CSS and JavaScript in a single `index.html` — no build step, no dependencies to install. Loads Three.js r128 (cdnjs) and Google Fonts (Anton, Inter) at runtime. The portrait cut-out and certificate images are embedded in the file; copies live in `assets/`.

## Run locally
Open `index.html` in a browser, or:
```
python3 -m http.server 8000
```
then visit http://localhost:8000

## Edit content
Open `index.html` and find `const CONFIG={` — edit text there (about, education dates, internship details, project link, contact info). Add the FairShare repo URL to `project.link` to show a "View on GitHub" button.

## Deploy (Vercel)
Framework Preset: **Other** · Build Command: *(empty)* · Output Directory: *(empty / root)* · Install Command: *(empty)*. Every push to `main` redeploys automatically.

## Contact
gaddamsreshtareddy@gmail.com · [GitHub](https://github.com/gaddamsreshtareddy) · [LinkedIn](https://www.linkedin.com/in/sreshtareddy-gaddam-ba618038a/)
