# Pulsyn-core

A ritual OS of rhythm, memory, and presence.

## 🔮 What is Pulsyn?
Pulsyn is a minimal, poetic OS designed to explore flow, memory, and presence in the digital age—blending rhythm, infrastructure, and scrolls.

## 💻 Tech Stack
- Next.js
- Tailwind CSS *(coming soon)*
- Vercel
- GitHub

## 🌐 Domains
- [pulsyn.app](https://www.pulsyn.app) – Primary scroll
- pulsyn.com – Brand alias (redirects to `.app`)
- pulsyn.io – Dev docs or platform base (optional future use)

## 🚀 Local Dev Setup

```bash
git clone https://github.com/BullyNinja/Pulsyn-core.git
cd Pulsyn-core
npm install
npm run dev

> ✅ Once updated, commit & push. Your scroll intro is now clean and public.

---

## 🌅 3. Deploy a Styled Landing Scroll

Let’s drop a minimal but stylized homepage using **Next.js + Tailwind CSS**.

### 🧵 Install Tailwind CSS

In your root project folder:

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
content: ["./pages/**/*.{js,ts,jsx,tsx}", "./components/**/*.{js,ts,jsx,tsx}"],
theme: {
  extend: {},
},
plugins: [],
@tailwind base;
@tailwind components;
@tailwind utilities;
import '../styles/globals.css'
export default function Home() {
  return (
    <main className="flex min-h-screen items-center justify-center bg-black text-white">
      <div className="text-center space-y-4">
        <h1 className="text-4xl font-bold tracking-wide">Pulsyn</h1>
        <p className="text-lg">A ritual OS of rhythm, memory, and presence.</p>
      </div>
    </main>
  );
}
