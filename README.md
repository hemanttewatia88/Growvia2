# GrowViaSphere — Official Web Application

> **Where Ambition Works, Wellness Thrives, and Community Compounds**

Delhi NCR's first integrated professional lifestyle destination. One premium address combining a commercial-grade fitness facility, luxury performance café, professional co-working space, and fully-equipped meeting & conference rooms.

---

## 🌐 Live Site

**[growviasphere.com](https://growviasphere.com)** *(deployment pending)*

---

## 📋 About This Project

This is the official web application for GrowViaSphere, built with React + Vite. The app serves as the primary digital presence for the brand — covering membership acquisition, service discovery, community programming, and founding member onboarding.

### Pages
| Route | Description |
|-------|-------------|
| `/` | Home — hero, services overview, problem statement, testimonials |
| `/about` | Brand story, founding team, values |
| `/services` | Deep-dive on all four verticals |
| `/membership` | Pricing tiers, corporate plans, FAQ |
| `/community` | Events calendar, community programming, member stories |
| `/contact` | Inquiry form, location, operating hours |

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | React 18 |
| Build Tool | Vite 8 |
| Routing | React Router v6 |
| Icons | Lucide React |
| Fonts | Cormorant Garamond + Inter (Google Fonts) |
| Styling | Vanilla CSS with CSS Custom Properties |
| Deployment | Vercel / Netlify (recommended) |

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm 9+

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/growviasphere.git
cd growviasphere

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be available at `http://localhost:5173`

### Available Scripts

```bash
npm run dev      # Start development server
npm run build    # Production build → /dist
npm run preview  # Preview production build locally
npm run lint     # Run ESLint
```

---

## 🎨 Design System

### Brand Colors
```css
--navy:        #1A3A5C   /* Primary — Deep navy */
--green:       #0E7C5B   /* Accent — Forest green */
--gold:        #C8962A   /* Highlight — Gold */
--cream:       #F9F6F0   /* Background — Warm cream */
```

### Typography
- **Display:** Cormorant Garamond (Serif) — Headlines, taglines
- **Body:** Inter (Sans-serif) — Body copy, UI elements
- **Mono:** JetBrains Mono — Labels, data, eyebrows

---

## 📁 Project Structure

```
growviasphere/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Navbar.jsx / Navbar.css
│   │   └── Footer.jsx / Footer.css
│   ├── pages/
│   │   ├── Home.jsx / Home.css
│   │   ├── About.jsx / About.css
│   │   ├── Services.jsx / Services.css
│   │   ├── Membership.jsx / Membership.css
│   │   ├── Community.jsx / Community.css
│   │   └── Contact.jsx / Contact.css
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── vite.config.js
├── package.json
└── README.md
```

---

## 🚢 Deployment

### Vercel (Recommended)
```bash
npm install -g vercel
vercel --prod
```

### Netlify
```bash
npm run build
# Drag and drop /dist to Netlify dashboard
# Or connect GitHub repo in Netlify UI
```

### Manual
```bash
npm run build
# Deploy contents of /dist to any static host
```

---

## 📊 Business Context

GrowViaSphere is a seed-stage startup raising INR 4.5 Crore at INR 12 Crore pre-money valuation. This web application is part of the founding member acquisition strategy targeting 100 pre-launch memberships before Day 1.

**Key Metrics:**
- Target TAM: INR 18,000 Crore
- Year 3 ARR Target: INR 5.8 Crore
- Founding Member Target: 100 pre-paid memberships
- Break-even: Month 18–22

---

## 📄 License

Proprietary. © 2025 GrowViaSphere. All rights reserved.

---

## 📞 Contact

**hello@growviasphere.com** | Delhi NCR, India
