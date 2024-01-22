---
sidebar_position: 5
summary: >-
  Docusaurus is a static site generator that builds your site into plain HTML, JavaScript, and CSS files. You can build your site by running `npm run build` , and the output static files will be stored in the `build` folder. You can test your production build locally by running `npm run serve` . You can also deploy the `build` folder almost anywhere for free or at a low cost.
---

# Deploy your site

Docusaurus is a **static-site-generator** (also called **[Jamstack](https://jamstack.org/)**).

It builds your site as plain **static HTML, JavaScript and CSS files**.

## Build your site

Build your site **for production**:

```bash
npm run build
```

The static files are generated in the `build` folder.

## Deploy your site

Test your production build locally:

```bash
npm run serve
```

The `build` folder is now served at [http://localhost:3000/](http://localhost:3000/).

You can now deploy the `build` folder **almost anywhere** easily, **for free** or very small cost (read the **[Deployment Guide](https://docusaurus.io/docs/deployment)**).