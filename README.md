# SEHSAA Solutions - Enterprise & Government-Grade Digital Transformation Partner

Welcome to the official codebase for the **SEHSAA Solutions** website. This project is built as a modern, high-performance static site using **Vite**, **Tailwind CSS**, and a component-based HTML architecture.

## 🚀 functionalities

-   **Component-Based Architecture**: Reusable HTML components using `vite-plugin-html-inject`.
-   **Modern Styling**: Styled with **Tailwind CSS v4**.
-   **Performance Optimized**: Fast builds and optimized assets via Vite.
-   **Responsive Design**: Mobile-first approach for all pages.
-   **Theme Support**: Built-in dark and light mode compatibility.

## 🛠️ Prerequisites

Before you begin, ensure you have the following installed on your machine:

-   **Node.js** (version 18 or higher recommended)
-   **npm** (Node Package Manager)

## 📦 Setup & Installation

Follow these steps to set up the project locally:

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd Sehsaa
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

## 💻 Development

To start the local development server with hot-reloading:

```bash
npm run dev
```

The server will typically start at `http://localhost:5173`. Open this URL in your browser to view the site.

## 🏗️ Building for Production

To create an optimized production build:

```bash
npm run build
```

The output will be generated in the `dist/` directory, ready for deployment.

## 📂 Project Structure

```
Sehsaa/
├── public/                  # Static assets (images, icons, fonts)
├── src/
│   ├── components/          # Reusable HTML components
│   │   ├── pages/           # Page-specific components (e.g., app-development)
│   │   └── shared/          # Shared components (Header, Footer, Menu)
│   ├── js/                  # JavaScript logic and animations
│   ├── styles/              # Global and component-specific CSS
│   └── main.js              # Application entry point
├── *.html                   # Main HTML pages
├── package.json             # Project dependencies and scripts
├── vite.config.js           # Vite configuration
└── README.md                # Project documentation
```

## 🎨 Customization

-   **Styles**: Global styles are located in `src/styles/`. Tailwind configuration works via the CSS files.
-   **Components**: Edit HTML components in `src/components/`. Changes are injected automatically during development.
-   **Assets**: Place new images or icons in `public/images/` and reference them as `/images/...` in your HTML.


