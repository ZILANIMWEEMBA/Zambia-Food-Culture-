# 🍲 Taste Zambia — Food Culture App
### App Innovators Club | Design Competition

---

## 📁 Project Folder Structure

```
zambia-food-culture/
│
├── index.html              ← HOME PAGE
│
├── pages/
│   ├── menu.html           ← MENU PAGE (all dishes)
│   └── details.html        ← DETAILS / RECIPE PAGE
│
├── css/
│   ├── style.css           ← Global styles (navbar, hero, cards, footer)
│   └── details.css         ← Details page extra styles
│
├── js/
│   └── main.js             ← All interactivity (filter, search, animations)
│
├── images/                 ← ⬅ PUT ORGANIZER PHOTOS HERE
│   ├── hero-dish.jpg
│   ├── nshima.jpg
│   ├── ifisashi.jpg
│   ├── kapenta.jpg
│   ├── chibwabwa.jpg
│   ├── vitumbuwa.jpg
│   ├── munkoyo.jpg
│   ├── chikanda.jpg
│   ├── groundnuts.jpg
│   └── ... (more as given)
│
└── README.md               ← This file
```

---

## 🖼️ How to Add Organizer Photos

Every image slot in the HTML is clearly marked with a comment:
```html
<!-- IMAGE SLOT: <img src="../images/nshima.jpg" alt="Nshima"> -->
```

**Steps to add a photo:**
1. Copy the photo into the `images/` folder
2. Find the matching `<!-- IMAGE SLOT -->` comment in the HTML
3. Remove the placeholder `<div class="card-img-placeholder">...</div>`
4. Uncomment / paste the `<img>` tag shown in the comment

**Example — before:**
```html
<div class="card-img-wrap">
  <!-- IMAGE SLOT: <img src="../images/nshima.jpg" alt="Nshima"> -->
  <div class="card-img-placeholder">
    <span class="ph-icon">🌽</span>
    <span>Nshima photo</span>
  </div>
  <span class="card-badge">Staple</span>
</div>
```

**Example — after (with photo added):**
```html
<div class="card-img-wrap">
  <img src="../images/nshima.jpg" alt="Nshima">
  <span class="card-badge">Staple</span>
</div>
```

---

## 📄 Pages Overview

| Page | File | Key Sections |
|------|------|--------------|
| Home | `index.html` | Hero, Categories, Featured Banner, Dishes Grid, Culture, Stats, Footer |
| Menu | `pages/menu.html` | Page Header, Search, Filter Tabs, Full Dishes Grid, Footer |
| Details | `pages/details.html` | Breadcrumb, Dish Info, Ingredients, Recipe Steps, Culture Note, Restaurant |

---

## ✨ Features Built

- ✅ Sticky navigation with scroll effect
- ✅ Chitenge-inspired pattern backgrounds  
- ✅ Category filter tabs (All / Staples / Stews / Street / Drinks / Snacks)
- ✅ Live search by dish name or description
- ✅ Scroll-triggered card animations
- ✅ Animated stat counters
- ✅ Thumbnail gallery on details page
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Warm Zambian earth-tone colour palette
- ✅ All image slots clearly labelled for organizer photos
- ✅ Restaurant info section
- ✅ Cultural significance notes

---

## 🎨 Design Theme

| Element | Value |
|---------|-------|
| Primary colour | Copper `#C96A2B` |
| Accent | Saffron Gold `#E8901A` / `#F2C14E` |
| Background | Warm Cream `#FDF6ED` |
| Dark | Bark Brown `#3D2008` |
| Green | Zambian Sage `#5A7A4A` |
| Display font | Playfair Display (serif) |
| Body font | Outfit (sans-serif) |

---

## 🛠️ Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, grid, flexbox, animations
- **Vanilla JavaScript** — filter, search, scroll reveal, counters
- **Google Fonts** — Playfair Display + Outfit
- *Compatible with WordPress page templates*

---

*App Innovators Club — Food Culture in Zambia Competition 2025*
