---
sidebar_position: 1
summary: >-
  1. 下载并安装 Node.js 18.0 或更高版本。

  2. 通过 `npm init docusaurus@latest my-website classic` 命令生成一个新的 Docusaurus
  站点，该命令会自动将经典模板添加到你的项目中。

  3. 通过 `cd my-website` 和 `npm run start` 命令启动你的站点，该命令会构建你的网站并在本地运行一个开发服务器，以便你在
  http://localhost:3000/ 查看。

  4. 编辑 `docs/intro.md` 页面，站点会自动重新加载并显示你的更改。
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
