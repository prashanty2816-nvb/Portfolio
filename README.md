# Unnati Rai Portfolio

A responsive React + Vite portfolio inspired by the provided Readdy website recording. Includes a hero profile section, experience timeline, filterable project cards, project detail modals, skills, education, certifications, interests, and a contact form that prepares an email using `mailto:`.

## Run in GitHub Codespaces

1. Upload/extract this project into a GitHub repository or Codespace.
2. Open the terminal in the project folder.
3. Run:

   ```bash
   npm install
   npm run dev -- --host 0.0.0.0
   ```

4. Open the forwarded port shown by Codespaces (Vite defaults to port 5173).

## Build for deployment

```bash
npm run build
```

The production site is generated in `dist/`.

## Customise

- Profile photo: replace `public/assets/unnati-portrait.jpg` with the original portrait file.
- Resume: replace `public/Unnati_Rai_Resume.pdf` with the latest resume.
- Content: edit `src/main.jsx`.
- Colours and responsive styling: edit `src/styles.css`.

## Important notes

- The portrait currently comes from a crop of the provided screen recording. Replace it with the original photo for best image quality.
- Project card illustrations are CSS mockups, not screenshots of the actual PBIX/Excel dashboards. Replace them with real screenshots when available.
- The contact form uses a `mailto:` fallback and does not save submissions to a server. Connect a form provider or backend if server-side submissions are required.
- The SQL script supplied alongside the resume appears to use a music-store dataset. Confirm the project name before presenting it as an e-commerce analysis.
