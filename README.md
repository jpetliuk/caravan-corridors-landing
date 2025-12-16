# Caravan Corridors Database - Landing Page

The official landing page for **Caravan Corridors Database**, an offline-first digital data collection tool designed for modern archaeology.

## 🚀 Live Site
https://jpetliuk.github.io/caravan-corridors-landing/

## 🛠 Tech Stack
*   **Framework**: [Astro](https://astro.build/) - High performance static site generator.
*   **Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework.
*   **Deployment**: GitHub Pages (via GitHub Actions).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:4321`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## 📦 Deployment

This project is configured to automatically deploy to GitHub Pages whenever changes are pushed to the `main` branch.

### Workflow
The workflow is defined in `.github/workflows/deploy.yml` and performs the following:
1.  Checkouts the code.
2.  Sets up Node.js.
3.  Installs dependencies (`npm ci`).
4.  Builds the site (`npm run build`).
5.  Deploys the `./dist` folder to GitHub Pages.

## 📂 Project Structure

```text
/
├── public/                 # Static assets (favicon, etc.)
├── src/
│   ├── assets/             # Images and optimized assets
│   ├── components/         # Reusable Astro components (Hero, Navbar, etc.)
│   ├── layouts/            # Page layouts
│   └── pages/              # Routing (index.astro, download.astro)
├── astro.config.mjs        # Astro configuration (base path, integrations)
└── tailwind.config.mjs     # Tailwind configuration
```
