# Madhavbaug Ayurvedic Migraine & Headache Relief Roll-On Landing Page

A high-converting, mobile-responsive landing page designed for **Madhavbaug Ayurvedic Migraine & Headache Relief Roll-On** following the exact conversion architecture of `madhav-PCOD`.

---

## 🌟 Key Features

1. **Pack of 3 Special Launch Offer**:
   - Primary default offer: **Pack of 3 (3x 10ml Roll-On Bottles) @ ₹699** (MRP ₹1,299 | Save ₹600 - 46% OFF).
   - Upgradable bundles: Pack of 6 @ ₹1,199 and Pack of 9 @ ₹1,699.
2. **Dedicated Visual Asset Flow**:
   - **Hero Product Image**: Pack of 3 premium Ayurvedic Roll-On bottles with herbal cooling aesthetics (`assets/images/migraine_hero.jpg`).
   - **Banner Below Hero (Benefits Banner)**: Visualizing fast 5-minute cooling relief, menthol & nilgiri action, and zero painkiller side effects (`assets/images/migraine_benefits_banner.jpg`).
   - **Ingredients Banner**: Infographic banner highlighting the 5 key active herbs: Pudina Satva (Menthol), Nilgiri Tel (Eucalyptus), Gandhapura (Wintergreen), Karpoor (Camphor), and Lavang Tel (Clove) (`assets/images/migraine_ingredients_banner.jpg`).
   - **WhatsApp Reviews Section Banner**: Authentic customer WhatsApp chat testimonials praise instant relief (`assets/images/migraine_whatsapp_reviews.jpg`).
   - **Official Madhavbaug Logo**: Embedded across Navbar and Footer (`assets/images/madhavbaug_logo.png`).
3. **100% Cash On Delivery (COD) Focus**:
   - Zero advance payment messaging across top announcement bar, hero section, sticky floating bar, and order modals.
   - 24-hour duplicate phone number protection against spam or accidental multiple orders.
   - Google Sheets Webhook integration (`google_apps_script.js`).
   - Instant WhatsApp Order Confirmation direct link with pre-filled message upon checkout.
4. **Live Social Proof**:
   - Rotating real-time buyer toast notifications from major Indian cities.
5. **Interactive Elements**:
   - Dynamic bundle selector synced with floating bottom sticky bar and modal form.
   - Smooth accordion FAQs.
   - Comprehensive comparison between conventional chemical painkiller tablets vs. topical Ayurvedic roll-on.

---

## 🚀 Running the Project

### Development Server:
```bash
npm run dev
```
Runs Vite dev server on port `3004`.

### Production Build:
```bash
npm run build
```
Creates an optimized production bundle in the `dist/` directory.

---

## 📊 Google Sheets Webhook Integration
To capture COD orders in your Google Sheet:
1. Open Google Sheets and create a sheet named `Madhavbaug Migraine Roll-On Leads`.
2. Go to **Extensions > Apps Script**.
3. Copy and paste the contents of `google_apps_script.js`.
4. Deploy as Web App (Execute as **Me**, Access: **Anyone**).
5. Update `GOOGLE_SHEETS_WEBHOOK_URL` in `assets/js/main.js`.
