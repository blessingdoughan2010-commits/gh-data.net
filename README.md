# 🔵🟡🔴 Little Dots Think Vendors

**Ghana's cheapest data bundles — 2GB to 4GB for MTN, Telecel & AirtelTigo**

> DATA. AIRTIME. QUICK BUNDLES. 🇬🇭  
> TEL: 0534337934

---

## 🚀 Deploy to Render

1. Push this repo to GitHub
2. Go to [render.com](https://render.com) → New → **Static Site**
3. Connect your GitHub repo
4. Settings auto-detected from `render.yaml`:
   - **Build Command:** `npm install && npm run build`
   - **Publish Directory:** `dist`
5. Click **Create Static Site** — done! ✅

---

## 💻 Run Locally

```bash
npm install
npm run dev
```

Build for production:
```bash
npm run build
```

---

## 🔐 Owner Features

### 📊 Sales Dashboard
- Click the tiny **📊 Sales** button (bottom-left of screen)
- Enter PIN: **1010** (change in `src/components/AdminPanel.tsx`)
- View all orders, revenue, and network breakdown

### 📢 Ads Manager
- Click the tiny **📢 Ads** button (bottom-left of screen)
- Enter PIN: **1010**
- Create, toggle, and delete scrolling ad banners
- Customers see the ads in the top ticker bar

### 🛒 How Orders Work
1. Customer picks a bundle → enters phone number
2. System generates a unique **Order ID** (e.g. `DH-M5K2X-AB3F`)
3. WhatsApp opens with pre-written message to **+233 534 337 934**
4. Order is logged in your Sales Dashboard

---

## 💰 Pricing (Competitive Market Rates)

| Network | 2GB | 2.5GB | 3GB | 3.5GB | 4GB |
|---------|-----|-------|-----|-------|-----|
| MTN | GH₵11 | GH₵13 | GH₵16 | GH₵19 | GH₵22 |
| Telecel | GH₵10 | GH₵12 | GH₵14 | GH₵16 | GH₵19 |
| AirtelTigo | GH₵9 | GH₵11 | GH₵13 | GH₵15 | GH₵18 |

---

## 🛠 Tech Stack
- React 19 + TypeScript
- Vite 7
- Tailwind CSS 4
- Lucide React icons
- WhatsApp API integration
