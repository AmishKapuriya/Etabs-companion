# ETABS Structural Design Companion

A premium pair of client-side web application dashboards designed to streamline modelling workflows, cross-reference Indian Standard (IS) code clauses, and track structural member optimization logs for ETABS.

Built with rich CSS styling, tactile animations, responsive circular progress indicators, and local browser persistence.

---

## 🛠️ Included Editions

1. **[ETABS Design Cockpit](etabs-design-cockpit.html)**:
    - A high-density, cockpit theme optimized for rapid engineering workflows.
2. **[ETABS Bento Dashboard](etabs-bento-dashboard.html)**:
    - A modern bento-style dashboard using clean card layouts and neon gradients.

---

## 🚀 Core Features

- **Multi-Project Hub**: Create, rename, save, and switch between multiple projects. Your project data is persisted automatically in your browser's local storage database.
- **Offline Backup & Restoration**: Export project state into a `.json` backup file or import existing project files.
- **Project Parameter Dashboard**: Set geotechnical factors (SBC, soil classification), seismic values ($Z, I, R$), and flat slab toggles.
- **Smart Story & Height Manager**:
    - Allows negative story heights (basements/sub-structure).
    - Checkbox controls to select superstructure levels to calculate Tx/Ty empirical periods accurately.
    - Quick-add interface to bulk insert $N$ number of stories at identical heights.
    - Live edit names/heights of previously added floors.
- **DCR & Member Optimization Log**: Log size/grade revisions and reinforcement ratios. Export your optimization logs directly to a clean `.csv` spreadsheet file.
- **IS Code Reference Guide**: Look up design rules from IS 456:2000, IS 1893:2016, and IS 13920:2016. Includes a dynamic Concrete Modulus ($E_c$) calculator.
- **Progress Tracking Ring**: Clean radial circular progress indicators showing workflow completion percentage in real time.

---

## 💻 How to Run Locally

Both dashboards are completely self-contained and run 100% offline. No node modules, servers, or installations required.
- Double-click **[etabs-design-cockpit.html](etabs-design-cockpit.html)** or **[etabs-bento-dashboard.html](etabs-bento-dashboard.html)** to launch them directly in Chrome, Edge, Safari, or Firefox.

---

## 🌐 Deploying to GitHub Pages (Free Hosting)

You can host these files online for free using GitHub Pages so you can access them from any computer or mobile device:

1. Create a repository on GitHub (e.g. named `etabs-companion`).
2. Push your files to the repository.
3. On GitHub, navigate to **Settings** > **Pages** (under the Code and automation section).
4. Under **Build and deployment**, set the source to **Deploy from a branch**.
5. Select the **main** branch and `/ (root)` folder, then click **Save**.
6. GitHub will generate a URL (e.g. `https://yourusername.github.io/etabs-companion/etabs-bento-dashboard.html`) to access your dashboard from anywhere!
