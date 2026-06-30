# Hossein Jafari Sharmi — Portfolio

A single-page personal portfolio/resume site built with plain HTML, CSS, and JavaScript (no frameworks, no build step).

🔗 **Live site:** https://shjafari80.github.io/main/

## Features
- Responsive one-page layout: Home, About, Skills, Projects, Experience, Contact
- Scroll-triggered animations via `IntersectionObserver`
- Interactive floating skills panel
- Contact form wired to [Formspree](https://formspree.io) (no backend required)
- SEO meta tags, Open Graph/Twitter cards, and JSON-LD structured data
- `robots.txt`, `sitemap.xml`, and a custom `404.html`

## Project structure
```
.
├── index.html        # Main page markup
├── styles.css         # All styling
├── script.js          # Animations, nav, skills panel, form handling
├── content/           # Images, icons, favicon, resume PDF
├── robots.txt
├── sitemap.xml
└── 404.html
```

## Setup
No build tools needed. Clone and open `index.html` in a browser, or serve locally:
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Configuring the contact form
This site uses Formspree to send contact form messages without a backend:
1. Create a free account at [formspree.io](https://formspree.io) and create a new form.
2. Copy your form ID and replace `YOUR_FORM_ID` in `index.html`'s `<form action="https://formspree.io/f/YOUR_FORM_ID">`.
3. Submit the form once to confirm your email address with Formspree.

## Adding your resume
Drop your resume PDF into `content/resume.pdf` — the "Download Resume" button already points there.

## Adding project/social links
Several project case-study links and social icons were placeholders and have been
either removed or marked as "coming soon" until real URLs are available. Search
`index.html` for `is-disabled` to find and update them.

## License
MIT — see [LICENSE](LICENSE).
