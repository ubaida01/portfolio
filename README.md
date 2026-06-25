# Portfolio of Abu Ubaida

A responsive personal portfolio website built with plain HTML, CSS, and JavaScript.

## Features

- Responsive single-page portfolio layout
- Hero, About, Skills, Experience, Projects, Certifications, Education, and Contact sections
- Dark mode toggle
- Animated typing text
- Scroll reveal effects
- Certifications carousel
- Contact form integration with Formspree
- Self-contained local image assets

## Tech Stack

- `HTML`
- `CSS`
- `JavaScript`

## Project Structure

```text
.
├── assets/
│   ├── certifications/
│   ├── projects/
│   └── ui/
├── index.html
├── script.js
├── styles.css
└── README.md
```

## Run Locally

Because this is a static site, you can open `index.html` directly or use a simple local server.

Example with Python:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

## Customize Content

Most editable content is stored in the `portfolioData` object near the top of [script.js](./script.js).

You can update:

- Navigation links
- Hero text
- About cards
- Skills
- Projects
- Experience
- Certifications
- Education
- Contact links
- Formspree endpoint

## Customize Styling

Main styles are in [styles.css](./styles.css).

You can easily change:

- Colors
- Spacing
- Typography
- Card styles
- Section backgrounds
- Animations

## Deployment

You can deploy this project on any static hosting platform, including:

- Vercel
- Netlify
- GitHub Pages

## Notes

- Images are stored locally in `assets/` for easier editing and portability.
- The contact form currently posts to Formspree. Replace the endpoint in `script.js` if you want to use your own form handler.

## License

This project is for personal portfolio use. Update the content, assets, and branding before publishing as your own public portfolio.
