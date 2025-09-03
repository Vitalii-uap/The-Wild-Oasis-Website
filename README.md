# The Wild Oasis Website

A modern full-stack web application built with **Next.js (App Router)**, **React**, and **Supabase** as the backend.  
This project is part of my learning journey with Next.js and demonstrates concepts like server components, client components, API routes, authentication, and database integration.

---

## Live Demo

Check out the deployed version live at:  
👉 [the-wild-oasis-website-vitalii-uap.vercel.app](https://the-wild-oasis-website-vitalii-uap.vercel.app/)

---

## ✨ Features

- 🏕️ Browse a list of luxury cabins
- 📄 View detailed information about each cabin
- 📅 Make and manage reservations
- 🔐 Authentication with Google (via NextAuth)
- 🗄️ Data stored and retrieved from Supabase
- 🎨 Styled with Tailwind CSS and Heroicons
- ⚡ Optimized with Next.js App Router, server actions, and data caching

## 🛠️ Tech Stack

- **Next.js 13+ (App Router)**
- **React**
- **Supabase** (database + authentication)
- **Tailwind CSS**
- **Heroicons**
- **date-fns**

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Vitalii-uap/The-Wild-Oasis-Website.git
cd The-Wild-Oasis-Website
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a `.env.local` file in the root of the project and add your Supabase credentials:

```env
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
```

### 4. Run the development server

```bash
npm run dev
```

Visit (http://localhost:3000) to see the app running.

## 📂 Project Structure

```
.
├── app/               # Next.js App Router pages and layouts
├── components/        # Reusable React components
├── lib/               # Data fetching logic and Supabase client
├── public/            # Static assets (images, icons, etc.)
├── styles/            # Global styles (Tailwind setup)
└── ...
```

This project is for educational purposes. Feel free to explore and use as reference.
