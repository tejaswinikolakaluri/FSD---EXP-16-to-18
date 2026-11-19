# Full Stack Development (FSD) — Experiments 16 to 18

This repository contains the practical experiments (16, 17, and 18) for Full Stack Development, implemented using **React** and bundled with **Vite**.

---

## 📁 Repository Structure

```text
├── react-html-render-app-main/      # Experiment 16: React HTML Rendering
├── react-jsx-render-app-main/       # Experiment 17: React JSX Rendering
└── react-rendering-lists-app-main/  # Experiment 18: React List Rendering
```

---

## 📖 Experiments Overview

### 1. Experiment 16: React HTML Rendering App (`react-html-render-app-main`)
- **Objective**: Demonstrate rendering HTML content dynamically inside a React application.
- **Key Concepts**:
  - `createRoot` and DOM mounting.
  - React element hierarchy and HTML tags (`div`, `h1`, `p`).

### 2. Experiment 17: React JSX Rendering App (`react-jsx-render-app-main`)
- **Objective**: Demonstrate JSX syntax, variable interpolation, and dynamic expressions in React.
- **Key Concepts**:
  - Embedding JavaScript expressions into JSX using curly braces `{}`.
  - Composing JSX elements into variables.
  - Rendering dynamic values such as strings and numbers.

### 3. Experiment 18: React List Rendering App (`react-rendering-lists-app-main`)
- **Objective**: Demonstrate rendering structured list data in an HTML table using JavaScript's `.map()`.
- **Key Concepts**:
  - Iterating over an array of objects.
  - Utilizing unique `key` props for list items.
  - Applying custom CSS styling for table structures.

---

## 🛠️ Prerequisites

Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (v20+ recommended)
- [npm](https://www.npmjs.com/) (v10+ recommended)

---

## 🚀 Getting Started

Follow the instructions below to run any of the experiments locally.

### 1. Experiment 16 — React HTML Render App
```bash
cd react-html-render-app-main
npm install
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

---

### 2. Experiment 17 — React JSX Render App
```bash
cd react-jsx-render-app-main
npm install
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

---

### 3. Experiment 18 — React List Rendering App
```bash
cd react-rendering-lists-app-main
npm install
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📦 Available Scripts (in each project)

- `npm run dev`: Starts the Vite development server with Hot Module Replacement (HMR).
- `npm run build`: Generates an optimized production build in the `dist/` directory.
- `npm run preview`: Previews the local production build.
- `npm run lint`: Runs ESLint to check for code quality and syntax errors.
