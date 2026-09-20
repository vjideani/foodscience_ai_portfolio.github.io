# Portfolio Website — Food Science & AI Consulting

This is a personal portfolio site for a food science professional who also builds AI/software tools.
It is written in first person and ready for GitHub Pages. Edit the placeholder content marked with
"Your Name", "yourusername", or "you@example.com" before publishing.

## File structure

```
portfolio-final/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── docs/       <- put your PDFs here (case studies, reports, CV, training decks)
    └── images/     <- put screenshots or photos here
```

## Sections included

1. **Home / Hero** — headline and quick summary of your two areas of work.
2. **About** — first-person background on your food science and tech experience.
3. **Services** — three concrete consulting offers (food safety, product development, research/AI tooling).
4. **Projects** — cards linking to GitHub repos for your technical work.
5. **Documents** — NEW: a dedicated section with cards linking to real files (PDFs, CV) stored in `assets/docs/`.
6. **Experience** — a two-column timeline of consulting, teaching, research, and technical work.
7. **Contact** — email, GitHub, LinkedIn, location, and a checklist of what to edit before publishing.

## How to add your own documents

1. Save your PDF (case study, report, training deck, CV) into `assets/docs/`.
2. Match the filename to the one referenced in `index.html`, for example `assets/docs/haccp-case-study.pdf`,
   or update the `href` in the Documents section to match your actual filename.
3. Repeat for each document card. Add more `<article class="document-card">` blocks if you have more files —
   copy an existing block and edit the title, description, and file path.

## How to publish on GitHub Pages

1. Create a GitHub repository (use `yourusername.github.io` for a personal root-level site).
2. Upload all files and the `assets/` folder, keeping `index.html` at the top level.
3. Go to **Settings > Pages**.
4. Under "Build and deployment," choose **Deploy from a branch**, select `main` and `/ (root)`.
5. Save, wait a few minutes, and visit your published URL.

## What to personalize first

- Replace "Your Name" throughout `index.html`.
- Replace `yourusername` in all GitHub/LinkedIn links.
- Replace `you@example.com` with your real email.
- Rewrite the About, Services, and Experience text to match your actual history — the current copy is a
  realistic starting draft based on a food science + AI consulting profile, not generic placeholder text.
- Add your real PDFs to `assets/docs/` and update the Documents section links.
- Add real project links once your repositories are public.
