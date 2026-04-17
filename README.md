# Grish Pradhan — Portfolio Website

A personal cybersecurity portfolio website built with plain HTML, CSS, and JavaScript. No build step or dependencies required.

## 🚀 Hosting Options

### Option 1: GitHub Pages (Recommended)

This repository is already named in the `<username>.github.io` format, which means GitHub Pages can serve it automatically for free.

**Steps:**

1. **Fork or push this repo** to your GitHub account, naming it `<your-username>.github.io`  
   *(e.g. `johndoe.github.io`)*

2. Go to your repository on GitHub and open **Settings → Pages**.

3. Under **"Build and deployment"**, set:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` (or `master`), folder `/` (root)

4. Click **Save**. GitHub will build and deploy the site within a few minutes.

5. Your site will be live at `https://<your-username>.github.io`

> **Note:** If you are using this repository as-is (not a user pages repo), set the Source branch to whichever branch contains `index.html` and the path to `/` (root).

---

### Option 2: Netlify

1. Create a free account at [netlify.com](https://www.netlify.com).
2. Click **"Add new site" → "Import an existing project"** and connect your GitHub account.
3. Select this repository.
4. Leave **Build command** and **Publish directory** blank (static site, no build step needed).
5. Click **"Deploy site"**.

Your site will be live on a `*.netlify.app` subdomain. You can attach a custom domain from the Netlify dashboard.

---

### Option 3: Vercel

1. Create a free account at [vercel.com](https://vercel.com).
2. Click **"Add New… → Project"** and import this repository from GitHub.
3. Vercel will auto-detect that it is a static site — no settings need to change.
4. Click **"Deploy"**.

Your site will be live on a `*.vercel.app` subdomain. Custom domains can be added in the project settings.

---

### Option 4: Run Locally

To preview the site on your own machine without any internet connection:

**Using Python (built-in, no install needed):**

```bash
# Python 3
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

**Using Node.js (`npx`):**

```bash
npx serve .
```

Then open the URL shown in your terminal (usually `http://localhost:3000`).

---

## 📁 File Structure

```
.
├── index.html      # Main portfolio page
├── admin.html      # Admin / dashboard page
├── images/         # Certification and profile images
└── badges/         # Badge images
```

## ✏️ Customization

All content lives in `index.html`. Open it in any text editor and update:

- **Name / tagline** — search for `Grish Pradhan`
- **Social links** — search for `href="https://github.com/` and `linkedin.com`
- **Skills & certifications** — update the relevant sections in the HTML
- **Colour scheme** — edit the CSS custom properties at the top of the `<style>` block inside `index.html`

No build tools or package managers are required — save the file and refresh your browser.
