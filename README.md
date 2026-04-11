# 🌐 Silent Echoes: The Global History of Deaf Education

![Accessibility](https://img.shields.io/badge/Accessibility-WCAG_2.2_AAA-success?style=for-the-badge)
![Tech Stack](https://img.shields.io/badge/Stack-Next.js_|_Three.js-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)

**Silent Echoes** is a state-of-the-art, open-source educational platform designed specifically for teacher candidates. Its mission is to illuminate the rich, complex, and evolving history of Deaf Education around the world through a deeply immersive, futuristic, and 100% accessible web interface.

---

## ✨ Project Vision & Features

We are building the gold standard in educational technology. The platform merges rigorous historical curriculum with a cutting-edge "futuristic glassmorphism" UI.

* **Interactive 3D Navigation:** A rotatable, WebGL-powered holographic globe serves as the primary timeline and geographic navigation tool.
* **Immersive Curriculum:** Comprehensive modules covering everything from the early pioneers (1500s) and the Milan Conference (1880) to the Deaf President Now movement and modern bilingual-bicultural education.
* **Gamified Comprehension Checks:** Low-stakes, scenario-based interactive assessments (drag-and-drop timelines, holographic flashcards) ensure knowledge retention.
* **Absolute Accessibility (WCAG 2.2 AAA):**
    * Picture-in-picture Sign Language interpretation (ASL, BSL, IS) for all media.
    * Advanced, customizable closed captioning and searchable transcripts.
    * Flawless screen reader and keyboard navigation semantics.
    * Motion-reduction toggles for neurodivergent and motion-sensitive users.

---

## 🛠️ Technology Stack

This project leverages modern, high-performance web technologies:

* **Frontend Framework:** [Next.js](https://nextjs.org/) (React)
* **3D Graphics & Animations:** [Three.js](https://threejs.org/) / [React Three Fiber](https://docs.pmnd.rs/react-three-fiber) / [Framer Motion](https://www.framer.com/motion/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (Custom Dark-Mode Glassmorphism)
* **Backend & Auth:** [Supabase](https://supabase.com/) (PostgreSQL)
* **Deployment:** Vercel

---

## 📂 Repository Structure

```text
silent-echoes/
├── public/                 # Static assets, 3D models, and global icons
├── src/
│   ├── app/                # Next.js App Router (Pages & API routes)
│   ├── components/         
│   │   ├── ui/             # Reusable glassmorphic UI components
│   │   ├── 3d/             # Three.js canvas, globe, and spatial elements
│   │   └── accessible/     # Screen-reader tailored and ASL video wrappers
│   ├── lib/                # Utility functions and database clients
│   ├── content/            # MDX files containing the historical curriculum
│   └── styles/             # Global CSS and Tailwind configurations
├── .eslintrc.json          # Linting rules strict for accessibility
├── tailwind.config.js      # Custom theme definitions
└── package.json
