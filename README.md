# RapidMobil 🚚 - Courier Service Website

**RapidMobil** is a modern, responsive website for a fictional courier service in Moldova, built as a coursework project. It showcases fast, reliable delivery options with a user-friendly interface, vibrant design, and interactive features. The site is designed to impress with its sleek courier-themed aesthetics and practical functionality for ordering deliveries. 📦

---

## 📖 Project Overview

RapidMobil is a static website for a courier service operating in Chisinau and across Moldova. It provides users with information about delivery options, tariffs, and services, and allows them to place delivery orders via an intuitive modal form. The project demonstrates proficiency in **HTML**, **CSS**, **JavaScript**, and modern web frameworks, with a focus on responsive design, accessibility, and user experience.

### 🎯 Key Features
- **🏠 Homepage (`index.html`)**:
  - Hero section with a call-to-action to order delivery.
  - Advantages section highlighting speed, reliability, and convenience.
  - Simplified Customer Feedback section with static testimonial cards (no carousel).
  - News & Updates section with recent company announcements.
- **📦 Order Page (`order.html`)**:
  - Displays four delivery options: Same-Day Express, Standard Delivery, Intercity Delivery, and Scheduled Delivery.
  - Interactive modal form triggered by "Order Now" buttons, allowing users to input details (name, email, phone, addresses, tariff, notes).
  - Form submission generates a `mailto:` email sent to the server (`info@rapidmobil.md`) and CC'd to the user, with a formatted order summary.
- **🎨 Design**:
  - Courier-themed color scheme: Blue (`#1E40AF`) for trust, Orange (`#F97316`) for energy.
  - `Inter` font for clean, modern typography.
  - Responsive grid layouts (1-3 columns) for mobile, tablet, and desktop.
  - Hover effects on cards and buttons for interactivity.
- **♿ Accessibility**:
  - Semantic HTML, ARIA labels, and keyboard navigation (Tab, Enter, Escape).
  - High-contrast colors meeting WCAG standards.
- **📱 Responsiveness**:
  - Mobile-first design with Tailwind’s responsive classes.
  - Tested on devices from 375px (mobile) to 1200px (desktop).

---

## 🛠️ Technologies Used

- **HTML5**: Semantic structure for all pages.
- **CSS3**:
  - **Tailwind CSS**: Utility-first framework for rapid styling.
  - **DaisyUI**: Tailwind plugin for pre-built components (cards, modals, navbar).
  - Custom styles for courier-themed colors and hover effects.
- **JavaScript**:
  - Modal toggling and form validation in `order.html`.
  - Dynamic `mailto:` email generation with form data.
- **Heroicons**: SVG icons for visual accents (e.g., checkmarks, lightning bolts).
- **Unsplash**: High-quality hero background image.

---

## 📂 Project Structure

```
rapidmobil/
├── index.html          # Homepage with Hero, Advantages, Feedback, News
├── order.html          # Delivery Options page with modal order form
├── services.html       # (Placeholder) Lists item types for delivery
├── tariffs.html        # (Placeholder) Pricing details
├── contact.html        # (Placeholder) Contact information
├── about.html         # (Placeholder) Company information
├── faq.html           # (Placeholder) Frequently asked questions
└── README.md          # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari).
- No server required (static site).
- Optional: Code editor (e.g., VS Code) for modifications.

### Installation
1. **Clone or Download**:
   - Clone the repository: `git clone <repo-url>` or download the ZIP file.
2. **Navigate to Project**:
   - Open the `rapidmobil` folder in your code editor or file explorer.
3. **Run Locally**:
   - Open `index.html` in a browser to view the homepage.
   - Navigate to `order.html` to test the order form.
   - No local server needed, as the site uses CDN-hosted dependencies (Tailwind, DaisyUI, Heroicons).

### Deployment
- Host on a static hosting platform like **Netlify**, **GitHub Pages**, or **Vercel**.
- Steps:
  1. Push the project to a GitHub repository.
  2. Connect the repository to your hosting platform.
  3. Deploy the site (root directory: `rapidmobil/`).
- Optimize images (convert to WebP) and minify HTML/CSS/JS for production.

---

## 🖱️ Usage

1. **Homepage (`index.html`)**:
   - Explore the Hero, Advantages, Feedback, and News sections.
   - Click "Order Now" in the Navbar or Hero to visit `order.html`.
2. **Order Page (`order.html`)**:
   - View delivery options (Same-Day Express, Standard Delivery, etc.).
   - Click "Order Now" on any card to open the modal form.
   - Fill in the form (name, email, phone, addresses, tariff, optional notes).
   - Submit to open your email client with a pre-filled order email.
   - Cancel or press Escape to close the modal.
3. **Testing**:
   - Verify responsiveness on mobile (375px), tablet (768px), and desktop (1200px).
   - Test form validation (empty fields, invalid email/phone).
   - Check email generation (To: `info@rapidmobil.md`, CC: user’s email).

---

## 🛠️ Customization

- **Hero Image**: Replace the Unsplash URL in `index.html` and `order.html` with a branded image.
- **Colors**: Update `.bg-courier-blue` (`#1E40AF`) or `.text-courier-orange` (`#F97316`) in the `<style>` section.
- **Form Fields**: Add fields (e.g., package weight) to the modal form in `order.html` and update the JavaScript `emailBody`.
- **Tariffs**: Modify delivery options in `order.html` (cards and `<select>` dropdown).
- **Language**: Translate to Romanian (e.g., “Comandă Livrare”) or Russian (e.g., “Заказать доставку”) by updating text in HTML files.

---

## ⚙️ Limitations

- **Static Site**: Uses `mailto:` for email submission, requiring users to manually send the email via their client. A backend (e.g., Node.js, PHP) could enable direct email sending.
- **Email Client Dependency**: `mailto:` may not work on devices without an email app configured.
- **Placeholder Pages**: `services.html`, `tariffs.html`, `contact.html`, `about.html`, and `faq.html` are not fully implemented (placeholders).

---

## 🌟 Future Improvements

- **Backend Integration**: Add a server (e.g., Node.js with Nodemailer) to send emails directly and store orders.
- **Order Confirmation**: Create a confirmation page or email auto-response after submission.
- **Tracking System**: Implement a mock tracking page for users to follow their packages.
- **Multilingual Support**: Add Romanian and Russian translations with a language toggle.
- **Enhanced Forms**: Include package details (weight, size) and real-time tariff pricing.

---

## 📝 Coursework Context

This project was developed as a **coursework assignment** to demonstrate skills in:
- **Frontend Development**: Building a responsive, accessible website with HTML, CSS, and JavaScript.
- **UI/UX Design**: Creating a visually appealing, user-friendly interface with Tailwind and DaisyUI.
- **Interactivity**: Implementing a dynamic modal form with client-side validation and email generation.
- **Project Documentation**: Writing a clear, professional README.

The site simulates a real-world courier service, with fictional testimonials, news, and delivery options tailored to Moldova.

---

## 👨‍💻 Author

- **Your Name** (replace with your name or team name)
- Built for **[Course Name]** coursework, [Year].

---

## 📧 Contact

For questions or feedback:
- Email: [Your Email]
- GitHub: [Your GitHub Profile]
- RapidMobil (fictional): `info@rapidmobil.md` | `+373 69 123 456`

---

## 🙏 Acknowledgments

- **Tailwind CSS** and **DaisyUI** for rapid, beautiful styling.
- **Heroicons** for clean, accessible icons.
- **Unsplash** for the hero background image.
- **xAI** for powering Grok, which assisted in generating this project.

Happy delivering with RapidMobil! 🚚✨