# Picaroni

Picaroni is a foundation that cares about penguins. Its mission is to protect penguins and the ocean ecosystems they depend on, through habitat protection, research, rescue, and public awareness.

## Live Website

**URL:** [https://picaroni-riwi.github.io/penguin-foundation/](https://picaroni-riwi.github.io/penguin-foundation/)

## Project Idea

The website gives the foundation a simple, clear place online where people can learn about penguins, understand the foundation's work, support it with a donation, and see the organizations that partner with it.

## Pages

- **Landing (`index.html`):** The first impression. It presents the foundation with a hero section, statistics about its work, penguin pictures, a call to donate, and a preview of partners.
- **Donate (`donate.html`):** Explains how donations help penguins and lets visitors give.
- **About Us (`about.html`):** The common information about the foundation: mission, history, and team. The "Who We Are" link in the navigation goes here.
- **Partners (`partners.html`):** Lists the partner organizations and explains how to become one.

The navigation bar on every page links to these pages, and the Donate button is always visible.

## Main Features

- A landing page that introduces the foundation and invites visitors to act
- Statistics about the foundation's impact
- A penguin photo gallery
- Donation page for supporting the foundation
- Partner listing
- Information page about the foundation

## Design Tokens & Color Decision

To resolve discrepancies between early prose and mockup specs, the official design tokens selected for the project follow the **Stitch tokens**:

- **Primary Color:** `#000000` (Deep Black)
- **Secondary Color:** `#fdc425` (Stitch Yellow)

These are defined in `src/input.css` under `@theme`.

## Technology & Deployment

The site is built with plain HTML and Tailwind CSS v4, compiled via the Tailwind CLI, so it can be opened in any browser and published on GitHub Pages without extra tools.

- **Hosting:** Published from the `main` branch to GitHub Pages, with a preview available for each pull request (PR).

## Getting Started

### Requirements

- [Node.js](https://nodejs.org/) (LTS version)
- Git

### 1. Clone the repository

```bash
git clone https://github.com/picaroni-riwi/penguin-foundation.git
cd penguin-foundation
```

### 2. Install dependencies

```bash
npm install
```

This installs Tailwind CSS v4 and its CLI, listed in `package.json`.

### 3. Build the CSS while you work

```bash
npm run dev
```

This runs the Tailwind CLI in watch mode. It reads `src/input.css`, scans the HTML files, and writes `dist/output.css` every time you save. Keep this terminal open while you work.

If you prefer the command directly, it is:

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./dist/output.css --watch
```

### 4. Open the site

Open `index.html` in your browser. Refresh the page after each save if the styles do not update.

## Scripts

| Command | What it does |
|---------|--------------|
| `npm install` | Installs dependencies |
| `npm run dev` | Rebuilds `dist/output.css` on every change |

## Contributing

Before you start, read the team rules in [penguin-foundation-docs](https://github.com/picaroni-riwi/penguin-foundation-docs).

- All work is in **English**.
- Every change goes through a **Pull Request**.
- **The project lead (carrenoA) approves every PR.** Wait for approval before continuing.