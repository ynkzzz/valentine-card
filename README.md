# valentine-card

# Interactive Valentine's Card Generator

A lightweight, single-page web application that allows users to create personalized Valentine's cards with custom messages and generate shareable dynamic links. When the recipient opens the link and accepts, an automated email notification is sent to the creator!

## Features

- 💌 **Custom Link Generation:** Encode sender, receiver, message, and email directly into URL parameters.
- 🎯 **Interactive Recipient View:** Dynamic letter rendering based on URL parameters.
- 🏃 **Playful "NO" Button:** The "NO" button dodges mouse hover/clicks on desktop and mobile.
- 📩 **Instant Notifications:** Integrated with EmailJS to send real-time confirmation emails.
- 🎨 **Pure CSS Background:** Smooth animated floating hearts without external video assets.

## Built With

- **HTML5 & CSS3** (Flexbox, CSS Animations, Glassmorphism)
- **JavaScript (ES6)** (URLSearchParams API)
- **[EmailJS](https://www.emailjs.com/)** (Client-side email handling)
- **GitHub Pages** (Hosting)

## How It Works

1. **Create:** The sender fills in their name, their beloved's name, their email address, and a personal message.
2. **Share:** The app generates a unique URL containing the encoded details.
3. **Respond:** The recipient opens the link and sees the tailored letter.
4. **Notify:** Clicking **YES!** triggers EmailJS to notify the sender immediately via email.

---
Made with ❤️ for Valentine's Day!
