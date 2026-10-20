# Vanesa Dwi Lestari — Developer Portfolio

Modern, responsive, bilingual (English / Bahasa Indonesia) portfolio made with **React + Vite + TypeScript**.

## Run locally

Requirements: Node.js 20.19+ or 22.12+.

```bash
npm install
npm run dev
```

Open the local URL shown by Vite.

## Production build

```bash
npm run build
npm run preview
```

## Deploy on Vercel

1. Create a GitHub repository and push the **contents of this folder** (not `node_modules`).
2. In Vercel, select **Add New → Project** and import the GitHub repository.
3. Vercel should detect **Vite** automatically. If not, choose Framework Preset `Vite`, Build Command `npm run build`, Output Directory `dist`.
4. Deploy. Subsequent pushes to your production branch will redeploy automatically.

## Edit your details

- `src/content.ts` contains the bilingual copy, skills, projects, certificate data and contact information.
- Add your GitHub profile URL to `profile.github` in `src/content.ts` to show the GitHub social link.
- `public/assets/vanesa-profile.png` is the profile photo cropped from the supplied CV.
- `public/assets/Vanesa-Dwi-Lestari-Resume-English.pdf` and `public/assets/Vanesa-Dwi-Lestari-Resume-Indonesia.pdf` are the latest supplied resumes. The Download CV button selects the corresponding file for the active language. Both files include a phone number; consider public-safe versions before publishing.
- Certificate images are in `public/assets/`. The DPR RI internship certificate preview has the student ID redacted and does **not** include the evaluation appendix. Its summary score is mentioned in the copy.
- Internal application source code and unprovided repository/demo URLs have intentionally **not** been invented.
- The third project is an explicitly marked placeholder. Replace with a verified project when ready.

## Features

- English / Indonesian switcher with `localStorage` persistence
- Mobile navigation and responsive layout
- CSS animation with reduced-motion support
- Interactive project overview dialogs
- Certificate gallery with keyboard arrows and Escape support
- Contact `mailto:` link and copy-email button
- SEO title/description and favicon
- Language-aware resume download (English or Bahasa Indonesia)

## Privacy checklist before publishing

- Check whether you want your email address and phone number in the public CV.
- Review all personal details and photographs.
- Ensure that any additional institutional project screenshots are approved for public use.
- The internship certificate is intentionally displayed as a redacted preview.

## Note

The portfolio itself is static and does not require a backend. This is appropriate for Vercel deployment; "Full-Stack Developer" describes the portfolio owner's skills rather than the architecture of this portfolio site.


## Editorial hero redesign
The hero now features a large name and the portrait from the resume. English/Indonesian language switching, certificates, and CV downloads are preserved.


## Project images (V3)
- `public/assets/sincan-planning-preview.webp`: screenshot supplied by portfolio owner, with form values blurred for public display.
- `public/assets/dpr-survey-preview.webp`: screenshot supplied by portfolio owner, with visible personal form entries and local session URL blurred.
- Both are previews of internship projects, not live demos. Do not upload original unredacted screenshots to a public repository.
- Sentiment analysis thesis card has been replaced with the DPR RI online survey internship project in both EN and ID.


## V4 editorial case studies

The two internship projects now include bilingual case studies covering context, challenges, personal contributions, workflow, and learnings. The third placeholder project is intentionally hidden until a verified project is available. Images are from the supplied internship screenshots with sensitive fields obscured. No internal source code is distributed.
