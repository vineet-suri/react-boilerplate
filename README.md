# React + TypeScript + Vite Boilerplate

This repository provides a well-structured React + TypeScript boilerplate using Vite, with pre-configured ESLint, Prettier, and essential libraries for building scalable applications.

---

## Features

- **Fast Build Times** – Optimized with Vite
- **TypeScript Support** – Ensures type safety
- **ESLint & Prettier** – Code linting and formatting
- **React Router** – Pre-configured for client-side routing
- **State Management Ready** – Can integrate with Zustand, Redux Toolkit, or Context API
- **SCSS / TailwindCSS Support** – Flexible styling options

---

## Folder Structure

```
📦 my-react-app
├── 📂 public                # Static assets
│   ├── index.html
│   ├── favicon.ico
├── 📂 src                   # Main source code
│   ├── 📂 assets            # Images, fonts, and other assets
│   ├── 📂 components        # Reusable UI components
│   ├── 📂 hooks             # Custom React hooks
│   ├── 📂 layouts           # Layout components (Header, Footer, etc.)
│   ├── 📂 pages             # Page-level components (e.g., Home, About)
│   ├── 📂 services          # API calls and services (Axios setup)
│   ├── 📂 store             # Redux Toolkit / Zustand store (if needed)
│   ├── 📂 styles            # Global styles
│   ├── 📂 utils             # Utility functions
│   ├── App.tsx             # Main App component
│   ├── main.tsx            # Entry point
│   ├── routes.tsx          # Route definitions
│   ├── index.css           # Global styles
│   └── vite-env.d.ts       # Vite environment types
├── 📂 tests                 # Unit & integration tests
├── .eslintrc.cjs            # ESLint configuration
├── .prettierrc              # Prettier configuration
├── .gitignore               # Git ignore file
├── package.json             # Dependencies & scripts
├── tsconfig.json            # TypeScript configuration
├── README.md                # Documentation
└── vite.config.ts           # Vite configuration
```

## Getting Started

### 1. Install Dependencies

Ensure Node.js is installed, then run:

```sh
npm install
```

### 2. Start Development Server

To start the development server, run:

```sh
npm run dev
```

The application will be available at [http://localhost:5173/](http://localhost:5173/).

### 3. Build for Production

To generate an optimized build, run:

```sh
npm run build
```

### 4. Run ESLint

To check for linting issues:

```sh
npm run lint
```

## Configuration

- **ESLint settings** are in `eslint.config.js`
- **Prettier settings** are in `.prettierrc`
- **Environment variables** should be placed in a `.env` file

## Styling Options

The project is compatible with SCSS, TailwindCSS, and Styled Components. Default styles are located in `src/styles/`.

## VS Code Extensions

For better development experience, install:

1. **ESLint** – For linting TypeScript and JavaScript.
2. **Prettier - Code formatter** – For consistent code formatting.
3. **Tailwind CSS IntelliSense** (if using TailwindCSS).
