<!-- HEADER BANNER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7a1722,50:9b1d2c,100:d4a017&height=210§ion=header&text=Aaditi's%20House%20of%20Banaras&fontSize=38&fontColor=ffe8a3&fontAlignY=38&desc=Authentic%20Handloom%20Silk%20Sarees%20%26%20Home%20Decor%20from%20Varanasi&descSize=16&descColor=fdf8f0&descAlignY=58" width="100%" alt="Aaditi's House of Banaras Header Banner" />
</div>

<div align="center">

[![Live Demo](https://img.shields.io/badge/🌐_Live_Website-Visit_Storefront-7a1722?style=for-the-badge&labelColor=d4a017)](https://kanak0091.github.io/web-dev-capstone/)
![HTML5](https://img.shields.io/badge/HTML5-Semantic_Markup-7a1722?style=for-the-badge&logo=html5&logoColor=ffe8a3)
![CSS3](https://img.shields.io/badge/CSS3-Grid_&_Flexbox-9b1d2c?style=for-the-badge&logo=css3&logoColor=ffe8a3)
![Responsive](https://img.shields.io/badge/Design-Mobile_First_Responsive-d4a017?style=for-the-badge&labelColor=222222)

**Crafted with heritage & code by [Kanak](https://github.com/Kanak0091) | Web Development Lab 5 Capstone**

</div>

---

## ✨ About the Project

> *"From Weaver's Heart to Your Home — Pure Banaras Craft."*

**Aaditi's House of Banaras** is a responsive, multi-page e-commerce storefront designed for a traditional Banarasi handloom brand rooted in **Mumbai & Varanasi**. Built completely from scratch using semantic **HTML5** and modern **CSS3**, this UI redesign concept brings the warmth of Katan silk, antique gold zari brocade, and heirloom craftsmanship to the web.

---

## 🎨 Brand Colour Palette

The visual identity draws directly from traditional Banarasi wedding silks and temple-border zari work:

| Swatch | Role | Hex Code | Usage in UI |
| :---: | :--- | :--- | :--- |
| ![#7a1722](https://placehold.co/24x24/7a1722/7a1722.png) | **Banarasi Maroon** | `#7A1722` | Sticky header, footer, headings & primary CTAs |
| ![#d4a017](https://placehold.co/24x24/d4a017/d4a017.png) | **Antique Zari Gold** | `#D4A017` | Section dividers, border accents & cart buttons |
| ![#fdf8f0](https://placehold.co/24x24/fdf8f0/fdf8f0.png) | **Raw Silk Cream** | `#FDF8F0` | Hero banner, alternating sections & testimonial cards |
| ![#ffe8a3](https://placehold.co/24x24/ffe8a3/ffe8a3.png) | **Soft Gold Tissue** | `#FFE8A3` | Brand title highlight & footer social links |
| ![#222222](https://placehold.co/24x24/222222/222222.png) | **Charcoal Ink** | `#222222` | High-contrast readable body typography |

---

## 🛍️ Pages & Storefront Experience

| Page | File | Key Highlights |
| :--- | :--- | :--- |
| **🏠 Home** | `index.html` | Sticky maroon-and-gold header, accessible skip link, animated welcome hero banner, and 4-column **Featured Highlights** grid. |
| **🧵 Collections** | `collections.html` | Curated 4-column showcase of **Banarasi Silk Sarees**, **Zari Handbags**, **Cushion Covers**, and **Table Runners** with weave details. |
| **🛒 Products** | `products.html` | Full **12-product catalog** featuring real handloom photography, detailed descriptions, INR (`₹`) pricing, and interactive `Add to Cart` buttons. |
| **💛 Why Us** | `about.html` | Brand pillars (authentic Varanasi weaver sourcing, pure silk fabrics, free pan-India shipping above ₹2,000) and verified buyer reviews. |
| **📩 Order Inquiry** | `contact.html` | Accessible custom-order form with paired `<label>` elements, category dropdown selector, HTML5 validation, and instant confirmation popup. |

---

## 📐 Responsive Architecture & CSS Highlights

- **Semantic HTML5 Structure:** Cleanly organized using `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>` landmarks.
- **CSS Custom Properties (`:root`):** Centralized colour tokens and relative `rem` units for scalable spacing and typography.
- **CSS Grid & Flexbox:**
  - **Flexbox** aligns the sticky navigation bar, full-height sticky footer layout, and uniform product card action buttons.
  - **CSS Grid** drives the responsive category showcase, 12-item product catalog, and customer feedback cards.
- **Adaptive Breakpoints:**
  - 🖥️ **Desktop (`> 1024px`):** `4-column` grid (`repeat(4, 1fr)`) for product and collection cards.
  - 📱 **Tablet (`≤ 1024px`):** `2-column` grid (`repeat(2, 1fr)`) for balanced medium-screen viewing.
  - 📲 **Mobile (`≤ 768px`):** `1-column` (`1fr`) stacked layout with centered header navigation.

---

## 📂 Repository Structure

```text
web-dev-capstone/
├── index.html                  # Landing page with hero banner & category highlights
├── collections.html            # Handloom collections overview
├── products.html               # 12-item product catalog with INR pricing
├── about.html                  # Brand story, USPs & customer testimonials
├── contact.html                # Custom order & inquiry form
├── style.css                   # Theme variables, Grid/Flexbox layouts & responsive queries
├── README.md                   # Project documentation
└── *.jpg / *.jpeg              # 12 authentic Banarasi handloom product & category photos
