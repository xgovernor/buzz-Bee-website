# Buzz and Bee Digital

Welcome to the official repository for **Buzz and Bee Digital**, a top-tier digital agency providing expert Design, Development, and Marketing services globally from Bangladesh.

This project is built using **Astro** for lightning-fast performance and **Tailwind CSS v4** for flexible, modern styling.

---

## 🚀 Project Setup

To get the project up and running locally, follow these steps:

### 1. Install Dependencies
Run the following command to install all required packages. (Note: We use `--legacy-peer-deps` to ensure compatibility with our specific Vite and Astro versions).
```bash
npm install --legacy-peer-deps
```

### 2. Start the Development Server
```bash
npm run dev
```
The site will be available at `http://localhost:4321/`.

### 3. Build for Production
To generate a static build, run:
```bash
npm run build
```
Your compiled website will be located in the `./dist/` folder.

---

## 🏗️ Project Structure

The codebase is organized as follows:

```
/
├── public/           # Static assets like images and favicons
├── src/
│   ├── components/   # Reusable UI components (Hero, Navigation, Pricing, etc.)
│   ├── layouts/      # Base layouts wrapping the application
│   ├── pages/        # Astro pages (index.astro is the main entry point)
│   └── styles/       # Global CSS (global.css containing Tailwind directives)
└── package.json      # Project dependencies and scripts
```

## 🌐 Deployment

This site is optimized to be deployed as a static site to **Cloudflare Pages**. 

### Deploy via GitHub (Recommended)
1. Push this repository to GitHub.
2. In your Cloudflare Dashboard, create a new Pages project and connect your GitHub repository.
3. Use the following build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Cloudflare will automatically build and deploy your site on every push!

### Deploy via CLI
You can also deploy directly from your terminal using Wrangler:
```bash
npm run build
npx wrangler pages deploy dist
```

---

## 📧 Contact
For support or inquiries, please contact [buzzandbee25@gmail.com](mailto:buzzandbee25@gmail.com).
