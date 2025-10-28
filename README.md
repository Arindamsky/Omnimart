# 🛍️ OmniMart - Full Stack E-Commerce Website

OmniMart is a **Next.js full-stack eCommerce platform** that includes both customer and admin interfaces.  
It features authentication, product management, order tracking, and image hosting — all powered by **Next.js 14**, **MongoDB**, **Clerk**, **Cloudinary**, and **Inngest**.

---

## Features

- Built with **Next.js 14 + Tailwind CSS + ShadCN UI**
- Secure **user authentication** with Clerk
- **Admin dashboard** for managing products and orders
- **Cloudinary** integration for image uploads
- **MongoDB** database with Mongoose models
- **Inngest webhooks** for background jobs
- **Deployed on Vercel** for fast and scalable hosting

---

## Getting Started

1. Clone the repo

   ```bash
   git clone https://github.com/Arindamsky/Omnimart
   cd OmniMart
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Create a `.env.local` file in the root directory and add:

   ```bash
   MONGODB_URI=your_mongodb_connection_string
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret
   INNGEST_API_KEY=your_inngest_key
   ```

4. Run locally

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Tech Stack

- **Frontend:** Next.js 14, Tailwind CSS, ShadCN UI
- **Auth:** Clerk
- **Database:** MongoDB (Mongoose)
- **Image Hosting:** Cloudinary
- **Webhooks / Background Jobs:** Inngest
- **Deployment:** Vercel

---



## Developer

**Name:** Arindom Saikia  
**Project:** Full Stack E-Commerce (OmniMart)  
**Year:** 2025  
**GitHub:** [github.com/Arindamsky](https://github.com/Arindamsky)

---

## License

This project is licensed under the **MIT License**.

---

 ⚡ OmniMart — Modern, Secure & Scalable eCommerce built with Next.js.
