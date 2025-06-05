# Image Link Grabber

**Image Link Grabber** is a fully static, client-side web tool that extracts image URLs from any public webpage. Built with vanilla HTML and JavaScript, it uses the free [AllOrigins](https://allorigins.win/) CORS proxy to bypass browser restrictions.

### 🔧 Features
- Paste any public webpage URL
- Instantly see all `<img>` tag sources
- One-click “Copy All” image URLs
- Works entirely on GitHub Pages—no server required

### 🚀 How It Works
Browsers block cross-origin requests by default. This tool fetches the HTML via the public **AllOrigins proxy**, parses the `<img>` tags, and lists them.

You can also host your own proxy using Cloudflare Workers for more control.

### 🖥 Demo
👉 [Live Site on GitHub Pages](https://indishmarketer.github.io/image-link-grabber/)

### 🛠 Tech Stack
- HTML5
- JavaScript (vanilla)
- GitHub Pages
- AllOrigins CORS proxy (or Cloudflare Workers)

### 📦 Self-hosting
Clone or fork this repo and deploy to your own GitHub Pages instance:
```bash
git clone https://github.com/indishmarketer/image-link-grabber.git
