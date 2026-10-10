# SEEDSTACK Frontend Client 🌾

AI-Powered Farmer-to-Vendor Agricultural Marketplace (Telangana & Andhra Pradesh)

## 📌 Project Overview
SEEDSTACK is a digital agricultural platform engineered for Telangana and Andhra Pradesh that connects farmers directly with commercial buyers (wholesalers, supermarkets, processors) with zero middlemen commission fees.

This repository contains the standalone **Frontend Client** application built with Next.js 14 App Router, Tailwind CSS, Lucide icons, and bilingual Telugu/English support.

## 🚀 Key Frontend Features
- **Kisan Simple Mode**: High-contrast, oversized touch cards with voice-assisted Telugu prompts designed for rural accessibility.
- **Dual Role Portals**: Strict UI barrier separation for Farmers (`/farmer/dashboard`) and Commercial Buyers (`/buyer/dashboard`).
- **Interactive Mandi Marketplace**: Real-time filters for cereals, spices, vegetables, and cash crops across TS/AP districts.
- **Live Transit & Weighbridge Tracking**: Digital Dharma Kanta slips and Leaflet GPS transit route visualization.
- **Bilingual Interface**: Full instant switching between Telugu (తెలుగు) and English.
- **Integrated Profile & Safety**: Floating edge back buttons (`CloseEdgeButton`) and contained user profile dropdown.

## 🛠️ Tech Stack
- **Framework**: Next.js 14 (App Router)
- **UI Library**: React 18, Tailwind CSS, Lucide React
- **Maps & Charts**: Leaflet, React-Leaflet, Recharts
- **Type Safety**: TypeScript 5, Zod, React Hook Form

## ⚙️ Setup & Development
```bash
# 1. Install dependencies
npm install

# 2. Configure environment
cp .env.example .env.local
# Set NEXT_PUBLIC_API_URL to your deployed backend or leave blank for integrated routes

# 3. Start local development server
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to view the application.
