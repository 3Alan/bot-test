---
sidebar_position: 5
summary: >-
  Docusaurus 是一个静态网站生成器，它将你的网站构建成简单的 HTML、JavaScript 和 CSS 文件。你可以通过运行 `npm run
  build` 命令构建你的网站，输出的静态文件将存储在 `build` 文件夹中。你可以使用 `npm run serve`
  命令在本地测试你的生产版本。你还可以使用免费或低成本的方式将 `build` 文件夹部署到几乎任何地方。
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
