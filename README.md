# 📱 Phone Catalog — React SPA

A modern single-page application for browsing a catalog of mobile phones.
Users can explore devices, open detailed product pages, switch between color and capacity options, manage favourites and cart items, and navigate the catalog using sorting and pagination controls.
The UI is fully responsive and built according to a professional Figma design.

---

## Live Demo

**GitHub Pages:**
https://tvk777.github.io/phone_catalog/

---

## 🎨 Design Source

**Figma template:**
https://www.figma.com/design/FRxncC4lfyhs6og1L6FGEU/Phone-catalog--V2--Rounded-Style-2?node-id=0-1&p=f

---

## ✨ Features

- **Responsive layout**
  Works on mobile, tablet, and desktop devices.

- **Sorting options**
  Sort phones by:
  - newest
  - alphabetical order
  - price

- **Pagination & items per page**
  Choose how many products appear per page (4 / 8 / 16 / all) and navigate between pages.

- **Product variations**
  Select options directly on the product details page:
  - color
  - storage capacity

- **Image gallery**
  Thumbnails dynamically change the main product image.

- **Favourites list**
  Add/remove phones from favourites — persisted in `localStorage`.

- **Shopping cart**
  - add products
  - update quantity
  - remove items
  Cart data is stored in `localStorage`.

- **Sticky header**
  Navigation bar stays visible while scrolling.

- **Scroll-to-top button**

- **Skeleton loaders**
  Show placeholder UI during data loading.

- **Breadcrumb navigation**
  Helps users understand where they are in the catalog.

- **404 Not Found page**
  Displayed when a route does not exist.

---

## Technologies Used

### Core

- **React**
- **TypeScript**
- **SCSS (Sass)**
- **Vite**

### Routing

- **React Router DOM**

### UI & helpers

- **Bulma**
- **Font Awesome**
- **classnames**
- **react-transition-group**
- **Swiper**

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/tvk777/phone_catalog.git
cd phone_catalog
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Run locally

```bash
npm start
```
