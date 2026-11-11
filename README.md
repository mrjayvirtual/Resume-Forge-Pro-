# Resume Forge Pro

> Career documents and job-application workspace. Built by MrJayVirtual. Creativity Meets Technology.

Live app: https://resume-forge-pro-mrjayvirtual.vercel.app

## What is implemented
- Resume, CV and cover letter builders with six shared templates and live preview
- Structured sections with start and end dates or Currently: experience, education, certifications, projects, languages, references, skills
- Photo and signature upload (resized in the browser)
- Import of DOCX, PDF and TXT resumes (read on the device)
- Explainable readiness scoring: completeness, job alignment, content quality, formatting
- Job link reader that pulls a public job post into the scorer
- Live job leads from open job boards plus quick search links
- Export: PDF (print dialog), Word (.doc), plain text, copy, share link (with consent prompt)
- Job tracker, document library, readable backup and restore
- Optional AI writing through a server-side provider (Gemini, Groq or OpenAI)

## Known limitations
- Scores are heuristic. They are not produced by any commercial ATS and guarantee nothing.
- AI writing needs a provider key. Without it the app runs in Basic mode.
- Documents live in browser storage. Clearing site data deletes them, so use Backup.
- Share links contain the document text in the URL (photo and signature excluded).
- The free AI run counter is client-side, a soft limit until accounts are added.
- Job leads come from public boards and can be stale. Always verify at the source.

## Stack
Vite, React, Framer Motion, Vercel serverless functions (api/).

## Run locally
```
npm install
npm run dev
```

## Environment variables
See `.env.example`. Never commit real keys.

Crafted by MrJayVirtual (Joshua Ikpendu), JayVirtual.
