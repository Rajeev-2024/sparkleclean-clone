# SparkleClean

A responsive, multi-page frontend for a professional cleaning service. The site presents cleaning services, pricing, company information, articles, and contact options.

## Pages

- `index.html` — Home page with service highlights, testimonials, and a cleaning request form
- `about.html` — Company information and team details
- `service.html` — Cleaning service descriptions
- `pricing.html` — Pricing plans
- `blog.html` — Cleaning tips and articles, with a newsletter section
- `contact.html` — Contact details and inquiry form

## Features

- Responsive layouts for desktop and mobile screens
- Shared navigation with a mobile menu
- Individual stylesheets for each page, plus shared site styles
- Local images and branding assets
- Font Awesome icons loaded from a CDN

## Run locally

No build tools or package installation are required. Download or clone the repository, then open `index.html` in a modern web browser. For a local web server, you can also use the **Live Server** extension in Visual Studio Code.

Keep the `images/` and `stylesfolder/` directories alongside the HTML files so the page styles and images load correctly. An internet connection is needed to load the Font Awesome stylesheet from its CDN.

## Project structure

```text
.
├── index.html
├── about.html
├── service.html
├── pricing.html
├── blog.html
├── contact.html
├── images/
└── stylesfolder/
    ├── style.css
    ├── about.css
    ├── service.css
    ├── pricing.css
    ├── blog.css
    └── contact.css
```

## Notes

The contact and cleaning request forms are frontend elements. Connect them to a form service or backend before using them to collect or send submissions.
