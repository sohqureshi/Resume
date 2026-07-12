# Resume

A simple, stylish, and printable resume website built with HTML, CSS, and JavaScript. The content is driven by a JSON file so it is easy to update and reuse.

## Live Page
[View Resume](https://sohqureshi.github.io/Resume/)

## Features
- Clean, modern resume layout
- Printable/PDF-friendly design
- SEO-ready meta tags and structured data
- Social links opening in new tabs
- Content managed through JSON

## Files
- index.html — main page structure and styling
- resume-data.json — resume content such as summary, skills, experience, and contact information
- README.md — project overview and usage instructions

## Run Locally
1. Open the project folder.
2. Start a local server, for example:
   ```bash
   python -m http.server 8000
   ```
3. Open your browser at:
   ```text
   http://localhost:8000/
   ```

## Update Resume Content
Edit the values in resume-data.json to change the name, title, summary, skills, projects, education, and contact details.

## Notes
- The page uses local JSON loading, so opening the HTML file directly may not work in some browsers.
- Using a local server is recommended for the best experience.
