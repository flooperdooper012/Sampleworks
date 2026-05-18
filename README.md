# Clean Spark Cleaning Services — Website

A responsive, single-page website for **Clean Spark Cleaning Services**, built with pure HTML, CSS, and JavaScript. No frameworks or dependencies required.

## 🚀 Live Demo (GitHub Pages)

Once deployed, your site will be live at:
`https://<your-username>.github.io/cleanspark-website/`

## 📁 Project Structure

```
cleanspark-website/
├── index.html       # Main website (all CSS & JS included)
└── README.md        # This file
```

## ✨ Features

- Fully responsive (mobile, tablet, desktop)
- Sticky navigation bar
- Hero section with animated elements
- Stats bar
- Services grid (6 services)
- How It Works section
- Customer Reviews / Testimonials
- Contact form with quote request
- Footer with links

## 🌐 How to Deploy on GitHub Pages

1. **Create a new GitHub repository**
   - Go to [github.com](https://github.com) → click **New repository**
   - Name it `cleanspark-website` (or anything you like)
   - Set it to **Public**
   - Click **Create repository**

2. **Upload the files**
   - Click **Add file → Upload files**
   - Drag and drop `index.html` and `README.md`
   - Click **Commit changes**

3. **Enable GitHub Pages**
   - Go to your repo → **Settings** → **Pages**
   - Under **Source**, select `main` branch and `/ (root)` folder
   - Click **Save**
   - Wait ~1 minute, then visit the link shown!

## 🛠 Local Development

Just open `index.html` in any browser — no build step needed.

```bash
# Optional: serve locally with Python
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## 📝 Customization

All content is in `index.html`. Key things to update:
- **Phone / Email / Address** — search for the contact section
- **Service descriptions** — in the `#services` section
- **Testimonials** — in the `#reviews` section
- **Colors** — edit the CSS variables at the top (`:root { ... }`)
