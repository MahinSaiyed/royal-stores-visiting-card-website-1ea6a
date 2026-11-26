# 👑 Royal Stores (રોયલ સ્ટોર્સ) — Clothing Repair, Fabric Vulcanizing & Wholesale Accessories

[![Live on Netlify](https://img.shields.io/badge/Netlify-royal--stores.netlify.app-00C7B7?style=flat&logo=netlify&logoColor=white)](https://royal-stores.netlify.app/)
[![Live on GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-mahinsaiyed.github.io-222222?style=flat&logo=github&logoColor=white)](https://mahinsaiyed.github.io/)
[![Google Analytics 4](https://img.shields.io/badge/Google%20Analytics%204-G--SQQ2ZFXNJ0-E37400?style=flat&logo=google-analytics&logoColor=white)](https://analytics.google.com/)
[![Crafted by](https://img.shields.io/badge/Developed%20By-SaiyedWebCoders-0a1c32?style=flat)](https://saiyedwebcoders.netlify.app/)

Welcome to the official repository of **Royal Stores (રોયલ સ્ટોર્સ)**, Ahmedabad's trusted clothing repair, fabric vulcanizing, and tailoring materials wholesale provider.

This repository powers both the physical shop banner QR code landing page (`https://mahinsaiyed.github.io/`) and the primary production deployment (`https://royal-stores.netlify.app/`).

---

## 🌐 Live URLs

| Service / Deployment | Live URL | Purpose |
| :--- | :--- | :--- |
| **Physical Shop Banner / QR Code** | [https://mahinsaiyed.github.io/](https://mahinsaiyed.github.io/) | Printed on physical shop banners & visiting cards across Ahmedabad |
| **Primary Production (Netlify)** | [https://royal-stores.netlify.app/](https://royal-stores.netlify.app/) | High-speed global CDN deployment via Netlify CI/CD |
| **Secondary Mirror (GitHub Pages)** | [https://mahinsaiyed.github.io/royal-stores-visiting-card-website/](https://mahinsaiyed.github.io/royal-stores-visiting-card-website/) | Backup GitHub Pages deployment |

---

## 🧵 About Royal Stores (રોયલ સ્ટોર્સ)

* **Founder / Manager**: Shehzad Alvi
* **Direct Order Desk**: `+91 97231 14370`
* **FabriBond Plus Founder Desk**: `+91 83478 74084`
* **Location**: Ahmedabad, Gujarat, India
* **Core Specialty**: Doorstep pickup and home delivery for fabric vulcanizing, invisible thermal tear bonding, zipper slider repairs, and garment alterations.

### 📋 Service Terms & Conditions (નિયમો અને શરતો)
1. **Advance Payment**: 100% advance or a minimum of **50% advance payment strictly mandatory** before repair work commences.
2. **Turnaround Time**: Minimum **1 week (7 days)** turnaround (e.g., Sunday pickup is delivered back on the following Sunday).
3. **Pre-Existing Heavy Damage**: No liability for garments with extreme pre-existing fabric rot, dry fiber decay, or irreparable tearing.
4. **Doorstep Pickup Eligibility**: Minimum **3 to 4 garments** and a minimum service bill of **₹300/-** required for free doorstep pickup and return delivery.

---

## 🛍️ Wholesale & Retail Accessories Catalog (`#products`)

Customers can browse and buy tailoring & luggage accessories directly through dedicated Amazon-style Product Detail Pages (`product.html`) with dynamic option pricing, quantity counters, and WhatsApp routing:

| # | Product Name | Brand | Pricing / Packaging | WhatsApp Routing |
| :-: | :--- | :--- | :--- | :--- |
| **1** | **TONI Brand Wire Zipper Runners**<br>*(Trolley luggage, duffle bags & ladies purses)* | **TONI BRAND** | • No. 5, 7, 8 (250 Pcs): **₹2,999**<br>• No. 10 (250 Pcs): **₹3,499** | Shehzad Alvi (`+91 97231 14370`) |
| **2** | **Jeans Two-Part Metal Buttons**<br>*(Embossed metal cap + heavy-duty tack nails)* | **ROYAL ACCESSORIES** | 100 Pieces Complete Set: **₹599** *(MRP: ₹799)* | Shehzad Alvi (`+91 97231 14370`) |
| **3** | **Premium Brass Metal Jeans Zippers**<br>*(5", 6", 7" Length options for trousers & denims)* | **ROYAL DENIM ACCESSORIES** | 50 Pieces Pouch Pack: **₹1,499** *(MRP: ₹1,899)* | Shehzad Alvi (`+91 97231 14370`) |
| **4** | **Heavy-Duty Jacket & Outerwear Zippers**<br>*(26" & 28" Brass Metal & Molded Fiber chains)* | **HEAVY-DUTY OUTERWEAR** | • Single Piece: **₹299**<br>• Wholesale 50 Pcs Pack: **₹2,999** | Shehzad Alvi (`+91 97231 14370`) |
| **5** | **FabriBond Plus Vulcanized Repair Sheet + Velcro**<br>*(DIY no-sew thermal bonding paper + fastener pack)* | **FABRIBOND PLUS** | Retail Pack (5"×20" Sheet + Velcro): **₹99** *(+₹50 Delivery)* | **Direct Founder Desk** (`+91 83478 74084`) |
| **6** | **Megibha Heavy-Duty Tailoring Elastic Rolls**<br>*(90 Foot rolls in 1", 1.5", 2", 2.5" Widths)* | **MEGIBHA** | 90 Foot Roll (White / Black): **₹999** *(MRP: ₹1,299)* | Shehzad Alvi (`+91 97231 14370`) |

---

## ⚡ Key Technical Features

* **Amazon-Style Dedicated PDP (`product.html`)**: Interactive option pills, dynamic real-time price calculation, quantity adjuster, and high-resolution product showcase.
* **Address & Payment Method Modal Popup**: Mandatory Customer Name and Delivery Address with 3 structured payment modes:
  - **Cash on Delivery (COD)**: 20% advance payment strictly mandatory online to confirm order dispatch, remaining 80% on delivery.
  - **Prepaid (100% Full Payment)**
  - **Google Pay (GPay / UPI)**
* **Automated WhatsApp Order Dispatch**: Generates pre-formatted WhatsApp orders beginning with `"This message from your Royals new website 2026."` with customer details, selected items, address, and payment method.
* **Google Analytics 4 (GA4)**: Configured with Measurement ID `G-SQQ2ZFXNJ0` and custom event tracking:
  - `qr_code_scan`: Detects visitors landing via physical banner & visiting card QR codes (`?source=qr` or `?source=visiting_card_qr`).
  - `call_click`: Direct phone calls.
  - `generate_lead`: Doorstep pickup booking form submissions.
  - `begin_checkout`: Opening the address & payment modal.
  - `purchase`: WhatsApp checkout completions.
* **Fully Responsive UI**: Mobile-optimized drawer with backdrop blur, touch event isolation, and clean light-theme typography.
* **Zero Framework Overhead**: Built with pure semantic HTML5, modern CSS3 (Custom Variables, Flexbox, Grid), and vanilla ES6 JavaScript for instant load times on 3G/4G/5G mobile devices.

---

## 📁 Repository Structure

```text
royal-stores/
├── index.html          # Main website homepage & services catalog
├── product.html        # Amazon-style standalone product detail page
├── README.md           # Project documentation & configuration guide
└── images/             # Optimized visual assets & catalog photography
    ├── call-qr-code.png
    ├── product-brass-zippers.jpg
    ├── product-elastic-rolls.jpg
    ├── product-fabribond.jpg
    ├── product-jacket-zippers.jpg
    ├── product-jeans-buttons.jpg
    ├── product-sun-runners.jpg
    ├── product-toni-runners.jpg
    ├── visiting-card-back.png
    └── visiting-card-front.jpg
```

---

## 🚀 Deployment & CI/CD

This repository is configured with a unified multi-remote push setup. A single push to `origin main` automatically synchronizes all three deployment targets:

1. **Netlify Production**: `https://github.com/MahinSaiyed/royal-stores-visiting-card-website-1ea6a.git`
2. **Shop Banner QR Code**: `https://github.com/MahinSaiyed/mahinsaiyed.github.io.git`
3. **GitHub Pages Mirror**: `https://github.com/MahinSaiyed/royal-stores-visiting-card-website.git`

```bash
# Push to all 3 remotes in one command:
git push origin main
```

---

## 👨‍💻 Developer & Agency Credits

* **Web Development & Architecture**: [SaiyedWebCoders](https://saiyedwebcoders.netlify.app/)
* **Lead Engineer**: Mahin Saiyed
* **Client**: Royal Stores (Shehzad Alvi)
* **Copyright**: © 2026 SaiyedWebCoders. All Rights Reserved.
