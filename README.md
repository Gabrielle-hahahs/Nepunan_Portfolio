# Green Mint Portfolio

A responsive student e-portfolio built with React, Vite, and Tailwind CSS v4.

## Requirements covered
- Home / Dashboard with welcome message, introduction, and navigation
- About Me with background, skills, and interests
- Projects / Work Samples with descriptions and interactive project-detail modals
- Resume / CV section with education, experience, and skills
- Contact information, social links, and a validated contact form demo
- React state, event handling, conditional rendering, and responsive layout
- Vercel-ready Vite build

## Run locally
1. Install Node.js (LTS) from https://nodejs.org/
2. Open this project folder in VS Code.
3. Open Terminal in VS Code and run:

   ```bash
   npm install
   npm run dev
   ```

4. Open the local URL printed by Vite, usually `http://localhost:5173`.

## Build check
```bash
npm run build
```

## Deploy to Vercel
1. Upload this project to a GitHub repository.
2. Go to https://vercel.com/ and import the repository.
3. Vercel should detect Vite automatically.
4. Use `npm run build` as the build command and `dist` as the output directory if asked.
5. Deploy, then open the public URL and test the sections, buttons, modal, and form.

## Personalize before submitting
Search the project for these placeholders and replace them:
- `your.email@example.com` — your real email address
- `Cavite State University (edit this with your campus and exact program details)` — your exact school/program
- Sample project entries in `src/App.jsx` — replace or revise them to reflect your own work
- Update the page title and social profile URLs in `index.html` and `src/App.jsx`

## Important note about the contact form
The form currently validates required fields and displays a confirmation state in the browser. It does not send email or store messages. Connect a form backend/service if you need real message delivery.

## CV note
The resume section is ready for your details, but a real downloadable CV PDF has not been attached. Add your own CV and link it from the Resume section if your instructor expects a working download.
