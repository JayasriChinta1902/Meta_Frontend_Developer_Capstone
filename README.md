# 🍋 Little Lemon Restaurant

A modern, responsive restaurant web app built as the capstone project for the Meta Frontend Developer Professional Certification.  
Little Lemon Restaurant is a vibrant, family-owned bistro web app where tradition meets innovation. The site features a beautiful landing page with weekly specials, customer testimonials, and an about section. Users can easily reserve a table online and receive instant confirmation via email, thanks to seamless EmailJS integration.

## 🎥 Demo

![Little Lemon Demo](./src/assets/images/demo.gif)

## 💡 Features

- 🏠 Elegant landing page with hero, specials, testimonials, and about sections
- 📅 Online table reservation form with email confirmation
- 🛡️ Robust form validation using Zod and React Hook Form
- 📱 Fully responsive and mobile-friendly design
- ⭐ Modern UI with Bootstrap 5 and custom SCSS
- ⚡ Fast, type-safe, and scalable with React + TypeScript

## 🛠️ Tech Stack

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)  
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)  
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)  
[![Zod](https://img.shields.io/badge/Zod-3E54A3?style=for-the-badge&logo=zod&logoColor=white)](https://zod.dev/)  
[![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)](https://react-hook-form.com/)  
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)  
[![EmailJS](https://img.shields.io/badge/EmailJS-4A90E2?style=for-the-badge&logo=emailjs&logoColor=white)](https://www.emailjs.com/)

## 🚀 Getting Started

To run the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Umairulislam/little-lemon-reservation.git
   cd little-lemon-reservation
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Set up EmailJS:**
   - Create an account on [EmailJS](https://www.emailjs.com/).
   - Create a new email service and template.
   - Add your EmailJS public key, service ID, and template ID to a .env file:
   ```env
   VITE_EMAILJS_PUBLIC_KEY=your_public_key
   VITE_EMAILJS_SERVICE_ID=your_service_id
   VITE_EMAILJS_TEMPLATE_ID=your_template_id
   ```
4. **Start the development server:**
   ```bash
    npm run dev
   ```
5. **Open your browser and navigate to:**
   ```
   http://localhost:5173
   ```

## 👨‍💼 Author

Crafted with care by **Engr. Umair Ul Islam**
