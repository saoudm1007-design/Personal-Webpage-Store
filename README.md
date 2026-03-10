# CyberSecurePro — Cybersecurity Services Landing Page

A professional cybersecurity services landing page with interactive tools and full Arabic/English bilingual support.

## Features

- **Service Packages** — Starter, Professional, and Enterprise tiers
- **Interactive Security Tools**
  - Password Strength Checker
  - Security ROI Calculator
  - Security Knowledge Quiz
- **Consultation Booking** — Schedule sessions with available time slots
- **Blog Section** — Latest cybersecurity articles and insights
- **Newsletter Signup** — Security updates subscription
- **Live Chat** — Built-in chat interface
- **Dark / Light Mode** — Theme toggle with saved preference
- **Arabic / English** — Full RTL/LTR bilingual support

## Tech Stack

- Pure HTML, CSS, JavaScript
- No frameworks, no dependencies
- No backend required — fully static

## Deployment

Since this is a static site, it can be hosted anywhere:

- GitHub Pages
- Nginx / Apache
- Netlify / Vercel
- Any static hosting provider

### Nginx example

```nginx
server {
    listen 80;
    server_name your-domain.com;
    root /var/www/your-site;
    index index.html;
}
```

## Project Structure

```
├── index.html       # Main page (all-in-one)
├── favicon.svg      # Site icon
└── README.md
```

## License

MIT
