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
```

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
