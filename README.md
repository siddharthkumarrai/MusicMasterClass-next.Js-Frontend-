<div align="center">

# 🎵 MusicMasterClass

**A modern, animated music-school website built with Next.js 14, TypeScript, and Tailwind CSS.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://musicmasterclass.vercel.app/)
![Next.js](https://img.shields.io/badge/Next.js-14-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-11-0055FF?style=for-the-badge&logo=framer&logoColor=white)

[**View Live Demo**](https://musicmasterclass.vercel.app/) · [**Watch Demo Video**](https://res.cloudinary.com/dombv2xju/video/upload/v1790262915/Screen_Recording_2026-09-24_203728_ve1vuo.mp4) · [**Report a Bug**](https://github.com/siddharthkumarrai/MusicMasterClass-next.Js-Frontend-/issues)

</div>

---

## 📖 Table of Contents

- [About the Project](#-about-the-project)
- [Demo](#-demo)
- [Features](#-features)
- [Pages and Routes](#-pages-and-routes)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Available Scripts](#-available-scripts)
- [Deployment](#-deployment)
- [What I Learned](#-what-i-learned)
- [Roadmap](#-roadmap)
- [Author](#-author)
- [Acknowledgements](#-acknowledgements)

---

## 📌 About the Project

**MusicMasterClass** is a front-end learning project: a complete marketing and course-catalog website for a fictional music school. It was built to practise the modern React ecosystem with **Next.js**, **TypeScript**, and **Tailwind CSS**, and to explore polished, animated UI design with **Framer Motion**.

The site lets visitors explore courses across guitar, vocals, and music production, read student testimonials, browse webinars, meet the instructors, and get in touch with the school.

> This is a **frontend-only** project. It focuses on UI, routing, and design, and does not include a backend or real course data.

## 🎬 Demo

**Live site:** 👉 [musicmasterclass.vercel.app](https://musicmasterclass.vercel.app/)

**Screen recording:** click the preview below to watch the walkthrough.

<div align="center">

[![MusicMasterClass demo video](https://res.cloudinary.com/dombv2xju/video/upload/so_3/v1790262915/Screen_Recording_2026-09-24_203728_ve1vuo.jpg)](https://res.cloudinary.com/dombv2xju/video/upload/v1790262915/Screen_Recording_2026-09-24_203728_ve1vuo.mp4)

</div>

## ✨ Features

- **Hero landing section**: a bold "Master the art of music" introduction with a clear call to action to explore courses.
- **Featured courses**: cards for Guitar Fundamentals, Advanced Vocal Techniques, Music Production Fundamentals, Electronic Music Production, and Blues Guitar Techniques, each linking to its own detail page.
- **Dynamic course pages**: a route per course (`/courses/[slug]`) plus a full course listing at `/courses`.
- **Value-proposition sections**: personalised instruction, live feedback and engagement, cutting-edge curriculum, and limitless learning opportunities.
- **Student testimonials**: a "Voices of success" section with feedback from students of different instruments.
- **Featured webinars**: a grid of webinar topics such as music theory, songwriting, and live performance.
- **Instructor showcase**: a "Meet Our Instructors" section with optimised profile images.
- **Contact page**: a dedicated `/contact` route.
- **Rich animations**: smooth, interactive motion powered by Framer Motion.
- **Optimised images**: uses the Next.js `Image` component for automatic resizing and lazy loading.
- **Fully typed**: written in TypeScript for safer, more maintainable code.
- **Responsive design**: styled with Tailwind CSS utility classes.

<!-- Adjust this list to match exactly what is implemented in src/, e.g. dark mode, sticky scroll, background effects, contact form. -->

## 🧭 Pages and Routes

| Route | Description |
| --- | --- |
| `/` | Home page: hero, featured courses, benefits, testimonials, webinars, instructors, footer |
| `/courses` | Full list of available courses |
| `/courses/[slug]` | Individual course page (for example `/courses/guitar-fundamentals`) |
| `/contact` | Contact page |

### Featured courses

| Course | Slug |
| --- | --- |
| Guitar Fundamentals | `guitar-fundamentals` |
| Advanced Vocal Techniques | `advanced-vocal-techniques` |
| Music Production Fundamentals | `music-production-fundamentals` |
| Electronic Music Production | `electronic-music-production` |
| Blues Guitar Techniques | `blues-guitar-techniques` |

## 🛠️ Tech Stack

| Category | Technology |
| --- | --- |
| **Framework** | [Next.js 14.1.4](https://nextjs.org/) |
| **UI library** | [React 18](https://react.dev/) |
| **Language** | [TypeScript 5](https://www.typescriptlang.org/) |
| **Styling** | [Tailwind CSS 3](https://tailwindcss.com/), PostCSS, Autoprefixer |
| **Animation** | [Framer Motion 11](https://www.framer.com/motion/) |
| **Visual effects** | `simplex-noise` for procedural noise-based effects |
| **Class utilities** | `clsx` and `tailwind-merge` for conditional, conflict-free class names |
| **SVG utilities** | `mini-svg-data-uri` for inline SVG backgrounds |
| **Code display** | `react-element-to-jsx-string` |
| **Linting** | ESLint with `eslint-config-next` |
| **Hosting** | [Vercel](https://vercel.com/) |

## 📁 Project Structure

```
MusicMasterClass-next.Js-Frontend-/
├── public/                 # Static assets
├── src/                    # Application source (pages, components, utilities)
├── .eslintrc.json          # ESLint configuration
├── .gitignore              # Files excluded from version control
├── next.config.mjs         # Next.js configuration (e.g. remote image domains)
├── postcss.config.js       # PostCSS configuration
├── tailwind.config.ts      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
├── package.json            # Dependencies and npm scripts
├── package-lock.json       # Locked dependency versions
└── README.md               # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** v20 or later (recommended)
- **npm** (bundled with Node.js)

```bash
node -v
npm -v
```

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/siddharthkumarrai/MusicMasterClass-next.Js-Frontend-.git
```

**2. Move into the project folder**

```bash
cd MusicMasterClass-next.Js-Frontend-
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm run dev
```

**5. Open the app**

Visit [http://localhost:3000](http://localhost:3000) in your browser. The page hot-reloads as you edit files.

## 📜 Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Starts the development server with Fast Refresh |
| `npm run build` | Creates an optimised production build |
| `npm run start` | Runs the production build locally (run `build` first) |
| `npm run lint` | Lints the codebase with ESLint |

## ☁️ Deployment

The site is deployed on **Vercel**, the platform built by the creators of Next.js.

1. Push the project to GitHub.
2. Go to [vercel.com/new](https://vercel.com/new) and import this repository.
3. Vercel detects Next.js automatically. Keep the default settings:

   | Setting | Value |
   | --- | --- |
   | Framework preset | Next.js |
   | Build command | `next build` |
   | Output directory | `.next` |

4. Click **Deploy**. Every push to `main` triggers a new production deployment.

## 🎓 What I Learned

<!-- Trim or edit this list so it matches what you actually built. -->

- **Next.js fundamentals**: file-based routing, layouts, and dynamic routes (`/courses/[slug]`).
- **TypeScript in React**: typing props, data, and components.
- **Tailwind CSS**: building responsive layouts quickly with utility classes, and merging classes safely with `clsx` and `tailwind-merge`.
- **Animation**: creating smooth, interactive UI with Framer Motion.
- **Image optimisation**: using `next/image` with remote images and configuring allowed domains.
- **Component design**: splitting a large page into reusable, well-organised sections.
- **Project tooling**: ESLint, PostCSS, and TypeScript configuration in a Next.js app.
- **Deployment**: shipping a production Next.js app to Vercel.

## 🗺️ Roadmap

Planned improvements:

- [ ] Update the page title and meta description (they still show the "Create Next App" defaults) and add Open Graph tags for SEO
- [ ] Replace placeholder footer details (email, phone, address) with real ones
- [ ] Point the webinar links and footer quick links to real pages
- [ ] Add a working contact form with validation
- [ ] Add a backend or CMS for courses, instructors, and webinars
- [ ] User authentication and course enrolment
- [ ] Add a search and filter for the course catalogue
- [ ] Dark mode toggle
- [ ] Accessibility audit (keyboard navigation, ARIA labels, reduced-motion support)
- [ ] Add unit and end-to-end tests (Jest, Playwright)
- [ ] Update the copyright year in the footer

## 👤 Author

**Siddharth Kumar Rai**

- GitHub: [@siddharthkumarrai](https://github.com/siddharthkumarrai)
- Live project: [musicmasterclass.vercel.app](https://musicmasterclass.vercel.app/)

## 🙏 Acknowledgements

- [Next.js documentation](https://nextjs.org/docs) and [Tailwind CSS documentation](https://tailwindcss.com/docs)
- [Framer Motion](https://www.framer.com/motion/) for the animation library
- [Unsplash](https://unsplash.com/) for the instructor photography
- [Vercel](https://vercel.com/) for free, seamless hosting

---

<div align="center">

⭐ If this project helped you learn something, consider giving it a star!

*Built while learning Next.js, TypeScript, and modern front-end development.*

</div>
