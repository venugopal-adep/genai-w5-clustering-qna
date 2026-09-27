# Customer Personality Segmentation Dashboard

Interactive 2D & 3D PCA Customer Segmentation Dashboard built with **Chart.js**, **Plotly.js**, and modern Vanilla CSS (Light Theme).

## 🚀 Live Demo on GitHub Pages
Once deployed, this dashboard will be live at:
`https://<your-username>.github.io/<your-repo-name>/`

---

## 📁 Repository Structure
- `index.html`: Main dashboard entry point for GitHub Pages.
- `customer_segmentation_dashboard.html`: Direct naming alias.
- `.nojekyll`: Disables Jekyll build engine so all scripts and assets load instantly without parsing issues.

---

## ⚡ How to Deploy to GitHub Pages (2 Minutes)

### Option A: Creating a New Dedicated Repository
1. Open terminal inside this folder (`github_pages`):
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Customer Segmentation Dashboard"
   ```
2. Create a new repository on GitHub (e.g. `customer-segmentation-dashboard`).
3. Link and push to GitHub:
   ```bash
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git branch -M main
   git push -u origin main
   ```
4. On GitHub, go to:
   **Settings** ➡️ **Pages** ➡️ Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` / `/(root)`
   - Click **Save**.
5. Wait ~30 seconds, and your dashboard will be live!

---

### Option B: Uploading Directly via GitHub Web UI
1. Create a new repository on [github.com/new](https://github.com/new).
2. Click **uploading an existing file**.
3. Drag and drop `index.html`, `customer_segmentation_dashboard.html`, and `.nojekyll` into the browser.
4. Commit changes.
5. In **Settings** ➡️ **Pages**, select branch `main` and root `/`, then click **Save**.

---

## 📊 Features
- **2D PCA Projection:** Dynamic cluster boundaries, centroid markers, and multi-K selection (K=2 to K=6).
- **3D PCA WebGL Space:** Interactive 3D point cloud with orbit controls, camera angle presets, and 360° spin animation.
- **Retail Persona Profiles:** Actionable marketing archetypes with spending baskets and channel habits.
- **Zero Local Dependencies:** 100% self-contained data and HTTPS CDN libraries.
