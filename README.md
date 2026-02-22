<div align="center">

<br/>

```
✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦
```

# REIGN Atelier

### Premium Luxury Shopify Theme

*Crafted for high-end fashion, jewelry & lifestyle brands*

```
✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦
```

<br/>

[![Shopify OS 2.0](https://img.shields.io/badge/Shopify-OS%202.0-96BF48?style=for-the-badge&logo=shopify&logoColor=white)](https://shopify.dev/docs/themes/os20)
[![Sections](https://img.shields.io/badge/Sections-75%2B-C9A96E?style=for-the-badge)](#sections)
[![Zero Dependencies](https://img.shields.io/badge/JS-Zero%20Dependencies-1A1A1A?style=for-the-badge&logo=javascript&logoColor=C9A96E)](#architecture)
[![WCAG 2.1](https://img.shields.io/badge/Accessibility-WCAG%202.1%20AA-4A90A4?style=for-the-badge)](#accessibility)
[![License](https://img.shields.io/badge/License-Single%20Store-E8D5B0?style=for-the-badge)](#license)

<br/>

**[🛍 View on Shopify Theme Store](https://themes.shopify.com/themes/reign-atelier?token=eyJwYXJ0bmVyX2lkIjo0NTk3MjEwLCJtZW1iZXJzaGlwX3VzZXJfaWRlbnRpdHlfaWQiOiI2NWVmYmYwNC05NjUyLTRkOGYtYmQxZS1jNjQzZWM5OWE3YTUiLCJ0aW1lc3RhbXAiOjE3NzE3ODM3Mjd9--b4fc9f2b5b3cc41167f5efc7de18a43760945903#Reviews)**
&nbsp;&nbsp;·&nbsp;&nbsp;
**[📖 Read the Docs](https://reignatelier.nexevai.com/)**
&nbsp;&nbsp;·&nbsp;&nbsp;
**[✉ Contact Support](mailto:rayeesyousuf80@gmail.com)**

<br/>

</div>

---

## Table of Contents

- [Overview](#overview)
- [Features at a Glance](#features-at-a-glance)
- [Sections Reference](#sections-reference)
- [Theme Settings](#theme-settings)
- [Architecture](#architecture)
- [Page Templates](#page-templates)
- [Performance](#performance)
- [Accessibility](#accessibility)
- [Installation](#installation)
- [Documentation](#documentation)
- [Support](#support)
- [License](#license)
- [Changelog](#changelog)

---

## Overview

**REIGN Atelier** is a luxury Shopify theme engineered from the ground up for high-end fashion, jewelry, accessories, and lifestyle brands. It pairs editorial elegance with serious commerce infrastructure — a complete, zero-compromise storefront on Shopify Online Store 2.0.

Every pixel, interaction, and line of code is crafted to match the visual standards of luxury brands — without sacrificing the conversion mechanics that make a store commercially successful.

```
Built by Nexevai  ·  Developer: Rayees Yousuf  ·  Version 1.0.0  ·  February 2026
```

---

## Features at a Glance

| Feature | Details |
|---|---|
| **Platform** | Shopify Online Store 2.0 — JSON templates, App Blocks, Section Everywhere |
| **Sections** | 75+ drag-and-drop sections, fully configurable in the native Customizer |
| **JavaScript** | Zero external dependencies — 100% vanilla ES6+, no jQuery |
| **Performance** | Lazy loading, responsive images via `srcset`, deferred scripts, Section Rendering API |
| **Accessibility** | WCAG 2.1 AA foundations — ARIA, keyboard nav, focus states, reduced-motion |
| **Animations** | Scroll reveals, parallax, character-reveal text, magnetic hover, 3D tilt |
| **Cart** | AJAX drawer cart with free-shipping bar, upsell product, and order notes |
| **Mobile** | Mobile-first responsive design + optional fixed mobile bottom nav bar |
| **Search** | Live predictive search with product images and prices |
| **Typography** | Dual-font system via Shopify Font Picker — heading serif + body sans |
| **Colors** | Full CSS custom property system — every color token set in the Customizer |
| **Localization** | All strings translatable via `en.default.json` |

---

## Sections Reference

> 75+ fully configurable drag-and-drop sections across 8 categories.
> Every section exposes granular controls for spacing, colors, typography, animation, and scoped custom CSS — no code required.

### 🎬 Hero Sections

<table>
<tr>
<th>Section</th>
<th>File</th>
<th>Key Features</th>
</tr>
<tr>
<td><strong>Hero Banner</strong></td>
<td><code>hero-banner.liquid</code></td>
<td>Full-width background image, overlay, heading, rich text, CTA button, configurable height</td>
</tr>
<tr>
<td><strong>Hero Simple</strong></td>
<td><code>hero-simple.liquid</code></td>
<td>Separate desktop/mobile images, overlay opacity, text position, button</td>
</tr>
<tr>
<td><strong>Hero Collection</strong></td>
<td><code>advanced-hero-collection.liquid</code></td>
<td>Full-bleed editorial hero — eyebrow tag, heading, subheading, CTA, all alignment/animation controls</td>
</tr>
<tr>
<td><strong>Slideshow</strong></td>
<td><code>slideshow.liquid</code></td>
<td>Multi-slide carousel, autoplay, arrows, dots — each slide has own image/text/CTA</td>
</tr>
<tr>
<td><strong>Split Screen</strong></td>
<td><code>split-screen.liquid</code></td>
<td>50/50 media + text — supports video, image shape masks, all content block types</td>
</tr>
</table>

### 🗂 Collection Sections

<table>
<tr>
<th>Section</th>
<th>File</th>
<th>Key Features</th>
</tr>
<tr>
<td><strong>Featured Collection</strong></td>
<td><code>featured-collection.liquid</code></td>
<td>Grid from any collection, columns 2–4, quick view, vendor, View All</td>
</tr>
<tr>
<td><strong>Featured Collection Grid</strong></td>
<td><code>featured-collection-grid.liquid</code></td>
<td>Editorial grid — image ratio, hover swap, quick add, sale badges, gap control</td>
</tr>
<tr>
<td><strong>Collection List</strong></td>
<td><code>home-collection-list.liquid</code></td>
<td>Multi-collection image tile grid — "Shop by Category" style</td>
</tr>
<tr>
<td><strong>Collection Tabs (AJAX)</strong></td>
<td><code>collection-tabs-ajax.liquid</code></td>
<td>Tab switching between collections without page reload — up to 5 tabs, configurable tab style</td>
</tr>
<tr>
<td><strong>Collection Banner</strong></td>
<td><code>collection-banner.liquid</code></td>
<td>Full-width banner for collection pages with background image</td>
</tr>
<tr>
<td><strong>Category Tags</strong></td>
<td><code>category-tags.liquid</code></td>
<td>Pill-style tag navigation strip — each tag is a block with label + URL</td>
</tr>
</table>

### 🛒 Product Sections

<table>
<tr>
<th>Section</th>
<th>File</th>
<th>Key Features</th>
</tr>
<tr>
<td><strong>Featured Product</strong></td>
<td><code>featured-product.liquid</code></td>
<td>Full buy interface (gallery, variants, ATC) for any product, anywhere on the page</td>
</tr>
<tr>
<td><strong>Product Carousel</strong></td>
<td><code>product-carousel.liquid</code></td>
<td>Horizontal touch-swipe carousel from a collection, autoplay, eyebrow/heading/subtitle</td>
</tr>
<tr>
<td><strong>Advanced Product Carousel</strong></td>
<td><code>advanced-product-carousel.liquid</code></td>
<td>Enhanced carousel — image swap, swatch hover preview, quick add, custom color palette per section</td>
</tr>
<tr>
<td><strong>Vertical Product Carousel</strong></td>
<td><code>vertical-product-carousel.liquid</code></td>
<td>Infinite vertical scroll ticker in multiple columns, pause on hover, alternate direction</td>
</tr>
<tr>
<td><strong>Trending Products Reveal</strong></td>
<td><code>trending-products-reveal.liquid</code></td>
<td>Oversized background text + product grid with scroll-reveal animation</td>
</tr>
<tr>
<td><strong>Product Card Hover Showcase</strong></td>
<td><code>product-card-hover-showcase.liquid</code></td>
<td>Luxury hover grid — secondary image, color/size swatch preview, custom overlay, ATC on hover</td>
</tr>
<tr>
<td><strong>Product Tabs</strong></td>
<td><code>product-tabs.liquid</code></td>
<td>Tab-based product showcase, one collection per tab block</td>
</tr>
</table>

### ✍️ Content Sections

<table>
<tr>
<th>Section</th>
<th>File</th>
<th>Key Features</th>
</tr>
<tr>
<td><strong>Image with Text</strong></td>
<td><code>image-with-text.liquid</code></td>
<td>Classic 50/50 layout — image left or right, heading/text/button blocks</td>
</tr>
<tr>
<td><strong>Image with Text Overlay</strong></td>
<td><code>image-with-text-overlay.liquid</code></td>
<td>Full-bleed image/video — parallax, Ken Burns hover, popup video, overlay opacity</td>
</tr>
<tr>
<td><strong>Split Image & Text</strong></td>
<td><code>split-image-text.liquid</code></td>
<td>Optional sticky image on desktop scroll — for long-form editorial content</td>
</tr>
<tr>
<td><strong>Rich Text</strong></td>
<td><code>rich-text.liquid</code></td>
<td>Full Shopify rich text editor — headings, captions, text, buttons</td>
</tr>
<tr>
<td><strong>Multi-Column</strong></td>
<td><code>multi-column.liquid</code></td>
<td>2–6 column grid — image, heading, text per column. USP rows, feature highlights</td>
</tr>
<tr>
<td><strong>Icon Row</strong></td>
<td><code>icon-row.liquid</code></td>
<td>SVG icon strip with labels — Free Shipping / Returns / Sustainability rows</td>
</tr>
<tr>
<td><strong>FAQ Accordion</strong></td>
<td><code>faq-accordion.liquid</code></td>
<td>Animated expand/collapse — optional multi-open, max-width, full color scheme control</td>
</tr>
<tr>
<td><strong>Story Timeline</strong></td>
<td><code>story-timeline.liquid</code></td>
<td>Vertical milestone timeline for brand history — year, heading, description, image per block</td>
</tr>
<tr>
<td><strong>Team Members</strong></td>
<td><code>team-members.liquid</code></td>
<td>Photo grid — configurable image shape (square/circle/arch), card style, columns</td>
</tr>
<tr>
<td><strong>Contact Form</strong></td>
<td><code>contact-form.liquid</code></td>
<td>Pre-styled form — floating labels, phone field, inquiry dropdown, info blocks, sidebar image</td>
</tr>
<tr>
<td><strong>Newsletter</strong></td>
<td><code>newsletter.liquid</code></td>
<td>Email capture — connects to Shopify Email, Klaviyo, Omnisend, Mailchimp</td>
</tr>
<tr>
<td><strong>Stats Counter</strong></td>
<td><code>stats-counter.liquid</code></td>
<td>Animated count-up numbers on scroll — suffix support (+, %, K), background image + parallax</td>
</tr>
<tr>
<td><strong>Text Reveal</strong></td>
<td><code>text-reveal.liquid</code></td>
<td>Word-by-word cinematic scroll animation — for brand manifestos & mission statements</td>
</tr>
<tr>
<td><strong>Custom Liquid</strong></td>
<td><code>custom-liquid.liquid</code></td>
<td>Insert any Liquid/HTML/JS anywhere, with color scheme, padding, and scoped CSS</td>
</tr>
<tr>
<td><strong>Spacer</strong></td>
<td><code>spacer.liquid</code></td>
<td>Vertical space with optional decorative divider — desktop/mobile heights independently set</td>
</tr>
</table>

### 🎬 Media Sections

<table>
<tr>
<th>Section</th>
<th>File</th>
<th>Key Features</th>
</tr>
<tr>
<td><strong>Video Section</strong></td>
<td><code>video-section.liquid</code></td>
<td>Full-width video — Shopify-hosted, YouTube, Vimeo. Autoplay, loop, poster image</td>
</tr>
<tr>
<td><strong>Video with Text</strong></td>
<td><code>video-with-text.liquid</code></td>
<td>Side-by-side video + text — aspect ratio, shadow, all content block types</td>
</tr>
<tr>
<td><strong>Interactive Video Parallax</strong></td>
<td><code>interactive-video-parallax.liquid</code></td>
<td>3D tilt + parallax video — oversized background text, configurable tilt axes and parallax speed</td>
</tr>
<tr>
<td><strong>Gallery Masonry</strong></td>
<td><code>gallery-masonry.liquid</code></td>
<td>Pinterest-style masonry grid — configurable columns, row height, gap, overlay text per image</td>
</tr>
<tr>
<td><strong>Image Banner</strong></td>
<td><code>image-banner.liquid</code></td>
<td>Standalone image with optional heading/text/CTA overlay — configurable height</td>
</tr>
<tr>
<td><strong>Before / After Slider</strong></td>
<td><code>before-after.liquid</code></td>
<td>Interactive drag slider comparing two images — for product transformations, campaigns</td>
</tr>
<tr>
<td><strong>Brand Logos</strong></td>
<td><code>brand-logos.liquid</code></td>
<td>Logo grid — stockists, press, certifications</td>
</tr>
<tr>
<td><strong>Logo List</strong></td>
<td><code>logo-list.liquid</code></td>
<td>Compact logo strip — simpler alternative to Brand Logos</td>
</tr>
</table>

### ✨ Interactive Sections

<table>
<tr>
<th>Section</th>
<th>File</th>
<th>Key Features</th>
</tr>
<tr>
<td><strong>Image Hotspot</strong></td>
<td><code>image-hotspot.liquid</code></td>
<td>Shoppable tags on any image — hotspot markers with tooltip info cards</td>
</tr>
<tr>
<td><strong>Shop The Look</strong></td>
<td><code>shop-the-look-hotspots.liquid</code></td>
<td>Full lookbook with animated pulsing product hotspots — quick-view card with ATC</td>
</tr>
<tr>
<td><strong>Lookbook</strong></td>
<td><code>lookbook.liquid</code></td>
<td>Editorial lookbook with tappable product markers</td>
</tr>
<tr>
<td><strong>Interactive Split Showcase</strong></td>
<td><code>interactive-split-showcase.liquid</code></td>
<td>Full-viewport hover-expand product panels — name, price, description, CTA per panel</td>
</tr>
</table>

### 🌟 Social Proof Sections

<table>
<tr>
<th>Section</th>
<th>File</th>
<th>Key Features</th>
</tr>
<tr>
<td><strong>Wall of Love</strong></td>
<td><code>reviews-wall.liquid</code></td>
<td>Masonry review card grid — stars, headline, quote, avatar initials, summary text, CTA</td>
</tr>
<tr>
<td><strong>Testimonials Grid</strong></td>
<td><code>testimonials-grid.liquid</code></td>
<td>Clean testimonial grid — quote size, shadow, border, avatar, stars, columns</td>
</tr>
<tr>
<td><strong>Testimonials</strong></td>
<td><code>testimonials.liquid</code></td>
<td>Simple testimonial carousel/stack</td>
</tr>
<tr>
<td><strong>Trust Badges</strong></td>
<td><code>trust-badges.liquid</code></td>
<td>Security/trust icon strip — layout type, icon position, card style, shadow, columns</td>
</tr>
</table>

### ⚙️ Utility Sections

<table>
<tr>
<th>Section</th>
<th>File</th>
<th>Key Features</th>
</tr>
<tr>
<td><strong>Scrolling Marquee</strong></td>
<td><code>marquee.liquid</code></td>
<td>Infinite ticker — mix Text, Image, Icon blocks. Speed, direction, pause-on-hover</td>
</tr>
<tr>
<td><strong>Moving Announcement</strong></td>
<td><code>advanced-marquee.liquid</code></td>
<td>Single-line promo marquee — custom bg/text colors, speed, direction</td>
</tr>
<tr>
<td><strong>Marquee Text</strong></td>
<td><code>marquee-text.liquid</code></td>
<td>Oversized typographic ticker — two lines, filled/outlined/mixed text styles</td>
</tr>
<tr>
<td><strong>Scrolling Icons / Logos</strong></td>
<td><code>scrolling-icons.liquid</code></td>
<td>Auto-scrolling logo strip — grayscale filter, fade edges, borders</td>
</tr>
<tr>
<td><strong>Countdown Timer</strong></td>
<td><code>countdown-timer.liquid</code></td>
<td>Live Days:Hours:Mins:Secs countdown — target date, optional CTA, color scheme</td>
</tr>
<tr>
<td><strong>Promotional Countdown</strong></td>
<td><code>promotional-countdown-banner.liquid</code></td>
<td>Full section countdown — timer styles, urgency badge, solid/gradient/image bg, redirect on expire</td>
</tr>
<tr>
<td><strong>Promotional Scroll Banner</strong></td>
<td><code>promotional-scroll-banner.liquid</code></td>
<td>Three text lines with outline + fill typography — scroll-reveal animation</td>
</tr>
<tr>
<td><strong>Popup Promo</strong></td>
<td><code>popup-promo.liquid</code></td>
<td>Lightbox popup — delay, cookie frequency, position, blur overlay, email capture blocks</td>
</tr>
<tr>
<td><strong>Featured Blog</strong></td>
<td><code>featured-blog.liquid</code></td>
<td>Blog post cards from any blog — date, author, excerpt, columns, View All</td>
</tr>
<tr>
<td><strong>Split Promo Banners</strong></td>
<td><code>split-promo-banners.liquid</code></td>
<td>2–3 campaign tile banners side-by-side — image, heading, description, link per tile</td>
</tr>
<tr>
<td><strong>Mobile Bottom Nav</strong></td>
<td><code>mobile-bottom-nav.liquid</code></td>
<td>Fixed bottom tab bar for mobile — Home, Collections, Search, Account, Cart with badge</td>
</tr>
</table>

---

## Theme Settings

All settings configured in the Shopify Customizer — no code required.

### Typography
| Setting | Type | Description |
|---|---|---|
| `type_header_font` | `font_picker` | Heading font — applied to H1–H6, section titles, product names |
| `type_body_font` | `font_picker` | Body font — paragraphs, buttons, labels, navigation |

### Colors
| Setting | Type | Description |
|---|---|---|
| `color_text` | `color` | Primary text — default `#1A1A1A` |
| `color_text_light` | `color` | Secondary/muted text |
| `color_background` | `color` | Page background — default `#FAFAF8` |
| `color_accent` | `color` | Brand accent — links, hover states, decorative elements — default `#C9A96E` |
| `color_border` | `color` | Dividers, card borders, input outlines |
| `color_button` | `color` | Primary CTA button background |
| `color_background_alt` | `color` | Surface/card background |
| `color_background_inverse` | `color` | Dark/inverse section background |
| `color_sale` | `color` | Sale badge and discount indicators |

### Layout
| Setting | Type | Description |
|---|---|---|
| `page_width` | `range` | Max content width 1000–1600px — default `1280px` |
| `spacing_sections` | `range` | Global section vertical padding multiplier |

### Cart
| Setting | Type | Options |
|---|---|---|
| `cart_type` | `select` | `drawer` — AJAX slide-in \| `page` — full `/cart` page |
| `currency_code_enabled` | `checkbox` | Append currency code to prices |

### Animations
| Setting | Type | Description |
|---|---|---|
| `enable_animations` | `checkbox` | Master toggle for all scroll animations |
| `animation_type` | `select` | Fade Up, Fade In, Slide Left/Right, Scale In, Stagger Children |
| `animation_speed` | `select` | Fast (0.3s) / Normal (0.5s) / Slow (0.8s) |
| `animation_stagger` | `range` | Delay between stagger child elements (ms) |
| `enable_parallax` | `checkbox` | Global parallax on background images |
| `enable_magnetic` | `checkbox` | Magnetic hover on CTA buttons |
| `enable_char_reveal` | `checkbox` | Character-by-character heading reveal |

### Social Media
`social_facebook` · `social_instagram` · `social_twitter` · `social_tiktok` · `social_youtube` · `social_pinterest` · `social_linkedin` · `social_snapchat` · `social_sharing_image`

---

## Architecture

### Directory Structure

```
reign-atelier/
│
├── assets/
│   ├── base.css                         # Reset, CSS variables, core utilities
│   ├── animations.css                   # Scroll animations, keyframes, transitions
│   ├── component-card.css               # Product card component styles
│   ├── component-price.css              # Price display styles
│   ├── theme.js                         # Main JS: cart drawer, header, animations
│   ├── global.js                        # Shared utilities and event helpers
│   └── intersection-observer-counters.js # Counter animation module
│
├── config/
│   ├── settings_schema.json             # All theme settings definitions
│   └── settings_data.json               # Runtime settings values
│
├── layout/
│   └── theme.liquid                     # Master layout template
│
├── locales/
│   └── en.default.json                  # All translatable strings
│
├── sections/                            # 89 section files (75+ customer-facing)
├── snippets/                            # Reusable Liquid partials
└── templates/                           # JSON page templates (OS 2.0)
    └── customers/                       # Account page templates
```

### JavaScript Patterns

| Pattern | Usage |
|---|---|
| **Custom Elements / Web Components** | Cart drawer, product form, variant picker, predictive search — encapsulated and app-compatible |
| **IntersectionObserver** | All scroll animations, lazy loading, counter triggers — zero scroll event listeners |
| **Fetch API + Section Rendering API** | AJAX cart operations, collection tab switching — no full page reloads |
| **Custom DOM Events** | `cart:add`, `cart:update` — loose coupling between cart drawer, product form, header count |
| **ES Modules** | Code split by responsibility — no monolithic bundle |

### No Build Step Required

REIGN Atelier uses modern CSS (custom properties, `clamp()`, grid, flex) and vanilla ES6+ JavaScript. No webpack, no preprocessors, no compilation needed — edit and ship directly.

---

## Page Templates

All templates built as Shopify OS 2.0 JSON templates — every block is drag-and-drop in the Customizer.

| Template | File | Notes |
|---|---|---|
| Homepage | `index.json` | Fully custom via drag-and-drop sections |
| Product | `product.json` | OS 2.0 blocks — variant picker, tabs, sticky bar, related products |
| Collection | `collection.json` | Storefront filtering, sorting, grid columns, quick add |
| Cart | `cart.json` | Two-column layout with order summary and express checkout |
| Blog | `blog.json` | 2–3 column article grid with pagination |
| Article | `article.json` | Full-width with share buttons and related articles |
| Search | `search.json` | Products, pages, articles with filter grid |
| Page | `page.json` | Generic rich-text page |
| About | `page.about.json` | Pre-configured for brand story sections |
| Contact | `page.contact.json` | Pre-configured with Contact Form section |
| FAQ | `page.faq.json` | Pre-configured with FAQ Accordion section |
| List Collections | `list-collections.json` | Auto-generated collection grid |
| Password | `password.json` | Coming Soon / pre-launch page |
| 404 | `404.json` | Styled not-found page with search |
| Gift Card | `gift_card.liquid` | Shopify native gift card |
| Login / Register | `customers/login.json` · `customers/register.json` | Styled account auth |
| Account Dashboard | `customers/account.json` | Orders, details, logout |
| Order | `customers/order.json` | Full order details |
| Addresses | `customers/addresses.json` | Manage saved addresses |
| Password Reset | `customers/reset_password.json` | Native flow, fully styled |
| Activate Account | `customers/activate_account.json` | Account activation |

---

## Performance

| Optimization | Implementation |
|---|---|
| **Lazy Loading** | Native `loading="lazy"` on all below-fold images. First image uses `loading="eager"` for LCP |
| **Responsive Images** | `image_url` filter with `widths` + `sizes` → automatic `srcset` per device |
| **No Render-Blocking JS** | All scripts loaded `defer` or `type="module"` |
| **Section Rendering API** | AJAX features fetch only required HTML fragments — no full page reloads |
| **Font Display** | `font-display: swap` + `preconnect` hints on all Google Font loads |
| **Critical CSS** | Above-fold styles in `<head>`. Section CSS inlined within section files |
| **Zero jQuery** | No heavy library overhead — pure vanilla JS throughout |

---

## Accessibility

REIGN Atelier is built to WCAG 2.1 AA standards as a foundation.

| Feature | Implementation |
|---|---|
| **Semantic HTML** | Correct heading hierarchy (H1–H6), landmark elements (`<header>`, `<main>`, `<nav>`, `<footer>`) |
| **ARIA Labels** | All icon-only buttons, close controls, carousel navigation include `aria-label` |
| **Keyboard Navigation** | Full keyboard support — dropdowns, modals, cart drawer, search use correct focus management |
| **Focus Styles** | Visible focus outlines on all interactive elements — not hidden with `outline: none` |
| **Reduced Motion** | All animations disabled via CSS `@media (prefers-reduced-motion: reduce)` |
| **Color Contrast** | Default palette meets WCAG AA contrast ratios |
| **Alt Text** | Passed through from Shopify Admin product/file alt text |

---

## Installation

> **Do not extract the ZIP file.** Shopify requires the original compressed archive.

1. Download `reign-atelier-v1.0.0.zip` from your purchase source
2. Go to **Shopify Admin → Online Store → Themes**
3. Click **Add theme → Upload ZIP file**
4. Select the ZIP → click **Upload**
5. Click **Publish** to make it live, or **Preview** to test first

**First setup checklist:**
- [ ] Set fonts: **Theme Settings → Typography**
- [ ] Set colors: **Theme Settings → Colors**
- [ ] Upload logo: **Header → Logo**
- [ ] Upload favicon: **Theme Settings → Favicon**
- [ ] Set cart type: **Theme Settings → Cart**
- [ ] Add social URLs: **Theme Settings → Social Media**
- [ ] Build your homepage with drag-and-drop sections
- [ ] Configure the product page blocks in the Customizer
- [ ] Preview on mobile before publishing

---

## Documentation

Complete official documentation with every section's settings, all configuration options, developer notes, and troubleshooting:

**[📖 reignatelier.nexevai.com](https://reignatelier.nexevai.com/)**

The documentation covers:
- Full installation walkthrough
- Every theme setting explained
- All 75+ sections with settings reference
- Page template configuration
- Architecture & developer guide
- Custom CSS / JS patterns
- Performance & accessibility notes
- FAQ (12 questions) and Troubleshooting (9 common issues)

---

## Support

| Channel | Details |
|---|---|
| **Email** | [rayeesyousuf80@gmail.com](mailto:rayeesyousuf80@gmail.com) |
| **Response Time** | 24–48 business hours, Monday–Friday |
| **Covered** | Theme bugs, usage questions, Customizer help |
| **Not Covered** | Custom code modifications, third-party app conflicts, general Shopify questions |

When contacting support, include:
- Your store URL
- A clear description and steps to reproduce
- Screenshot or screen recording if applicable
- Any recently installed apps or theme code changes

---

## License

**Single-store license.** One purchase covers one live Shopify store.

- ✅ Use on one live store
- ✅ Use on staging / development stores for the same project
- ❌ Use on multiple separate live stores (requires additional purchase per store)
- ❌ Redistribution, resale, or sharing of theme files

---

## Changelog

### v1.0.0 — February 2026 — *Initial Release*

- 75+ drag-and-drop sections across 8 categories
- Shopify Online Store 2.0 — JSON templates, App Blocks, Section Everywhere
- Advanced animation system — scroll reveals, parallax, character reveal, magnetic hover, 3D tilt
- AJAX cart drawer with free-shipping bar, upsell product block, and order notes
- Interactive Split Showcase — full-viewport hover-expand product panels
- Shop The Look / Lookbook with animated pulsing hotspot product markers
- Interactive Video Parallax with 3D tilt and configurable parallax speed
- Before / After interactive drag slider
- Promotional Countdown Banner — solid/gradient/image backgrounds, urgency badge, redirect-on-expire
- Popup Promo — configurable delay, cookie duration, position, content blocks
- Wall of Love masonry review section and Testimonials Grid
- Gallery Masonry section
- Vertical Product Carousel — infinite scroll, multi-column, alternate directions
- Trending Products Reveal with oversized background text element
- Marquee, Moving Announcement, Marquee Text, Scrolling Icons/Logos
- Collection Tabs with AJAX collection switching (no page reload)
- Mobile Bottom Navigation fixed tab bar
- Live predictive search with product images and prices
- Enhanced Footer with full block-based column system
- Zero external JavaScript dependencies
- WCAG 2.1 AA accessibility foundations
- `prefers-reduced-motion` fully respected
- Mobile-first responsive — every component

---

<div align="center">

```
✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦
```

**Built by [Nexevai](https://reignatelier.nexevai.com/) · Developer: Rayees Yousuf**

*Premium Shopify theme development for luxury brands*

[🛍 View Theme](https://themes.shopify.com/themes/reign-atelier?token=eyJwYXJ0bmVyX2lkIjo0NTk3MjEwLCJtZW1iZXJzaGlwX3VzZXJfaWRlbnRpdHlfaWQiOiI2NWVmYmYwNC05NjUyLTRkOGYtYmQxZS1jNjQzZWM5OWE3YTUiLCJ0aW1lc3RhbXAiOjE3NzE3ODM3Mjd9--b4fc9f2b5b3cc41167f5efc7de18a43760945903#Reviews) · [📖 Documentation](https://reignatelier.nexevai.com/) · [✉ Support](mailto:rayeesyousuf80@gmail.com)

© 2026 Nexevai. All rights reserved.

```
✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦ ── ✦
```

</div>
