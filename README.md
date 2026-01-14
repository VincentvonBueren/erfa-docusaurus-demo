# 📘 ipt Documentation

This is the **internal documentation site for ipt**, built to explore and test [Docusaurus](https://docusaurus.io/).  
It serves as a sandbox for experimenting with documentation structure, theming, and developer onboarding.

---

## 🚀 Quick Start

### 1. Install Dependencies

```bash
npm install
```

> Requires **Node.js ≥ 18**.

### 2. Start Local Development

```bash
npm run start
```

This starts the site locally at [http://localhost:3000](http://localhost:3000).

⚠️ **Heads up**: Full-text search does **not work** in development mode.
To test search, you’ll need to build the production site and serve it (see below).

---

## 📦 Build and Serve Production

```bash
npm run build
npx serve build
```

This will generate the static site in the `build/` directory and start a local production server.
✅ **Search will work** in this mode.

---

## ⚙️ Using with Devbox

If you use [Devbox](https://www.jetpack.io/devbox/) to set up the environment:

```bash
devbox shell
npm install
```

Then you can run:

```bash
npm run start     # Local dev server (no search)
npm run build     # Production build
npx serve build   # Serve production site with working search
```

To leave the Devbox shell:

```bash
exit
```

## 💬 Community & Resources

Looking for help or inspiration?
Join the [Docusaurus Discord](https://discord.gg/docusaurus), browse the [community showcase](https://docusaurus.io/showcase), or check out the [official documentation](https://docusaurus.io/docs/).

---

🛠️ Built with ❤️ by ipt engineers.
