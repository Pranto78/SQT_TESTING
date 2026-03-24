# 🎟️ BookingExpress — Event Booking System

A full-stack web-based event booking platform built for seamless event discovery, ticket purchasing, and administration.

> **Course:** Software Quality Assurance and Testing | AIUB — Fall 25-26  
> **Team:** MD. Fahim Shahriyar Pranto · Mohtasim-Ur-Rahman · Arpita Mitra Sara

---

## 🚀 Features

- **User Authentication** — Secure sign-up & login with CAPTCHA lockout after repeated failed attempts
- **Event Discovery** — Browse events filtered by category, date, and location using real-time AJAX search
- **Ticket Booking** — Select seat type, quantity, specific seats, amenities, upgrades, and promo codes
- **Secure Checkout** — Payment integration with order summary and booking confirmation
- **Refund Management** — Request cancellations, track refund status with timeline view
- **Admin Control Panel** — Manage users (search, delete, block), view event details and pending requests
- **Profile Management** — Users can update name, phone, address, and profile photo
- **Contact Us Form** — Users can send queries directly through the platform
- **Responsive Design** — Fully functional across mobile, tablet, and desktop

---

## 🛠️ Tech Stack

| Layer       | Technology                        |
|-------------|-----------------------------------|
| Frontend    | HTML, CSS, JavaScript (AJAX)      |
| Backend     | PHP                               |
| Database    | MySQL                             |
| Local Server| XAMPP                             |
| UI Design   | Figma                             |
| Testing     | Selenium IDE                      |

---

## 🧪 Testing

Automated testing was performed using **Selenium IDE** with the following test cases:

| Test ID | Module               | Status |
|---------|----------------------|--------|
| FR_1    | User Registration    | ✅ Pass |
| FR_2    | User Log In          | ✅ Pass |
| FR_3    | Admin Log In         | ✅ Pass |
| FR_4    | User Profile Update  | ✅ Pass |
| FR_5    | Contact Us Form      | ✅ Pass |
| FR_6    | User Data Delete     | ✅ Pass |
| FR_7    | Search User          | ✅ Pass |
| FR_8    | Ticket Booking       | ✅ Pass |
| FR_9    | Search Admin Requests| ✅ Pass |
| FR_10   | Log Out              | ✅ Pass |

> Testing levels covered: **Unit Testing**, **System/Integration Testing**, **Acceptance Testing**

---

## ⚙️ Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/Pranto78/SQT_TESTING.git
   ```
2. Move the project folder into your `htdocs` directory (XAMPP)
3. Import the database via `phpMyAdmin`
4. Start Apache and MySQL in XAMPP
5. Open `http://localhost/Event-Booking-System/View/Landing_Page_feature/landing_page.html`

---

## 📁 Project Structure

```
BookingExpress/
├── View/
│   ├── Landing_Page_feature/
│   ├── User_Authentication_feature/
│   ├── Ticket_Booking_feature/
│   └── Admin_feature/
├── Controller/
├── Model/
└── assets/
```

---

## 📊 Effort Estimation (COCOMO)

- **SLOC:** ~5,450
- **Estimated Effort:** ~14 person-months
- **Development Time:** ~4 months
- **Team Size:** 3 developers

---

## 📄 License

This project was developed for academic purposes at **American International University-Bangladesh (AIUB)**.
