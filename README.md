# Haul Pass Trash Valet — Sign Up

Resident sign-up page: $10/month, trash picked up from the apartment door 2x/week.

## Setup
- **Stripe:** in `index.html`, set `STRIPE_PAYMENT_LINK` (near the bottom) to your Stripe Payment Link.
- **Sign-up emails:** form details (name, email, phone, complex, unit) are emailed to `NOTIFY_EMAIL` via FormSubmit.co before checkout. Click the one-time activation email FormSubmit sends after the first sign-up.
- **Hosting:** GitHub Pages from the `main` branch root.
