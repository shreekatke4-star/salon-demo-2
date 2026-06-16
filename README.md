# Glamour Studio — Salon Website 💇‍♀️

A premium, responsive salon website built with **HTML**, **Tailwind CSS**, and **Vanilla JavaScript**.

## 🌐 Live Site
[View Website](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME)

## ✨ Features
- Responsive design (mobile & desktop)
- Booking form with **EmailJS** email integration
- WhatsApp booking button
- Gallery with lightbox viewer
- Before & After slider
- Services modal popups
- FAQ accordion
- Google Maps embed
- Smooth scroll animations

## 📁 Project Structure
```
salon-website/
├── index.html          ← Main website file
├── images/             ← All images
│   ├── hero.jpg
│   ├── haircut.jpg
│   ├── hair-spa.jpg
│   ├── hair-color.jpg
│   ├── facial.jpg
│   ├── makeup.jpg
│   ├── bridal-makeup.jpg
│   ├── manicure-pedicure.jpg
│   ├── waxing-threading.jpg
│   ├── team-priya.jpg
│   ├── team-neha.jpg
│   ├── team-anita.jpg
│   ├── team-gargi.jpg
│   ├── makeup-after-1.png
│   ├── makeup-before-1.png
│   ├── makeup-after-2.png
│   ├── makeup-before-2.png
│   ├── interior-gallery.jpg
│   ├── haircut-gallery.jpg
│   ├── makeup-gallery.jpg
│   └── hair-color-gallery.jpg
└── README.md
```

## 🚀 Deploy on GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set Source to **main branch / root**
4. Your site will be live at `https://username.github.io/repo-name`

## 📧 EmailJS Setup
Edit `index.html` and replace these 3 values in the script:
```js
emailjs.init("YOUR_PUBLIC_KEY");
const SERVICE_ID  = 'YOUR_SERVICE_ID';
const TEMPLATE_ID = 'YOUR_TEMPLATE_ID';
```
Get your free keys at [emailjs.com](https://www.emailjs.com)
