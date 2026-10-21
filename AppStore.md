# GlossLog — App Store Submission Guide

## 1. App Store Metadata

- **Name:** GlossLog
- **Subtitle:** Car Detailing Log & Journal
- **Category:** Lifestyle (Primary), Utilities (Secondary)
- **Bundle Identifier:** `com.glosslog.app`
- **SKU:** `glosslog-ios`
- **Keywords (exactly 100 characters max):**
  `car detailing,detailing log,shine track,wash tracker,ceramic coating,paint protection,auto detailer`
- **Targeted Devices:** iPhone & iPad (Universal)
- **Primary URLs (GitHub Pages):**
  - **Support URL:** `https://orangedev9.github.io/luster-docs/support.html`
  - **Privacy Policy URL:** `https://orangedev9.github.io/luster-docs/privacy.html`
  - **Marketing / Landing URL:** `https://orangedev9.github.io/luster-docs/index.html`
  - **Terms of Use:** `https://orangedev9.github.io/luster-docs/terms.html`

---

## 2. App Store Description

Precision automotive detailing, protection tracking, and garage history — all in one native app.

GlossLog is the ultimate privacy-first detailing journal designed for car collectors, weekend enthusiasts, and mobile detailing professionals. Track treatments, monitor ceramic and wax degradation, compare before & after transformations with an interactive slider, and generate professional client invoices — 100% offline.

SHOWCASE GALLERY & BEFORE/AFTER SLIDER
- Align your "after" shot perfectly using our camera ghost overlay
- Interactive side-by-side touch comparison slider
- Export and share high-resolution branded transformation cards

TREATMENT PROTECTION INTELLIGENCE
- Live wear-off progress bars for waxes (60d), sealants (90d), and ceramic coatings (365d+)
- Know exactly when protection is fading before water stops beading
- 1-tap "Log Renewal" to maintain paint protection effortlessly

LOG SERVICES IN SECONDS
- Full support for Washes, Waxes, Sealants, Ceramic Maintenance, Interior Cleans, Paint Correction, Wheels, and Engine Bays
- Record duration, mileage, weather, condition notes, and multi-step checklists
- Automatically calculate product consumption and cost per wash

CHEMICAL SHELF & INVENTORY TRACKING
- Track your supply shelf with bottle sizes, purchase costs, and live remaining percentages
- Low-stock alerts remind you to reorder before running dry
- Import products easily via CSV or load a starter detailing shelf

MOBILE DETAILING BUSINESS SUITE
- Create customized estimates, quotes, and client invoices with regional tax rates
- Record client payments, deposits, and payment terms
- Export branded vector PDF reports and client statements with your logo

FIRST-CLASS IPAD & MAC EXPERIENCE
- iPadOS sidebar navigation with multi-column split views
- Desktop keyboard shortcuts (⌘N for new session, ⌘⇧N for new vehicle, ⌘F for search)
- Full support for system Light Mode and Dark Mode

100% PRIVATE BY DESIGN
- No account required, no ads, no trackers, and no external servers
- Protect your garage and client records with optional Face ID
- Full offline .zip backups with full-resolution photos that you control

PRICING & PLUS
Free tier includes up to 3 vehicles, 5 detail sessions, and 3 sample PDFs.
Upgrade to GlossLog Plus for unlimited vehicles, unlimited sessions, unlimited watermark-free PDF exports, maintenance reminders, and advanced insights.
- Monthly: $2.99 / month (`com.glosslog.plus.monthly`)
- Yearly: $14.99 / year with 7-day free trial (`com.glosslog.plus.yearly`)
- Lifetime: $39.99 one-time purchase (`com.glosslog.lifetime`)

---

## 3. App Review Notes (Paste into App Store Connect)

> GlossLog operates 100% offline and requires no user registration, account, or login. All vehicle records, photos, and chemical inventories are stored locally on the device using Apple's SwiftData framework.
> 
> Testing In-App Purchases:
> - The free tier allows up to 3 vehicles and 5 sessions. Adding a 4th vehicle or 6th session prompts the StoreKit paywall.
> - Sandbox test accounts can test Monthly, Yearly (with 7-day free trial), and Lifetime purchases.
> - In Settings > GlossLog Plus, tap "Restore Purchases" to restore test transactions.
> 
> Hardware & Permissions:
> - Camera is used only when the user taps the camera button to take vehicle before/after photos.
> - Photos library is accessed only via standard PhotosPicker when selecting photos.
> - Face ID / Touch ID is an optional local security lock (Settings > Require Face ID).
> - Notifications deliver local maintenance reminders scheduled directly on-device.

---

## 4. App Privacy Declaration (App Store Connect)

- **Data Collection:** Data Not Collected
- **Tracking:** No (GlossLog does not track users across apps or websites)
- **Privacy Manifest:** `PrivacyInfo.xcprivacy` included with `NSPrivacyAccessedAPICategoryUserDefaults` (CA92.1) and zero tracking domains.

---

## 5. Screenshot Checklist (iPhone & iPad)

Launch in Xcode with arguments: `-seedSampleData -forcePlus`

1. **Dashboard:** Vehicle summary card, active Care Status treatment gauges, and recent sessions.
2. **Showcase Gallery:** Side-by-side Before/After slider mid-transformation.
3. **Detail Session:** Highlighting products used, duration, cost, and checklist items.
4. **Treatment Protection:** Ceramic and wax protection wear-off indicators.
5. **Inventory Shelf:** Chemical bottles with % remaining and low-stock warnings.
6. **PDF Invoicing:** Professional branded invoice with tax and logo.

---

## 6. App Icon (1024x1024)

- **Production Icon:** `Assets.xcassets/AppIcon.appiconset/AppIcon.png` (Full-bleed graphite background, electric-blue gloss caustic glow, futuristic aerodynamic hypercar enclosed inside a protective glass bubble with a starburst sparkle).
- **Original Droplet Backup:** `Assets.xcassets/AppIcon.appiconset/AppIcon_original_droplet.png`.
