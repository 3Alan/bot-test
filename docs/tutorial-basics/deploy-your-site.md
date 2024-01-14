---
sidebar_position: 5
summary: >-
  Docusaurus 是一个静态网站生成器，它将你的网站构建为简单的静态 HTML、JavaScript 和 CSS 文件。你可以通过运行 `npm run
  build` 构建你的网站，并将静态文件生成在 `build` 文件夹中。你可以通过运行 `npm run serve` 测试你的生产构建。你可以将
  `build` 文件夹部署到任何地方，几乎免费或非常小的成本。
---

# Deploy your site

Docusaurus is a **static-site-generator** (also called **[Jamstack](https://jamstack.org/)**).

It builds your site as simple **static HTML, JavaScript and CSS files**.

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
