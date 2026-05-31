# AI E-Commerce Project (Next.js + Sanity + Clerk + Stripe + AI)

## 📌 Project Overview
This is a full-stack AI-powered e-commerce application built with modern tools:

- Next.js 16 (Frontend + Backend)
- Sanity CMS (Products & Orders Management)
- Clerk Authentication (User Login System)
- Stripe Payments (Checkout System)
- Vercel AI Gateway (AI Shopping Assistant)

---

## 🚀 How to Run (Local Setup)


### 1. Install Dependencies
> **Important:** Since this project utilizes the latest Next.js 16 and React 19 capabilities, please use the `--legacy-peer-deps` flag during installation to handle deep peer dependencies seamlessly.
npm install --legacy-peer-deps

### 2. Set Up Environment Variables
Please Copy the Env.Local File And Paste In the Project From Email

### 3. Start Development Server
npm run dev

---

## 🌐 Application URLs

- **Main App:** http://localhost:3000  
- **Sanity Studio:** http://localhost:3000/studio  

---

## 🧠 Features

### Customer Features
- Browse and filter premium products fetched dynamically from Sanity CMS
- Interactive, persistent shopping cart experience
- Secure Stripe Checkout Integration
- Context-aware AI Shopping Assistant for smart natural language product discovery
- Protected User Profiles and Order History tracks via Clerk Authentication

### Admin Features
- Comprehensive Sanity Studio dashboard to manage products, categories, and inventory
- Live order tracking and transactional logging
- Schema-enforced real-time data streaming and instant updates using Sanity Live API

---

## 💳 Stripe Integration
- Fully operating in Stripe Test Mode for risk-free sandbox environments
- Automated Webhook architecture listening for secure `checkout.session.completed` events
- Immediate, hands-off order generation inside Sanity after successful checkout confirmation

---

## 🤖 AI Assistant
- Intuitively designed conversational product search interface
- Robust natural language query parsing utilizing state-of-the-art LLMs
- Optimized backend delivery via Vercel AI Gateway (Claude Model Integration)

---

## 🚀 Deployment

- Live Demo: **ADD_DEPLOYMENT_LINK_HERE**

---

## ✅ Run Checklist
- [ ] Repository cloned and directory targeted properly
- [ ] npm install --legacy-peer-deps completed successfully
- [ ] Local environment variables properly configured inside .env.local
- [ ] Next.js development server active via npm run dev
- [ ] Sanity Studio dashboard accessible at /studio
- [ ] Stripe webhooks configured for order management lifecycle testing

---

## 🎯 Final Step
Clone the project ➔ install dependencies using the legacy flag ➔ configure environment variables ➔ run locally. Everything is configured and ready to build! 🚀