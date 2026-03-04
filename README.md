# 🧠 Logic Hack

Frontend web application built with **React + TypeScript + Vite**.

Live Site: [https://loot.fossptu.dev/](https://loot.fossptu.dev/)

---

## 🚀 Overview

Logic Hack is a modern web application designed for coding challenges and competitive programming events. It provides a fast, responsive, and scalable frontend architecture using Vite for lightning‑fast builds and React for a modular UI system.

---

## 🛠 Tech Stack

* ⚛️ React
* 🟦 TypeScript
* ⚡ Vite
* 🎨 CSS / Tailwind (if used)
* 🧹 ESLint

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/logic-hack.git
cd logic-hack
```

Install dependencies:

```bash
npm install
```

---

## 💻 Development

Start the development server:

```bash
npm run dev
```

The app will run on:

```
http://localhost:5173
```

---

## 🏗 Build for Production

Create an optimized production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

---

## 📂 Project Structure

```
src/
 ├── assets/
 ├── components/
 ├── pages/
 ├── hooks/
 ├── utils/
 ├── App.tsx
 └── main.tsx
```

---

## 🧹 ESLint Configuration (Optional Advanced Setup)

For production-grade applications, enable type-aware linting:

```js
export default defineConfig([
  globalIgnores(["dist"]),
  {
    files: ["**/*.{ts,tsx}"],
    extends: [
      tseslint.configs.recommendedTypeChecked,
      tseslint.configs.strictTypeChecked,
      tseslint.configs.stylisticTypeChecked,
    ],
    languageOptions: {
      parserOptions: {
        project: ["./tsconfig.node.json", "./tsconfig.app.json"],
        tsconfigRootDir: import.meta.dirname,
      },
    },
  },
]);
```

---

<<<<<<< HEAD
```js
// eslint.config.js
import reactX from "eslint-plugin-react-x";
import reactDom from "eslint-plugin-react-dom";

export default defineConfig([
  globalIgnores(["dist"]),
  {
    files: ["**/*.{ts,tsx}"],
    extends: [
      // Other configs...
      // Enable lint rules for React
      reactX.configs["recommended-typescript"],
      // Enable lint rules for React DOM
      reactDom.configs.recommended,
    ],
    languageOptions: {
      parserOptions: {
        project: ["./tsconfig.node.json", "./tsconfig.app.json"],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
]);
```

"# logic-hack"

````markdown
## Note

If `VITE_PUBLIC_POSTHOG_RHOST` is enabled, please ensure that `localhost` is allowed as a CORS origin in your PostHog settings at [https://us.i.posthog.com/project/YOUR_ID/project-web-analytics/settings/cors](https://us.i.posthog.com/project/YOUR_ID/project-web-analytics/settings/cors) or modify vite.config.ts like

```typescript
  server: {
    proxy: {
      '/ads': {
        target: 'https://ads.yourdomain.com', // or 'https://eu.i.posthog.com' for EU region
        changeOrigin: true,
        secure: true,
        rewrite: (path) => path.replace(/^\/ads/, ''),
      },
    },
  },
```
````

.

```

```
=======
## 🌍 Deployment

This project can be deployed easily on:

* Vercel
* Netlify
* Render
* Any static hosting provider

---

## 📜 License

MIT License

---

## 👨‍💻 Author

Built with ❤️ for competitive programming and logic-based challenges.

---

If you want, I can also create:

* 🔥 A professional GitHub-optimized README with badges
* 📸 Screenshot section
* 🧩 Contributing guidelines
* 🐛 Issue & PR templates
* 🚀 CI/CD setup instructions
>>>>>>> f5626c8164f8f820fac840ac26d31e24ce2b4645
