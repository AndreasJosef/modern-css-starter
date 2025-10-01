# Modern CSS Starter

A minimal **content-first landing page starter** built with modern CSS.  

This project is meant as a professional baseline for learning, prototyping, or shipping lightweight pages without heavy frameworks.


## Quick start

The easiest way to start a new project from this template is with [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit AndreasJosef/modern-css-starter my-new-project
cd my-new-project
npm install
npm run dev
````

This will copy the latest version of **Modern CSS Starter** into `my-new-project` without including the Git history.


## Features

* **Content-first workflow** — start with semantic HTML, design emerges from content
* **Cascade layers** — predictable overrides (`tokens`, `base`, `blocks`, `utilities`)
* **Design tokens** — surfaces, ink, brand colors, type scale, spacing, layout knobs
* **Modern CSS** — custom properties, clamp(), grid, flex, container queries ready
* **No frameworks** — artisanal CSS, fully under your control
* **Vite dev server** — fast hot reload, easy to extend later


## Philosophy

The goal is to **learn and practice CSS deeply** while having a solid baseline that already feels professional.
Instead of copying utility classes or fighting a framework, you build directly with tokens and blocks.
Design emerges from content, not the other way around.


## Project structure

```
modern-css-starter/
├── index.html        # semantic content structure
├── vite.config.js    # dev server setup
├── package.json
└── src/
    └── styles/
        ├── app.css      # entry point with @layer order + imports
        ├── tokens.css   # design tokens (colors, type, spacing, layout)
        ├── base.css     # resets + accessibility baseline
        └── blocks.css   # block/component styles (BEM)
```


## Getting started manually

Clone this repo:

```bash
git clone https://github.com/AndreasJosef/modern-css-starter.git
cd modern-css-starter
```

Install dependencies:

```bash
npm install
```

Run the dev server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```


## Example workflow

1. Write semantic HTML in `index.html`
2. Add or tweak tokens in `src/styles/tokens.css`
3. Style blocks in `src/styles/blocks.css` (use BEM naming)
4. Adjust spacing, type, and colors via tokens
5. Fine-tune with modifiers and container queries


## License

MIT — free to use and adapt.
