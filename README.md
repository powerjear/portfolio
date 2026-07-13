# Daren Jear Galera — Portfolio Website

A clean, single-page portfolio landing page for **Daren Jear Galera** — GoHighLevel Expert, Funnel Builder, and AI Automation Specialist.

## Tech Stack

- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties, CSS Grid, Flexbox, responsive design
- **Vanilla JavaScript** — No frameworks, no dependencies
- **Google Fonts** — Montserrat (headings) + Inter (body)

## Project Structure

```
daren-portfolio/
├── index.html              # Main landing page
├── css/
│   └── style.css           # All styles
├── js/
│   └── main.js             # Scroll effects, mobile menu, form handler
├── assets/
│   ├── images/             # Add your photos and project screenshots here
│   └── icons/              # Favicon and icon assets
└── README.md
```

## Sections

| Section | Description |
|---------|-------------|
| Navigation | Sticky dark navbar with smooth scroll + mobile hamburger menu |
| Hero | Full-screen dark hero with headline, subheadline, and dual CTAs |
| Stats Bar | 4-column trust bar with key numbers |
| About | Two-column bio section with photo placeholder and skill tags |
| Services | 5 service cards (3+2 grid layout) with checklists |
| Work | 3-column project card grid with tags and outcomes |
| Process | 4-step horizontal process with gold numbered circles |
| CTA Banner | Dark full-width conversion banner |
| Contact | Split layout — contact form + direct contact info |
| Footer | 4-column dark footer |

## Getting Started

1. Clone or download this repository
2. Open `index.html` in any browser — no build step required
3. Customize the placeholders (see below)

## Customization Checklist

### Replace Photo Placeholders
Find the `hero-image-placeholder` and `about-image-placeholder` divs in `index.html` and replace them with:
```html
<img src="assets/images/daren.jpg" alt="Daren Jear Galera">
```

### Update Contact Info
Search for `hello@yourwebsite.com` and replace with your real email address.

### Add Booking Link
Search for `href="#"` near "Schedule a Free Discovery Call" and "Let's Work Together" in the contact section — replace with your Calendly or GoHighLevel booking URL.

### Add Social Links
In the footer, replace the `href="#"` values on LinkedIn, Twitter/X, and Facebook links with your real profile URLs.

### Add Project Screenshots
Replace the `project-thumb` placeholder divs in the Work section with:
```html
<img src="assets/images/project-1.jpg" alt="Project Name">
```

### Connect the Contact Form
The form currently simulates a submission. To make it functional, integrate one of the following:
- **Formspree**: Add `action="https://formspree.io/f/YOUR_ID"` to the `<form>` tag
- **GoHighLevel**: Replace the form with your GHL embedded form code
- **Netlify Forms**: Add `netlify` attribute to the `<form>` tag (if hosting on Netlify)

## Deployment

This is a static site — it can be hosted anywhere:

| Platform | Steps |
|----------|-------|
| **GitHub Pages** | Push to `main` branch → Settings → Pages → Deploy from branch |
| **Netlify** | Drag and drop the folder into netlify.com/drop |
| **Vercel** | `vercel --prod` from the project directory |
| **Cloudflare Pages** | Connect GitHub repo in Cloudflare dashboard |

## Brand Colors

| Token | Value | Usage |
|-------|-------|-------|
| `--primary` | `#1a1a1a` | Backgrounds, headings, dark sections |
| `--accent` | `#C9A227` | CTAs, highlights, borders, icons |
| `--bg` | `#f7f6f2` | Light section backgrounds |
| `--text-body` | `#444444` | Body copy |

---

Built for Daren Jear Galera. Ready to deploy.
