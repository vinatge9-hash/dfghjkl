# Brew Haven – Website Build Notes

This is a complete, multi-page website for Brew Haven, a modern, artisanal coffee shop. It includes:

- Home (index.html) with hero, testimonials, and a gallery.
- Menu (menu.html) with sections for Coffee, Teas, and Pastries. Items can be added to cart.
- Cart (cart.html) that stores items in localStorage and allows removal.
- Checkout (checkout.html) with a mock PayPal Sandbox payment flow.
- About (about.html) telling Brew Haven's sourcing story.
- Contact (contact.html) with a form, interactive map (Hyderabad, India placeholder), and hours.

Styling and interactions are built with Tailwind CSS. All icons are inline SVGs. The design uses a warm palette with a serif heading font and a clean sans-serif body font. A three-column footer is featured on desktop sizes.

Notes:
- Placeholder images use the format: src="https://pixabay.com/get/g8bba3eb01177a018b04654c123be2dc95d32cc7304cfe3888cc5a5bc1f012f5e8b169051d9d36698aad8cebaaf2756fbbc3d39a198c5b8a000f3d5fadedf1b01_640.jpg".
- The current year in the footer is 2025.
- All pages share a consistent header and footer.
- Page load includes a gentle fade-in, and sections below the hero use scroll reveal animations.
- The cart is persisted in localStorage and is accessible across pages.
- A README is included for reference and future updates.