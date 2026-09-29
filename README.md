<div align="center">

  # 🌟 Dhruvraj Zala — Personal Portfolio & AI Showcase

  <p align="center">
    <strong>An ultra-modern, high-performance 3D interactive developer portfolio built with React 19, TypeScript, Tailwind CSS v4, and Lightswind UI.</strong>
  </p>

  <p align="center">
    <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-19.1.1-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React 19" /></a>
    <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-5.8-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /></a>
    <a href="https://vite.dev/"><img src="https://img.shields.io/badge/Vite-7.1-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" /></a>
    <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind_CSS-v4.1-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" /></a>
    <a href="https://www.framer.com/motion/"><img src="https://img.shields.io/badge/Framer_Motion-12.23-black?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" /></a>
    <a href="https://threejs.org/"><img src="https://img.shields.io/badge/Three.js-0.185-black?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js" /></a>
  </p>

  <p align="center">
    <a href="#-key-features">Key Features</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-project-structure">Project Structure</a> •
    <a href="#-getting-started">Getting Started</a> •
    <a href="#-customization">Customization</a> •
    <a href="#-contact">Contact</a>
  </p>

</div>

---

## 📖 Overview

This repository contains the source code for the personal portfolio of **Dhruvraj Zala**, an AI & Full-Stack Developer and MCA student specializing in Artificial Intelligence. 

Designed with modern visual aesthetics and high performance in mind, this portfolio showcases machine learning applications, full-stack web platforms, technical proficiencies, academic milestones, and career experiences.

---

## ✨ Key Features

- 🪪 **Interactive 3D Hanging ID Badge**: Realistic physics-based interactive hanging lanyard card with 3D motion, custom tags, and dynamic lighting.
- 🌌 **Aurora & Morphing Text Effects**: Vibrant gradient headers and animated morphing typography powered by modern CSS shaders and Framer Motion.
- 🪄 **Interactive Magic Cards**: Spotlight cards with cursor-following radial gradient borders and subtle glassmorphism effects.
- 🍏 **macOS-Style Dynamic Dock**: Floating desktop dock with magnification and smooth scroll triggers to navigate effortlessly between sections.
- ⏱️ **Interactive Journey Timeline**: Animated milestone tracker with dynamic progress line filling as the user scrolls.
- 🍱 **12-Column Bento Grid Showcase**: Highlighting featured Machine Learning and Web Development projects with rich preview overlays.
- 🌊 **Ultra-Smooth Inertia Scrolling**: Integrated with [Lenis](https://github.com/darkroomengineering/lenis) for smooth kinetic scrolling experience.
- 🌗 **Dark & Light Mode Support**: Seamless theme switching with persistent user preference powered by `next-themes`.
- ⚡ **Zero Layout Shift & Lazy Loading**: Below-the-fold component chunking with React 19 `Suspense` and skeleton loaders for instant page loads.
- 📱 **Fully Responsive Design**: Optimized across mobile, tablet, and ultra-wide displays.

---

## 🛠️ Tech Stack

### **Core & Framework**
- **React 19** — Latest component architecture and modern Hooks
- **TypeScript 5.8** — Strict type safety and robust developer experience
- **Vite 7** — Lightning-fast HMR and optimized build bundling

### **Styling & Design System**
- **Tailwind CSS v4** — Cutting-edge utility-first styling engine
- **Lightswind UI** — Curated collection of high-end motion and interactive components
- **Geist Font** — Clean, modern typography designed for high-clarity interfaces

### **Animation & 3D Graphics**
- **Framer Motion 12** — Declarative UI animations and gesture interactions
- **Three.js** — 3D graphics rendering capabilities
- **GSAP & @gsap/react** — High-performance scripted timeline animations
- **Lenis** — Smooth kinetic scrolling physics

### **Icons & Utilities**
- **Lucide React** — Crisp and consistent vector icon set
- **clsx & tailwind-merge** — Conditional class composition

---

## 📂 Project Structure

```text
portfolio01/
├── public/                     # Static assets (images, icons, resumes)
│   ├── dhruvraj.jpg            # Profile avatar
│   └── vite.svg
├── src/
│   ├── assets/                 # Local images and graphic resources
│   ├── components/             # Reusable UI modules & section blocks
│   │   ├── AboutSection/       # Bio, highlights, and quick statistics
│   │   ├── CareerSection/      # Interactive scroll timeline & experience
│   │   ├── ContactSection/     # Contact channels and message form
│   │   ├── EducationSection/   # Academic milestones & skill categories
│   │   ├── Footer/             # Morphing text, navigation & credits
│   │   ├── Header/             # Responsive navbar with theme switcher
│   │   ├── HeroSection/        # Hero header, CTA & 3D Hanging ID Card
│   │   ├── ProjectsSection/    # Bento grid showcasing featured projects
│   │   ├── ServicesSection/    # What I Know / Technical specialties
│   │   ├── TechStackSection/   # Infinite marquee of technologies
│   │   └── lightswind/         # Modular motion components (Dock, Cards, Badges)
│   ├── hooks/                  # Custom React hooks
│   ├── lib/                    # Helper functions & utility methods (cn, etc.)
│   ├── App.tsx                 # Application layout, Lenis setup & lazy loading
│   ├── index.css               # Design tokens, theme variables & Tailwind setup
│   ├── lightswind.css          # Animation keyframes & custom effect styles
│   └── main.tsx                # React root entry point
├── index.html                  # HTML template with SEO metadata & preloads
├── package.json                # Project dependencies and npm scripts
├── tsconfig.json               # TypeScript compiler configuration
└── vite.config.ts              # Vite bundler configuration with React SWC
```

---

## 🚀 Getting Started

Follow these steps to run the portfolio locally on your machine:

### **Prerequisites**
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version `18.x` or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) / [pnpm](https://pnpm.io/)

### **Installation**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/portfolio01.git
   cd portfolio01
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open your browser:**
   Navigate to `http://localhost:5173` to view the live site.

---

## 🔧 Available Scripts

In the project directory, you can run:

| Command | Description |
| :--- | :--- |
| `npm run dev` | Starts the Vite local development server with Hot Module Replacement (HMR) |
| `npm run build` | Runs TypeScript type-checking and builds the production bundle into `/dist` |
| `npm run preview` | Locally previews the production build output |
| `npm run lint` | Runs ESLint to inspect code quality and catch syntax issues |

---

## 🎨 Customization Guide

You can easily adapt this portfolio with your own details:

1. **Personal Information & Bio:**
   - Modify `src/components/HeroSection/HeroSection.tsx` to update your name, headline, summary, and social links.
   - Update your profile picture in `public/dhruvraj.jpg` or replace it in `HeroSection.tsx`.

2. **Featured Projects:**
   - Edit the `projects` array in `src/components/ProjectsSection/ProjectsSection.tsx` to showcase your own applications, GitHub repositories, and live demo links.

3. **Career & Academic Journey:**
   - Update `careerEvents` in `src/components/CareerSection/CareerTimeline.tsx` and degree information in `src/components/EducationSection/EducationSection.tsx`.

4. **Technical Skills & Tools:**
   - Customize `technologies` in `src/components/TechStackSection/TechStackSection.tsx` and skill matrices in `src/components/EducationSection/SkillCategory.tsx`.

---

## 📬 Contact & Connect

- **Name:** Dhruvraj Zala
- **Specialization:** AI & Full Stack Development (MCA AI)
- **Email:** [dhruvrajsinhzala2002@gmail.com](mailto:dhruvrajsinhzala2002@gmail.com)
- **Phone:** [+91 75670 12355](tel:+917567012355)
- **Location:** Anand, Gujarat, India

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — feel free to use it as inspiration or a template for your personal portfolio.

<div align="center">
  <sub>Designed & Developed with ❤️ by Dhruvraj Zala</sub>
</div>
