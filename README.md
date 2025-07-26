## Saim’s Personal Branding Site

This repository contains the source code for Saim’s personal branding site, hosted with **GitHub Pages** and powered by **Jekyll** and **Tailwind CSS**. It’s designed to be minimal, fast and easy to update.

### ✨ Features

- Responsive layout with a clean teal accent and generous white space
- Hero banner with a call‑to‑action button linking to your résumé
- About section highlighting your work at Tuscan Consulting and on WorkPlus
- Expertise grid driven by data in `_config.yml`
- Case studies carousel and testimonials slider powered by Alpine.js
- Automatic blog index that lists Markdown posts from `_posts`
- Contact form using [Formspree](https://formspree.io) – just set your form endpoint
- Open Graph meta tags, Google Analytics integration and a generated sitemap

### 🛠 Editing Content

- **Configuration:** Most content is stored in `_config.yml`. Update the `title`, `description`, `tagline`, `resume_url`, `expertise`, `case_studies`, `testimonials`, `formspree_endpoint` and other fields to customise the site.
- **Blog posts:** Add Markdown files to the `_posts` folder with a filename in the format `YYYY‑MM‑DD‑slug.md`. Jekyll automatically builds a blog index section on the home page.
- **Images:** Case study images use the [Unsplash Source API](https://source.unsplash.com). Replace the `image` URLs in `_config.yml` with your own hosted images if desired. Upload additional assets to the `assets` folder.
- **Résumé:** Replace `assets/resume.pdf` with your actual résumé file and update `resume_url` if you change the location.
- **Formspree:** Sign up for a free Formspree account and replace the `formspree_endpoint` value with your unique form URL so that the contact form submissions are delivered to your email.
- **Analytics:** Insert your Google Analytics measurement ID in the `google_analytics` field to enable tracking.

### 🚀 Deployment

1. Commit and push your changes to the `main` branch.
2. In your GitHub repository settings, enable **GitHub Pages** and select the `main` branch as the source.
3. Your site will be available at `https://<your-username>.github.io/<repository-name>` after a few minutes.

### 📝 License

This project is licensed under the [MIT License](LICENSE) unless stated otherwise.
