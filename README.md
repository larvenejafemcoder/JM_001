# 🌌 Krnl_12301ct — Bootstrapped Beauty - JavascriptMastery1st (JM_001)


> 🚀 A sleek Astro + Vite + TypeScript + Tailwind starter crafted for speed, beauty, and interstellar dev vibes.


## 🧠 Philosophy
```
This project ain't just front-end—it’s **Frontend Quantum Alchemy**.  
Minimal boilerplate, maximum control.  
Built for devs who don't wanna suffer in silence 😭.
```
## 📁 Folder Architecture

```txt
📦 / (Root)
 ┣ 📂 public          # Static files (e.g. favicon, images)
 ┣ 📂 src             # All source code lives here (actual root)
 ┃ ┣ 📂 assets        # Images, fonts, and other media
 ┃ ┣ 📂 components    # Reusable UI blocks
 ┃ ┣ 📂 constants     # 🧠 Only `index.ts` lives here for shared values
 ┃ ┣ 📂 layouts       # Page skeletons, e.g. header/footer
 ┃ ┣ 📂 pages         # Astro pages (routes auto-generated)
 ┃ ┣ 📂 styles        # Tailwind / global CSS
 ┃ ┗ 📂 utils         # Helper functions & client logic
 ┣ 📄 index.html      # Entry point, handled by Astro
 ┣ 📄 vite.config.ts  # Vite config (aliasing, plugins, etc.)
 ┣ 📄 tailwind.config.js # Tailwind custom theme setup
 ┣ 📄 tsconfig.json   # TypeScript settings
 ┗ 📄 README.md       # This file, duh
```


## ⚙️ Tech Stack
```
| Tool           | Description                     |
| -------------- | ------------------------------- |
| 🧞 Vite        | Lightning-fast frontend tooling |
| 🌌 React       | Modern static site frontend    |
| 🌬 TailwindCSS | Utility-first CSS with themeing |
| 🧠 TypeScript  | Type-safe development           |
| 🐾 ESlint      | Code linting (yes it's strict)  |
| 🌲 Prettier    | Code formatting, auto-purified  |
```


## 🚀 Getting Started

```bash
# 1. Install dependencies
npm install

# 2. Dev server with live reload
npm run dev

# 3. Build for production
npm run build

# 4. Preview your site
npm run preview
```

---

## 🧩 Aliases (from `vite.config.ts`)

```ts
import { defineConfig } from 'vite';

export default defineConfig({
  resolve: {
    alias: {
      '@': '/src',             // Absolute import shortcut
      '@components': '/src/components',
      '@assets': '/src/assets',
      '@styles': '/src/styles',
    }
  }
});
```

Use like:

```ts
import Navbar from '@components/Navbar.astro';
import Logo from '@assets/logo.svg';
```

---

## 🎨 Tailwind Goodies

> Theme customized for ✨ cozy vibes ✨ — modify `tailwind.config.js`.

```js
module.exports = {
  content: ['./src/**/*.{astro,html,js,ts,jsx,tsx}'],
  theme: {
    extend: {
      fontFamily: {
        display: ['Poppins', 'sans-serif'],
        code: ['Fira Code', 'monospace'],
      },
      colors: {
        kernel: '#4e4e6a',
        ghost: '#8a7fd9',
      }
    }
  },
  plugins: [],
}
```

---

## 🧼 Linting & Formatting

```bash
# Lint the code
npm run lint

# Format using Prettier
npm run format
```

---

## 🧙 Magic Touches

* Fast startup
* Modular structure
* No clutter
* Zero tracking bloat
* Pookie-approved 🐈

---

## 🧠 Inspired By

* 🧑‍🚀 [Astro.build](https://astro.build)
* 🧵 [Tailwind Labs](https://tailwindcss.com/)
* 💻 Your inner cracked dev self

---

## 📜 License

MIT — use freely, break stuff wisely.

---

> 🪐 Made with caffeine and KernelGhost’s divine madness 🫡
> *"multi-threaded uncertainty with execution"* - Kangism Doctrine

```

```
