# Safin Rahman's Portfolio

Welcome to my personal developer portfolio! This project is built to showcase my backend and full-stack engineering skills alongside a passion for crafting premium, high-performance web experiences.

## 🚀 Live Demo

[https://safinrahman.vercel.app](https://safinrahman.vercel.app)

## 🛠️ Built With

*   **[Astro](https://astro.build/)** - For lightning-fast static site generation and component architecture.
*   **[Tailwind CSS v4](https://tailwindcss.com/)** - For rapid, utility-first styling and precise UI design.
*   **[GSAP (GreenSock)](https://gsap.com/)** - Used for complex scroll animations, text scrambling effects, and smooth reveal transitions.
*   **TypeScript** - Ensuring type safety across the Astro components.

## ✨ Key Features

*   **Custom Design System**: A dark-themed, minimalist aesthetic featuring custom noise overlays, animated scanlines, and a dynamic custom cursor.
*   **High Performance**: Leveraging Astro's zero-JS-by-default architecture, meaning interactive scripts (like GSAP) are only loaded when strictly necessary.
*   **Advanced Animations**:
    *   Custom Page Loader with percentage count.
    *   Scroll-triggered reveals across all sections using GSAP `ScrollTrigger`.
    *   Interactive text scrambling effect on hover over links and headers.
    *   Magnetic button hover effects.
    *   Magnetic custom cursor that expands on interactable elements.
*   **Responsive**: Fully responsive design that adapts flawlessly from massive desktop monitors down to mobile devices.

## 📁 Project Structure

```text
/
├── public/                 # Static assets (fonts, images, favicons)
├── src/
│   ├── components/         # Reusable Astro UI components (Hero, Works, About, Contact, etc.)
│   ├── layouts/            # Base HTML wrapper (Layout.astro) containing global scripts/meta tags
│   └── pages/              # Astro routing (index.astro is the main entry point)
│   └── styles/             # Global CSS and Tailwind directives (global.css)
└── astro.config.mjs        # Astro configuration
```

## 🚀 Getting Started

To run this project locally:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/SafinRweb/safinrahman.git
    cd safinrahman
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Start the development server:**
    ```bash
    npm run dev
    ```
    The site will be available at `http://localhost:4321`.

## 📦 Building for Production

To create a production build:

```bash
npm run build
```

This will generate a `dist/` directory with the compiled static files, ready to be deployed to any static hosting provider (Vercel, Netlify, GitHub Pages, etc.).

## 📬 Contact

*   **Email**: [safinr.gg@gmail.com](mailto:safinr.gg@gmail.com)
*   **WhatsApp**: [+8801782213173](https://wa.me/8801782213173)

---
*Designed & Developed by Safin Rahman — Dhaka, Bangladesh*
