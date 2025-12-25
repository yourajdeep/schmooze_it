# 💬 Schmooze it

A **private, real-time chat application** built with a modern full-stack TypeScript ecosystem.  
Designed for speed, scalability, and developer experience.

---

## ✨ Features

- 🔒 **Private 1-to-1 chat**
- ⚡ **Fast & reactive UI**
- 🧠 **Type-safe validation**
- 🔁 **Efficient server state management**
- 🧩 **Modular & scalable architecture**
- 🌙 **Dark mode ready**
- 📱 **Responsive design**

---

## 🛠 Tech Stack

### Frontend
- **Next.js** – App Router, Server Components
- **React**
- **Tailwind CSS**
- **TanStack Query** – Server state & caching

### Backend
- **Elysia** – Lightweight, high-performance server
- **Zod** – Schema validation & type safety

### Tooling
- **TypeScript**
- **ESLint**
- **Prettier**

---

## 📁 Project Structure

```bash
schmooze-it/
├── app/                # Next.js app router
│   ├── layout.tsx
│   ├── page.tsx
│   └── globals.css
├── components/         # Reusable UI components
├── lib/                # Utilities & helpers
├── server/             # Elysia backend logic
├── schemas/            # Zod schemas
├── hooks/              # Custom React hooks
├── public/             # Static assets
├── README.md
└── package.json
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/schmooze-it.git
cd schmooze-it
```

### 2️⃣ Install dependencies
```bash
npm install
# or
pnpm install
```

### 3️⃣ Run the development server
```bash
npm run dev
```
Visit 👉 http://localhost:3000

---

## 🧪 Environment Variables
Create a .env.local file:
```env
NEXT_PUBLIC_API_URL=http://localhost:3001
```
(Extend this as your project grows.)

---

## 🧠 Why These Technologies?

| Technology | Why It Was Chosen |
|-----------|------------------|
| **Next.js** | Full-stack React framework with App Router, SSR, and great developer experience |
| **Elysia** | Ultra-fast, lightweight backend optimized for modern runtimes |
| **Zod** | Runtime schema validation with full TypeScript inference |
| **TanStack Query** | Powerful server-state management, caching, and background syncing |
| **Tailwind CSS** | Utility-first styling for rapid and consistent UI development |
| **TypeScript** | End-to-end type safety and better maintainability |