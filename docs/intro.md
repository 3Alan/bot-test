---
sidebar_position: 1
summary: |-
  1. 使用命令 “npm init docusaurus@latest my-website classic” 创建一个新的 Docusaurus 网站。
  2.使用“cd my-website”和“npm run start”命令启动开发服务器，以在本地构建并运行您的网站。
  3. 打开 “docs/intro.md” 并编辑一些行，网站将自动重新加载并显示您的更改。
  4. Docusaurus 提供了一个经典模板，可以在创建新站点时自动添加，并且需要 Node.js 版本 18.0 或更高版本。
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
