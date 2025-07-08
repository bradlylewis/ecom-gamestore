# 🎮 E-Commerce Game Store

A modern, full-stack e-commerce storefront for digital and physical games. Built with **React** and powered by **Firebase** for backend services and deployment. Styled using **SCSS + CSS Modules** for modular, scalable, and maintainable UI.

---

## 🛠 Tech Stack

- **Frontend:** React, React Router, Context API
- **Styling:** SCSS + CSS Modules
- **Backend:** Firebase Firestore
- **Auth:** Firebase Auth (optional)
- **Payments:** Stripe (Test Mode)
- **Hosting:** Firebase Hosting + Cloud Functions

---

## 🚀 Features

| Feature                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| 🛍 Product Catalog        | Browse game listings with image, price, and description                    |
| 🛒 Cart System            | Add/remove items, update quantities, view cart                             |
| 💳 Checkout Flow         | Checkout form with Stripe test integration                                 |
| 🔐 User Auth (Optional)  | Firebase email/password login and account persistence                      |
| 🗃 Firestore Backend      | Store product and cart data in real-time NoSQL database                    |
| ☁️ Cloud Deployment       | Hosted via Firebase with optional Cloud Functions backend                  |

---

## 📦 Folder Structure

ecom-gamestore/  
├── public/  
├── src/  
│   ├── components/  
│   ├── pages/  
│   ├── context/  
│   ├── firebase/  
│   ├── styles/ *(SCSS Modules)*  
│   └── App.js  
├── .env  
├── firebase.json  
└── README.md  

---

## ⚙️ Setup Instructions

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/ecom-gamestore.git && cd ecom-gamestore
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Set up Firebase**  
   - Create a Firebase project  
   - Enable Firestore, Authentication, and Hosting  
   - Add your Firebase config to `.env`:

   ```env
   REACT_APP_FIREBASE_API_KEY=xxx
   REACT_APP_FIREBASE_AUTH_DOMAIN=xxx
   REACT_APP_FIREBASE_PROJECT_ID=xxx
   REACT_APP_FIREBASE_STORAGE_BUCKET=xxx
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=xxx
   REACT_APP_FIREBASE_APP_ID=xxx
   ```

4. **Start the dev server**  
   ```bash
   npm run start
   ```

5. **Deploy to Firebase**  
   ```bash
   npm run build && firebase deploy
   ```

---

## 🧪 Stripe Test Info

Use Stripe’s test keys and cards to simulate transactions.  
📚 [Stripe Testing Docs](https://stripe.com/docs/testing)

---

## 📸 Screenshots

_Add UI screenshots of the product catalog, cart system, and checkout page._

---

## 📄 License

MIT — feel free to fork, modify, and build on top of it.
