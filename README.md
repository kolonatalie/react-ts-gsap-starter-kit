[![React + GSAP + TypeScript Starter Kit](/src/assets/demo.gif)](https://github.com/kolonatalie/react-ts-gsap-starter-kit)
# React + GSAP + TypeScript Starter Kit

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

Professional boilerplate for high-performance web animations and scalable frontend architecture featuring Vite, ESLint 9, and SASS Modules.

## Features
-  Powered by **Vite**.

- Pre-configured with **GSAP** and **@gsap/react** for optimized animation lifecycles.

- **SASS** Modules.

- Strict Quality Gates:

    - Husky-powered pre-commit hooks running **ESLint 9** and **Stylelint**.

- Pre-defined **path aliases** (`@/*`) and atomic folder structure.

## 📁 Project Structure
```
src/
├── assets/      # Static assets (fonts, images)
├── components/  # Atomic UI components (with .module.scss)
├── hooks/       # Custom React & GSAP hooks
├── styles/      # Global SCSS (reset, base, variables, mixins)
├── utils/       # Helper functions & math utilities
└── main.tsx     # Application entry point

```

## Tech Stack

* **Core:** React 18, TypeScript 5, Vite
* **Animation:** GSAP, @gsap/react
* **Styles:** SASS Modules, OKLCH, PostCSS
* **Quality:** ESLint 9, Stylelint, Husky


##  Getting Started

1.  **Clone the repository:**
    
    `git clone` [`https://github.com/kolonatalie/react-ts-gsap-starter-kit.git`](https://github.com/kolonatalie/react-ts-gsap-starter-kit.git)

    ```bash
    cd react-ts-gsap-starter-kit
    ```

2.  **Install:**
    ```bash
    npm install
    ```

3. **Run:**
    ```bash
    npm run dev
    ```

## Demo Component
This starter kit includes a pre-built `Example` component located in `src/components/Example`. It serves as a live demonstration of:
- **GSAP Reveal Animation:** Using `useGSAP` hook and scoped selectors.
- **Fluid Typography:** Implementation of `clamp()` and OKLCH color system.
- **SASS Modules:** Scoped styling with the 7-1 pattern.

**To start with a blank slate:** Simply delete the `src/components/Example` folder and clear the `App.tsx` file.

## Available Scripts
|  |  |
| :--- | :--- |
|`npm run dev`| Starts Vite dev server at `http://localhost:3000` |
|`npm run build`| Runs Type-check (`tsc`) and builds the project with Vendor Splitting (React, GSAP into separate chunks).|
|`npm run preview`| Locally previews the production build|
|`npm run lint`| Audits JS/TS and SCSS for errors.|
|`npm run lint:fix` | Automatically fixes linting and styling issues.|

---

*Created by [kolonatalie](https://github.com/kolonatalie) • Connect: [LinkedIn](https://www.linkedin.com/in/kolonatalie/) | [Portfolio](https://kolonatalie.vercel.app)*