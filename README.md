# ♻️ Loop Market — Give Resources a Second Life

**An AI-assisted circular-economy marketplace connecting surplus materials with people and businesses that can reuse them, alongside a dedicated Food Rescue experience.**

🌐 **Live website:** https://loop-market-vttx7c.v2.appdeploy.ai/

## About the Project

Loop Market is a sustainability-focused digital platform designed to make reuse, resource sharing and surplus-food coordination easier. Individuals and businesses can list reusable materials, discover resources, submit requests and coordinate exchanges. Its dedicated **Food Rescue** experience helps connect surplus-food donors with people and community organisations.

Our vision is simple: **what one person no longer needs can become another person's valuable resource.**

## The Problem

Reusable materials are often discarded because potential users cannot easily find them. Small businesses may struggle to source affordable secondary materials, while surplus food can go unused even when nearby communities could benefit. Local resource sharing is often fragmented and difficult to coordinate.

## The Solution

Loop Market brings material exchange and food rescue into one digital ecosystem. It combines a searchable marketplace, AI-assisted discovery, direct participant coordination, community participation tools and activity-based impact reporting.

## Main Features

### ♻️ 1. Circular Materials Marketplace
- Browse listings across paper, plastic, metal, glass, textiles, organic and other categories.
- Search and filter available materials.
- View descriptions, quantities, condition, location and price.
- Publish surplus materials with photos and listing details.
- Manage vendor listings and inventory.
- Submit order requests and follow their status.
- Save favourites and coordinate directly with participants.

### 📸 2. AI Material Scanner
- Upload a material photo for an AI-assisted assessment.
- Receive an indicative material name, category and visible-condition estimate.
- Explore potential reuse ideas.

*AI identification is an estimate, not laboratory analysis, a safety assessment or formal material certification.*

### 🧠 3. Smart Material Matchmaking
- Describe a material need.
- Discover active listings that may fit the request.
- Rank results using relevant keywords in titles, descriptions, categories and locations.

Matching is a discovery aid; it does not guarantee suitability, quality or availability.

### 🍲 4. Food Rescue — Share a Meal, Change a Day
- Publish eligible surplus-food donations.
- Include food type, portions, dietary information, known allergens, packaging and collection deadline.
- Discover and filter donations by area, dietary need and portions.
- Submit requests for available portions.
- Allow donors to accept or decline requests.
- Confirm completed handovers.
- Contact donors through WhatsApp when they have chosen to share a contact number.

*Food Rescue coordinates community handovers; it does not certify food safety or replace local food-safety requirements. Donors should only offer food they know has been handled safely and disclose known allergens and collection deadlines.*

### 🌱 5. Eco Impact Dashboard
- Track completed marketplace activity.
- Display eligible material quantities recorded in completed orders.
- Track completed food handovers and portions.
- Monitor active material listings and food donations.

Impact figures depend on platform records. Quantities that cannot reliably be converted to mass are excluded from kilogram totals. The platform does not claim independently verified carbon savings.

### 🚚 6. Pickup & Delivery Coordination
- Choose an existing order.
- Submit a preferred collection date.
- Select collection or delivery as the preferred arrangement.
- Save requests pending confirmation by the other participant.

This is coordination between participants, not an integrated live courier-booking service.

### 🏆 7. Green Rewards & Leaderboard
- Earn participation points for completed orders.
- View personal points and community leaderboard activity.

Points are participation scores, not cash or redeemable currency.

### 🤖 8. Eco AI Assistant
- Ask questions about reuse ideas, responsible sorting and circular-economy approaches.
- Explore suggestions for sustainable material management.

AI responses are informational and should be checked before safety-critical or technical decisions.

### 🛡️ 9. Trust & Quality Verification
- Submit business verification requests.
- Describe the business and materials handled.
- Support human review before a verification badge is awarded.

A submitted request remains pending until an authorised reviewer approves it.

### ✨ 10. Responsive Animated Experience
- Eco-inspired forest-green, lime and warm-cream visual identity.
- Responsive desktop and mobile layouts.
- Animated interface elements, transitions and interactive cards.
- Clear navigation and accessible focus states.

## Technology Stack

| Technology | Purpose |
|---|---|
| React 19 | User interface |
| TypeScript | Typed application development |
| Vite 6 | Development and production build tooling |
| Tailwind CSS | Styling utilities |
| Framer Motion | Interface animations |
| GSAP | Advanced motion effects |
| Lucide React | Icons |
| AppDeploy client integration | Application API, authentication and image-processing integration |
| AppDeploy | Hosting and deployment |

## Project Structure

```text
loop-market/
├── src/
│   ├── App.tsx                 # Main application and marketplace
│   ├── FoodRescue.tsx          # Food donation and rescue
│   ├── LoopLab.tsx             # AI tools, matching and impact features
│   ├── index.css               # Global styles and visual design
│   └── main.tsx                # Application entry point
├── backend/
│   ├── index.ts
│   ├── realtime.ts
│   └── realtime-subscribers.ts
├── tests/
│   └── tests.json
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts
```

## Run Locally

### Prerequisites
- Node.js and npm
- Access to the required AppDeploy application configuration and backend services

### Install and start

```bash
git clone https://github.com/shankarendiran-a-g/trash-and-food-website.git
cd trash-and-food-website
npm install
npm run dev
```

### Production build

```bash
npm run build
npm run preview
```

**Configuration note:** The frontend uses AppDeploy client integration and application API endpoints. A local frontend build does not automatically configure the backend, authentication or AI services. Follow the deployment configuration instructions for those services. Never commit API keys, passwords or other secrets to GitHub.

## Responsible Design

- Material condition and listing details should be described clearly.
- AI outputs are estimates, not certifications.
- Verification requests remain pending until human approval.
- Pickup requests require confirmation from the other participant.
- Food listings should disclose known allergens and collection deadlines.
- Avoid publishing private home or kitchen addresses.
- Environmental reporting is based on recorded platform activity.
- Application secrets and personal contact details should be protected.

Online payment processing is not currently part of the platform. Exchanges are coordinated directly between participants.

## Roadmap

- Improve image-based material recognition and guidance.
- Expand location-aware matchmaking.
- Add multilingual support, including Tamil.
- Improve trust, quality and moderation workflows.
- Expand community rewards and impact reporting.
- Improve collection coordination.
- Continue mobile optimisation and evaluate Android packaging with Capacitor (APK/AAB).

Roadmap items are future development goals, not claims that those capabilities are already shipped.

## Vision

We believe sustainability becomes easier when technology helps people find practical ways to share and reuse what already exists. Loop Market aims to connect individuals, businesses and community organisations so materials stay useful for longer and eligible surplus food can reach people who need it.

**We are not just building another marketplace. We are building a smarter loop for resources, communities and the planet.**

## Project Information

- **Project:** Loop Market
- **Focus:** Circular Economy, Sustainability, Reuse and Food Rescue
- **Live demo:** https://loop-market-vttx7c.v2.appdeploy.ai/
- **Repository:** https://github.com/shankarendiran-a-g/trash-and-food-website

**LOOP MARKET — NOTHING USEFUL SHOULD GO TO WASTE.** ♻️
