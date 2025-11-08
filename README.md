# Women Safety Device Website

This repository contains the official website for **Women Safety Device**, a personal security device designed to protect women through instant alerts, live GPS tracking, and automated calling functions. The website serves as an awareness platform and an e-commerce interface for direct purchase.

---

## 🧭 Overview

The **Women Safety Device Website** spreads awareness about women’s safety issues, highlights real-time statistics, and offers a one-click purchase option for DevineTech’s safety device priced at **₹7,000 (inclusive of GST)**.

### Key Sections

* **Home Page** – Showcases women safety importance, crime data, and solution introduction.
* **Product Section** – Detailed specifications, working mechanism, and features of the device.
* **Statistics Section** – Displays safety incident data and awareness numbers.
* **Purchase Form** – Integrated with [Web3Forms](https://web3forms.com/) for secure submission; users get a unique token number upon order confirmation.

---

## 🧩 Features

* **Responsive single-page layout** built with **Tailwind CSS**.
* **Neumorphism-inspired design** for a soft, modern aesthetic.
* **Web3Forms integration** for backend-free order form submission.
* **Client-side token generator** for instant order tracking.
* **Smooth scroll navigation** and modern UI animations.

---

## 💻 Tech Stack

| Technology               | Purpose                       |
| ------------------------ | ----------------------------- |
| **HTML5**                | Page structure                |
| **Tailwind CSS**         | Styling and layout            |
| **JavaScript (Vanilla)** | Form logic & token generation |
| **Web3Forms API**        | Email form submission         |

---

## 🛒 Purchase Flow

1. User fills out the purchase form.
2. On submission, the data is securely sent to Web3Forms.
3. Admin receives all purchase details via email.
4. The user gets an on-screen confirmation with a **unique token number** marked as *Pending*.

---

## ⚙️ Setup Instructions

1. Clone or download this repository.
2. Open the main HTML file in your code editor.
3. Replace the placeholder `YOUR_WEB3FORMS_ACCESS_KEY` with your actual [Web3Forms access key](https://web3forms.com/).
4. Optionally update email settings, brand logo, or product images.
5. Deploy using any static hosting platform (e.g., **Vercel**, **Netlify**, or **GitHub Pages**).

---

## 🔒 Environment Variables

No server environment variables required. Only a Web3Forms API key is needed in the form’s hidden field:

```html
<input type="hidden" name="access_key" value="YOUR_WEB3FORMS_ACCESS_KEY">
```

---

## 📦 Folder Structure

```
WomenSafetyDeviceWebsite/
├── index.html        # Main single-page website
├── README.md         # Project overview and setup instructions
└── assets/           # (Optional) Images, icons, and media files
```

---

## 📊 Future Enhancements

* Integration of **Razorpay / Stripe** payment gateway.
* Live **NCRB statistics** API for real-time safety data.
* Admin dashboard to manage and confirm orders.
* Auto email confirmation and **PDF invoice generation**.

---

## ✨ Credits

Developed by **Adityaraj Patil**  — an initiative to build innovative, tech-driven solutions for public safety and empowerment.

---

## 📫 Contact

8669792979

---

**License:** MIT License
© 2025 DevineTech — All Rights Rese
