# SKYLIGHT ENGINEERING & ENERGY SOLUTIONS PRIVATE LIMITED
## Corporate Business Portfolio & Engineering Web Application

[![Vercel Ready](https://img.shields.io/badge/Deployment-Vercel%20Ready-000000?style=for-the-badge&logo=vercel)](https://vercel.com)
[![React 19](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org)
[![Tailwind CSS v4](https://img.shields.io/badge/Tailwind-CSS%20v4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-6.x-646CFF?style=for-the-badge&logo=vite)](https://vite.dev)

A modern, responsive, high-performance B2B corporate business portfolio web application built for **SKYLIGHT ENGINEERING & ENERGY SOLUTIONS PRIVATE LIMITED**.

The application reflects the company's statutory **Memorandum of Association (MOA)** business scope, covering industrial automation, electrical and electronic systems, renewable solar power, machinery installation & commissioning, equipment supply, plant maintenance, and technical consultancy.

---

## 🏛️ Corporate Identity & Legal Charter

* **Company Legal Name:** `SKYLIGHT ENGINEERING & ENERGY SOLUTIONS PRIVATE LIMITED`
* **Incorporation Jurisdiction:** State of Maharashtra, India
* **Corporate Persona:** Professional B2B engineering contractor suitable for Government Departments, Public-Sector Undertakings (PSUs), infrastructure developers, and industrial manufacturing enterprises.
* **Corporate Headline:** *"Engineering Excellence. Smarter Automation. Sustainable Energy."*
* **Design Palette:** Pure white, deep navy blue (`#0A192F`), steel grey, and clean renewable-energy green (`#10B981`) with industrial cyber-blue telemetry accents.

---

## ⚙️ 12 Core Engineering Disciplines (MOA Aligned)

The website features deep technical showcases for all 12 disciplines:

1. **Industrial Automation and Control Systems** — Redundant PLCs (Siemens, Rockwell, ABB), SCADA, DCS, industrial telemetry, fieldbus (Profinet, Modbus TCP), and process loop tuning.
2. **Engineering Design and Technical Solutions** — Electrical Single Line Diagrams (SLDs), P&IDs, cable sizing, earthing grids (IS 3043 / IEEE 80), and FEED advisory.
3. **Electrical and Electronic Systems** — HT/LT switchgears, Motor Control Centres (MCC), Power Control Centres (PCC), APFC panels, and harmonics mitigation.
4. **Industrial Machinery Installation and Commissioning** — Turnkey rigging, optical/laser shaft alignment, dynamic balancing, and vibration baseline records (ISO 10816).
5. **Renewable Energy and Solar Energy Systems** — Commercial & Industrial (C&I) rooftop and ground-mounted solar PV plants, inverters, and net-metering synchronization.
6. **Energy-Efficient Equipment and Power Solutions** — IE4/IE5 super-premium electric motors, low-harmonic VFD retrofits, and ISO 50001 energy monitoring.
7. **Machinery Repair, Servicing and Maintenance** — Annual Maintenance Contracts (AMC), predictive FFT vibration analysis, thermography, and rotating equipment overhauls.
8. **Equipment Refurbishment, Retrofitting and Modernisation** — Upgrading relay logic to modern PLCs, DC-to-AC vector drive conversions, and ISO 13849 machine safety retrofits.
9. **Machinery, Equipment, Spare Parts and Component Supply** — Verified procurement of switchgears, sensors, drives, bearings, and mechanical spares with Manufacturer Test Certificates (MTC).
10. **Technical Consultancy and Project Execution** — Detailed Project Reports (DPR), Technical Bid Evaluation (TBE), Owner's Engineer representation, and statutory audits.
11. **Research, Development and Technology Innovation** — Applied IoT edge gateways, hybrid microgrid dispatch algorithms, and predictive degradation models.
12. **Software, Hardware Maintenance and Technical Support** — SLA technical support, SCADA historian backup archival, OT cybersecurity network segmentation, and calibration.

---

## 🏢 Target Client Sectors

Presented transparently as target sectors for partnership and tender bidding:

* **Government Organisations** (Public works, municipal pumping telemetry, urban distribution)
* **Public-Sector Undertakings (PSUs)** (Power generation, heavy engineering, transport)
* **Private Industrial Organisations** (Automotive, chemical, continuous process manufacturing)
* **Energy and Renewable-Energy Sectors** (Solar developers, independent power producers, utilities)
* **Infrastructure and Engineering Projects** (Logistics corridors, ports, water transmission networks)

---

## ✨ Advanced Features & Capabilities

* **Filterable Project Portfolio:** Categories across Automation, Electrical Systems, Renewable Energy, Equipment, and Engineering with technical scope, architecture, outcomes, and clear sample spec disclaimers.
* **Equipment & Products Catalogue:** Real technical parameters without invented prices; includes an interactive **"Request a Quote"** action.
* **Structured Technical Enquiry Desk:** Multi-field validation, service category selection, budget brackets, timeline horizon, and feedback toasts.
* **Procurement & Tenders Portal:** Active notice listings, scope summaries, deadlines, and an admin interface to publish new tender announcements.
* **Interactive Careers Portal:** Real technical job profiles, eligibility requirements, and simulated CV upload.
* **Downloadable Corporate Profile PDF:** Dedicated printable dossier component (`window.print()`) rendering executive summary, MOA scope, and contact parameters.
* **Demo Administrative Dashboard (`/admin`):** Review, filter, update status, delete, and export all client leads, quotations, and job applications as JSON.
* **Maharashtra Contact Hub:** Direct WhatsApp chat integration, corporate hours, communication channels, and industrial corridor map graphic.
* **Statutory Compliance Pages:** Comprehensive Privacy Policy and Terms of Use adhering to Indian IT Act and MOA business objects.

---

## 🚀 Getting Started Locally

### Prerequisites

* Node.js v18 or later (tested on Node v20)
* npm v9 or later

### Installation

```bash
# Clone or navigate to the project directory
cd c:\Skylight2

# Install dependencies
npm install

# Start the development server
npm run dev
```

The application will launch at `http://localhost:5173/`.

### Production Build

```bash
# Compile TypeScript and bundle with Vite
npm run build

# Preview production build locally
npm run preview
```

---

## 🌐 Vercel Deployment Instructions

The project is pre-configured with `vercel.json` for seamless deployment.

### Method 1: Deploy with Vercel CLI

```bash
# Install Vercel CLI globally (if not already installed)
npm install -g vercel

# Deploy to Vercel
vercel

# Deploy to production
vercel --prod
```

### Method 2: Deploy via GitHub / GitLab Repository

1. Push this repository to GitHub or GitLab.
2. Log in to [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Import your repository.
4. Configure Build Settings (auto-detected):
   * **Framework Preset:** Vite
   * **Build Command:** `npm run build`
   * **Output Directory:** `dist`
   * **Install Command:** `npm install`
5. Click **"Deploy"**. The site will be live on a custom `.vercel.app` domain with instant global CDN caching and HTTPS.

---

## 🔒 Backend Integration Roadmap

The prototype operates with a decoupled architecture using React Context and `localStorage`. When ready to connect a live production backend:

1. **Database:** Replace the `localStorage` helpers in `src/context/AppContext.tsx` with PostgreSQL, Supabase, or MongoDB API calls.
2. **Authentication:** Integrate NextAuth, Supabase Auth, or Clerk for role-based administrative authentication.
3. **Email Notifications:** Plug in Resend, SendGrid, or AWS SES to notify corporate executives upon form submission.
4. **File Storage:** Connect AWS S3 or Google Cloud Storage for actual multipart resume and CAD drawing uploads.

---

## 📄 License & Compliance

© 2025–2026 **SKYLIGHT ENGINEERING & ENERGY SOLUTIONS PRIVATE LIMITED**. All rights reserved.  
Registered in Maharashtra, India.
