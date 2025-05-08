# 🍰 SweetSpot – Artisan Dessert Marketplace

**SweetSpot** is a whimsical yet elegant dessert marketplace designed for small-batch bakeries and home bakers to showcase their creations. Built for dessert lovers who crave custom treats, and for bakers who need modern tools to manage orders, subscriptions, and growth.

![CI](https://github.com/<your-username>/sweetspot-devops/actions/workflows/ci.yml/badge.svg)

---

## ✨ Highlights

- 🧁 Explore and order artisanal desserts
- 📦 Subscribe to monthly dessert boxes
- 📊 Vendors manage menus, track orders, and see real-time insights
- 🔄 Real-time order tracking and customization
- 🔐 Secure, scalable cloud deployment (Firebase + DevOps)
- 💖 UI built with Tailwind CSS, designed for delight ✨

---

## 🧑‍🍳 Target Users

- **Customers**: Dessert lovers, foodies, and subscribers
- **Vendors**: Small-scale bakers, home-based dessert creators

---

## 🧠 Features

### 🌸 **Landing Page**
- Hero section with whimsical CTA
- Featured treats (image cards)
- Testimonials slider
- Footer with newsletter, socials, contact

### 👩‍🍳 **Customer Dashboard**
- Sidebar: Home, Orders, Subscriptions, Favorites
- Realtime order tracking (live updates!)
- Order history and easy reordering

### 🧾 **Vendor Dashboard**
- Sidebar: Menu Editor, Orders, Insights
- Menu editing: upload images, tags (e.g., vegan, gluten-free)
- Order table with status filters (Pending, Preparing, Shipped)
- Analytics widgets: Sales, Orders, Top Product

### 📦 **Subscription Box Builder**
- Pick delivery frequency (weekly/monthly)
- Select dessert preferences + flavors
- Live visual summary of selected items

### 🍩 **Product Page**
- Image carousel/gallery
- Ingredient tags + dietary filters
- Customization (flavor, quantity)
- "Add to Cart" with transitions & toast confirmation

---

## 🛠️ Tech Stack

| Layer         | Tech                             |
|---------------|----------------------------------|
| Frontend      | React, Tailwind CSS, React Router, Axios |
| Backend       | Node.js, Express.js              |
| Database      | MongoDB Atlas                    |
| Auth & Hosting| Firebase Authentication + Hosting (optional) |
| CI/CD         | GitHub Actions                   |
| Deployment    | AWS EKS / Firebase Hosting       |
| Animations    | Framer Motion                    |

---

## 🧩 Component Architecture

> Reusable, scalable, and aesthetic-first

- `<Button />`
- `<Card />` (ProductCard, OrderCard, AnalyticsCard)
- `<Sidebar />` (Vendor + Customer)
- `<Modal />` (Cart, Subscription Preview)
- `<Navbar />`
- `<HeroSection />`, `<TestimonialsSlider />`, `<Footer />`
- `<ImageGallery />`, `<Tag />`, `<CustomizationForm />`

---

## 🌗 Bonus Features

- Light / Dark Mode Toggle (via Tailwind + state toggle)
- Micro-interactions with Framer Motion
- Responsive across mobile, tablet, and desktop
- ARIA roles and keyboard nav for accessibility

---

## 🌐 Folder Structure

```bash
/src
  /components
    /common
    /customer
    /vendor
  /pages
    Landing.jsx
    DashboardCustomer.jsx
    DashboardVendor.jsx
    ProductPage.jsx
    SubscriptionBuilder.jsx
  /utils
  /styles
  App.jsx
  main.jsx
