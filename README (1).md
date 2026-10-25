# Forma — ATS Resume Builder

A lightweight, browser-based resume builder with live preview and ATS-friendly writing checks. No backend, framework, account, or external assets required.

## Run locally

Open `index.html` in a browser, or serve the folder with:

```bash
python3 -m http.server 4173
```

Then visit http://localhost:4173.

## Features

- Editable contact details, summary, experience, education, skills, projects, and certifications
- Live resume preview with Classic, Modern, and Compact styles
- ATS readiness checklist and job-description keyword matching
- Print-to-PDF download
- Browser-local draft saving, plus JSON import/export

## Privacy

Resume data and pasted job descriptions are stored in the browser's local storage. They are not sent to a server.

## GitHub Pages

This is a static site. Push the repository to GitHub, then enable **Settings → Pages → Deploy from a branch**, selecting the `main` branch and `/ (root)`.
