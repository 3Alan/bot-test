---
sidebar_position: 1
summary: >-
  Docusaurus
  是一个现代的静态网站生成器，提供了一个简单却强大的文档站点创作体验。只需5分钟即可创建Docusaurus站点。首先创建一个新站点，或者使用
  docusaurus.new 立即试用 Docusaurus。您需要安装最新版本（18.0 或更高）的 Node.js。然后，使用命令 npm init
  docusaurus@latest my-website classic 生成一个新的经典模板的 Docusaurus 站点。最后，运行 npm run
  start 命令启动您的站点，并在 http://localhost:3000/ 处查看。
---

# Tutorial Intro

Let's discover **Docusaurus in less than 5 minutes**.

## Getting Started

Get started by **creating a new site**.

Or **try Docusaurus immediately** with **[docusaurus.new](https://docusaurus.new)**.

### What you'll need

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.

## Generate a new site

Generate a new Docusaurus site using the **classic template**.

The classic template will automatically be added to your project after you run the command:

```bash
npm init docusaurus@latest my-website classic
```

You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command also installs all necessary dependencies you need to run Docusaurus.

## Start your site

Run the development server:

```bash
cd my-website
npm run start
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes.
