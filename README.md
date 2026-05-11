# 🏷️ PakPrices — Pakistan Price Comparison Website

## 📁 File Structure
```
pakprices/
├── index.html        ← Main website page
├── vercel.json       ← Vercel deployment config
├── css/
│   └── style.css     ← All styles
└── js/
    ├── data.js       ← All product data (edit this to add products)
    └── app.js        ← Website logic
```

---

## 🚀 How to Deploy FREE on Vercel (Step by Step)

### Step 1 — Create a GitHub account
- Go to https://github.com and sign up (free)

### Step 2 — Upload your files
1. Click "New repository"
2. Name it: `pakprices`
3. Click "Upload files"
4. Drag and drop ALL files (keep folder structure)
5. Click "Commit changes"

### Step 3 — Deploy on Vercel
1. Go to https://vercel.com and sign up with GitHub
2. Click "New Project"
3. Select your `pakprices` repository
4. Click "Deploy" — done! ✅

Your site will be live at: `pakprices.vercel.app` (FREE)

---

## ➕ How to Add More Products

Open `js/data.js` and copy this template:

```javascript
{
  id: 13,                          // unique number
  name: "Product Name Here",
  category: "mobile",              // mobile / laptop / appliance / fashion / grocery
  emoji: "📱",
  prices: [
    { store: "Daraz",  price: 50000, url: "https://daraz.pk/your-link", color: "#EF4444" },
    { store: "OLX",    price: 47000, url: "https://olx.com.pk/your-link", color: "#0EA5E9" },
    { store: "Local",  price: 52000, url: "#", color: "#F59E0B" }
  ]
},
```

---

## 💰 How to Earn Money

### 1. Google AdSense (Passive income from ads)
- Go to https://adsense.google.com
- Add your site URL
- Paste the ad code in `index.html`
- Earn every time someone views or clicks an ad

### 2. Daraz Affiliate Program
- Go to https://affiliate.daraz.pk
- Sign up free
- Replace the `url` in `data.js` with YOUR affiliate links
- Earn 3-8% commission on every sale

### 3. Charge for "Featured Listings"
- Sellers pay you Rs 500-2000/month to appear at top
- Contact local Daraz sellers directly

---

## 📈 How to Get Traffic (Free)

1. **Facebook Groups** — Post in "Online Shopping Pakistan", "Daraz Deals Pakistan" etc.
2. **TikTok** — Make short videos showing price differences ("iPhone 15 — Rs 30,000 saved!")
3. **SEO** — Your site will rank on Google for "iPhone price in Pakistan" etc. over time
4. **WhatsApp** — Share daily deal screenshots in groups

---

Built with ❤️ for Pakistan 🇵🇰
