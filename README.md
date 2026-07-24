# TriniBuild — AI Store Builder + Street Food + Fresh Catch

Mobile-first web app for **Trinidad & Tobago**.

**Take a photo → AI lists it.** 5 free listings for life. Order street food & fresh catch. COD + PayPal. Store builder, VAT tracker, affiliates.

## Live prototype files

| File | Purpose |
|------|---------|
| `index.html` | Full app (auth, Snap & List, marketplace orders, store builder, VAT, affiliates) |
| `landing.html` | Marketing landing page |

## Features

- **AI Snap & List** — photo → title, description, price, tags (simulated AI in demo)
- **5 free listings for life** — counter + localStorage persistence
- **Auth** — name + email, data saved on device
- **Marketplace** — Street Food + Fresh Catch vendors (Port of Spain)
- **Orders** — cart, Cash on Pickup (COD) or PayPal (demo), order history
- **Store Builder** — templates, name/tagline/colour, live preview
- **VAT Tracker** — 12.5% TT calculator + sales log from orders
- **Affiliates** — referral link, WhatsApp share, commission structure
- **WhatsApp** — `wa.me` chat vendor, share listing, support
- **Mobile-first** — bottom nav, safe areas, CRO + GEO + SEO meta for TT

## Run locally (PowerShell)

```powershell
cd path\to\trinibuild-app
Start-Process index.html
# or
Start-Process landing.html
```

Or any static server:

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Stack

- Single-file HTML + Tailwind CDN + vanilla JS
- `localStorage` for auth, listings, orders, store, VAT, affiliates
- No backend required for the prototype

## Payments (demo)

- **Cash on Pickup** — primary for TT
- **PayPal** — simulated success (wire real SDK for production)

## Related

- [antigravity-trinibuild](https://github.com/RAYKUNJAL/antigravity-trinibuild) — original website builder
- [fresh-catch-depot-finder](https://github.com/RAYKUNJAL/fresh-catch-depot-finder) — seafood / depot app

## License

Private / all rights reserved unless otherwise stated by Ray Kunjal.
