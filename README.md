# Foundation React

A modern, lightweight React starter template built with Vite, TypeScript, Tailwind CSS, ESLint, and Prettier — designed for rapid development with best practices out of the box.

---

## Features

- ⚡️ **Blazing-fast dev server** with Vite
- 💪 **TypeScript** support with strict type checking
- 🎨 **Tailwind CSS** for utility-first styling
- 🔍 **ESLint** + **Prettier** for consistent code style
- 📦 Dependency management with **pnpm**
- ✅ Pre-commit hooks with **Husky** and **lint-staged**
- 📚 Opinionated folder structure and example components
- 🛠️ Ready-to-use React Router integration
- 🎯 Focus on developer experience and performance

---

## Getting Started

### Prerequisites

- Node.js >= 18.20.3
- pnpm >= 10 (or npm/yarn, adjust scripts accordingly)

### Installation

```bash
pnpm install
```

### Development

```bash
pnpm dev
```

Open your browser and navigate to [http://localhost:5173](http://localhost:5173)

### Build

```bash
pnpm build
```

### Preview

```bash
pnpm preview
```

---

## Scripts

| Script              | Description                                  |
| ------------------- | -------------------------------------------- |
| `pnpm dev`          | Start the development server                 |
| `pnpm build`        | Build the project for production             |
| `pnpm preview`      | Preview the production build                 |
| `pnpm lint`         | Run ESLint to check code style errors        |
| `pnpm lint:fix`     | Auto-fix ESLint errors                       |
| `pnpm format`       | Format code using Prettier                   |
| `pnpm format:check` | Check code formatting without fixing         |
| `pnpm type-check`   | Run TypeScript type checking                 |
| `pnpm upgrade`      | Upgrade dependencies using npm-check-updates |

---

## Folder Structure

```
├── public/                # Static assets (favicons, manifest, images)
├── src/
│   ├── components/        # Reusable React components
│   ├── pages/             # Page components and routes
│   ├── styles/            # Global and Tailwind CSS configs
│   ├── hooks/             # Custom React hooks
│   ├── utils/             # Utility functions
│   ├── App.tsx            # Root React component
│   ├── main.tsx           # Entry point
│   └── ...
├── .eslintrc.js           # ESLint config
├── .prettierrc            # Prettier config
├── tailwind.config.js     # Tailwind config
├── tsconfig.json          # TypeScript config
├── vite.config.ts         # Vite config
└── package.json
```

---

## Recommendations

- Customize Tailwind configuration as needed.
- Add testing framework and write tests.
- Extend ESLint rules or add plugins if desired.
- Integrate state management or API libraries depending on project needs.

---

## License

MIT License © Diwash Bhattarai
