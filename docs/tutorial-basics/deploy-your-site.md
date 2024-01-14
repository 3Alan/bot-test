---
sidebar_position: 5
summary: >-
  Docusaurus是一个静态站点生成器，它将您的网站构建为简单的静态HTML、JavaScript和CSS文件。您可以使用`npm run
  build`命令构建您的站点，生成的静态文件将存储在`build`文件夹中。您可以使用`npm run
  serve`命令在本地测试您的生产构建，`build`文件夹将被提供在[http://localhost:3000/](http://localhost:3000/)。您可以将`build`文件夹部署到几乎任何地方，并且几乎免费或非常低的成本。
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
