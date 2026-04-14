# 🌿 Shopify Theme Custom — Luar biasa & tanpa antarmuka templat

> A custom Shopify theme collection — a modern, clean, and responsive storefront built with Liquid, HTML, CSS, and JavaScript.

---

## 📁 Project Structure

```
shopify-store-vegetl/
├── 📂 layout/
│   └── theme.liquid              # Main layout template (header, footer, global)
│
├── 📂 templates/
│   ├── index.liquid              # Homepage
│   ├── product.liquid            # Product detail page
│   ├── collection.liquid         # Collection / category page
│   ├── cart.liquid               # Shopping cart
│   ├── page.liquid               # Static pages
│   ├── blog.liquid               # Blog listing
│   ├── article.liquid            # Single blog post
│   └── 404.liquid                # Not found page
│
├── 📂 sections/
│   ├── header.liquid             # Site header & navigation
│   ├── footer.liquid             # Site footer
│   ├── hero-banner.liquid        # Homepage hero section
│   ├── featured-products.liquid  # Featured products grid
│   └── announcement-bar.liquid   # Top announcement bar
│
├── 📂 snippets/
│   ├── product-card.liquid       # Reusable product card component
│   ├── breadcrumb.liquid         # Breadcrumb navigation
│   ├── pagination.liquid         # Pagination component
│   └── icon.liquid               # SVG icon helper
│
├── 📂 assets/
│   ├── style.css                 # Main stylesheet
│   ├── theme.js                  # Main JavaScript file
│   └── *.png / *.svg             # Images & icons
│
├── 📂 config/
│   ├── settings_schema.json      # Theme settings (colors, fonts, etc.)
│   └── settings_data.json        # Saved theme settings
│
├── 📂 locales/
│   └── en.default.json           # Default language strings
│
└── 📄 README.md                  # You are here
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) `v18+`
- [Shopify CLI](https://shopify.dev/docs/themes/tools/cli) `v3.59+`
- A [Shopify Partner Account](https://partners.shopify.com) with a Development Store

### Installation

```bash
# 1. Clone this repository
git clone https://github.com/your-username/shopify-store-vegetl.git
cd shopify-store-vegetl

# 2. Install Shopify CLI (if not already installed)
npm install -g @shopify/cli

# 3. Login to your Shopify Partner account
shopify auth login

# 4. Start local development server
shopify theme dev --store=your-store.myshopify.com
```

Then open your browser at:
```
http://localhost:9292
```

---

## 🛠️ Development Workflow

```
Edit files in VS Code
        ↓
Preview at localhost:9292   ← auto live reload
        ↓
Test across devices
        ↓
shopify theme push          ← upload to Shopify
        ↓
Preview in Shopify Admin
        ↓
Publish as active theme ✅
```

---

## 📦 Useful Commands

| Command | Description |
|---|---|
| `shopify theme dev` | Start local dev server with live reload |
| `shopify theme push` | Upload theme to Shopify |
| `shopify theme pull` | Download latest theme from Shopify |
| `shopify theme list` | List all themes in your store |
| `shopify theme publish` | Set theme as active/live |
| `shopify theme delete` | Remove a theme from your store |

---

## 🎨 Theme Customization

You can customize the theme via:

1. **Shopify Admin** → Online Store → Themes → Customize
2. **Editing `config/settings_schema.json`** for custom settings fields
3. **Editing `assets/style.css`** for global styles
4. **Editing section files** in `/sections` for layout changes

---

## 🧩 Tech Stack

| Technology | Purpose |
|---|---|
| **Liquid** | Shopify's templating language |
| **HTML5** | Page structure |
| **CSS3** | Styling & layout |
| **JavaScript (ES6+)** | Interactivity |
| **Shopify CLI** | Local development & deployment |

---

## 📌 Notes

- Always **duplicate your theme** before making changes in production
- Use `shopify theme dev` for local testing — never edit the live theme directly
- Keep `settings_data.json` out of version control if it contains sensitive store data
- Test on mobile viewport before publishing

---

## 📄 License

This project is private and intended for **Vegetl store** use only.

---

<div align="center">
  Built with me 💚 using Shopify & Liquid
</div>
