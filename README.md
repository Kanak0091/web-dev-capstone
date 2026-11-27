# Aaditi's House of Banaras — Responsive E-Commerce Storefront (Lab 5 Capstone)

**Submitted by:** Kanak  
**Project Theme:** E-Commerce Store UI (Static HTML5 & CSS3 Redesign Concept)  
**Live Website:** `https://YOUR-USERNAME.github.io/web-dev-capstone/`

---

## Project Overview
**Aaditi's House of Banaras** is a multi-page, responsive e-commerce storefront designed for a traditional Banarasi handloom brand based in Mumbai and Varanasi. Built from scratch using semantic **HTML5** and modern **CSS3**, the website showcases authentic handwoven Banarasi silk sarees, zari tote handbags, brocade cushion covers, and dining table runner sets.

---

## Pages & Sections Implemented
1. **Home (`index.html`):**
   - Sticky top navigation header with brand title, tagline, and accessible skip-to-content link.
   - Animated welcome hero banner with direct call-to-action button.
   - 4-column Featured Highlights grid covering Sarees, Zari Handbags, Cushion Covers, and Table Runners.
2. **Collections (`collections.html`):**
   - Structured 4-column category showcase detailing fabric varieties (Katan, Dola, Tissue, Georgette) and available design counts across each product line.
3. **Products (`products.html`):**
   - 12-item responsive product catalog displaying real handloom product photography, itemized descriptions, INR (`₹`) pricing, and interactive `Add to Cart` buttons.
4. **Why Us (`about.html`):**
   - Key brand value propositions (direct Varanasi weaver sourcing, pure silk fabrics, and pan-India shipping) paired with verified customer feedback cards.
5. **Order Inquiry (`contact.html`):**
   - Accessible custom order and inquiry form featuring paired `<label>` elements, HTML5 validation (`required`), category dropdown selection, and instant confirmation feedback.

---

## Technical Architecture & Layout Techniques
- **Semantic HTML5:** Uses `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>` for clean document structure and accessibility.
- **CSS Custom Properties (`:root`):** Centralized colour palette (`--maroon: #7a1722`, `--gold: #d4a017`, `--cream: #fdf8f0`) and relative `rem` sizing for consistent visual hierarchy.
- **CSS Grid & Flexbox:**
  - **Flexbox** structures the sticky header, full-height sticky footer layout, internal product card alignment, and social links row.
  - **CSS Grid** powers the multi-column category cards, 12-product catalog grid, and customer testimonial layout.
- **Responsive Breakpoints:**
  - **Desktop (`> 1024px`):** 4-column grid layout across categories and products (`repeat(4, 1fr)`).
  - **Tablet (`≤ 1024px`):** 2-column grid layout (`repeat(2, 1fr)`) for balanced spacing on medium screens.
  - **Mobile (`≤ 768px`):** Single-column (`1fr`) stacked layout with centered navigation and touch-friendly spacing.

---

## Project File Structure
```text
web-dev-capstone/
├── index.html              # Home page with hero banner & category highlights
├── collections.html        # Product collections overview
├── products.html           # 12-item product catalog with pricing
├── about.html              # Brand story, USPs & customer reviews
├── contact.html            # Accessible order inquiry form
├── style.css               # Global styles, CSS variables, Grid/Flexbox & media queries
├── README.md               # Project documentation
└── *.jpg / *.jpeg          # Product and category photography (12 assets)
