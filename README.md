# Aspire Welfare Community Group — Website

A complete, modern, mobile-friendly website for Aspire Welfare Community Group
(Manchester non-profit) built with the colours and logo of the official brand.

## Files
- `index.html` — page shell, full design system & styles
- `app.js` — all pages, navigation, dashboards, learning portal & interactivity
  (the official logo is embedded directly, so the site is fully self-contained)

## How to view / deploy
Just open `index.html` in any browser, or upload both files to any web host
(Netlify, Vercel, GitHub Pages, cPanel, etc.). No build step required.

## What's included
**15 pages** (hash-routed): Home, About, Vision & Mission, Previous Work & Impact,
Programmes, Robotics & STEM, Sports & Wellbeing, Donate, Volunteer, Partners,
Policies & Safeguarding, Testimonials, Contact, Login/Sign Up, Learning Portal,
plus a multi-role Dashboard (Admin / Parent / Volunteer / Young Person).

**Features (front-end ready):**
- Activity & event booking form + calendar list
- Donation page: amount selector, one-off/monthly toggle, animated progress bars,
  campaign pages, "Sponsor a Young Person" & "Robotics Waqf"
- Volunteer application, feedback/testimonial submission, contact & newsletter forms
- Learning portal: courses, video cards, downloadable resources, quiz, progress tracking
- Sports activities: Football, Martial Arts, Swimming, Cycling, Kayaking,
  Aspire Camps, Sleepover, Wellbeing
- English / Arabic language toggle (with RTL support)
- Social links (Facebook, Instagram, YouTube, WhatsApp)
- Floating Donate + WhatsApp buttons
- SEO meta tags, semantic markup, accessible colour contrast, responsive design

## Connecting the backend (production next steps)
The forms and buttons are wired to demo confirmations. To go live, connect:
- **Payments:** Stripe Checkout / PayPal SDK on the Donate & booking actions
- **Auth & dashboards:** Firebase Auth / Auth0 or a Laravel/Node backend
- **Bookings, attendance, messaging:** a database (PostgreSQL/MySQL) + API
- **CMS:** the Admin dashboard maps to a headless CMS (Strapi/Sanity) or WordPress
- **Email:** SendGrid / Mailgun for confirmations & newsletters
- **Calendar:** Google Calendar API or FullCalendar for live scheduling

All of these are standard integrations the current structure is designed to slot into.
