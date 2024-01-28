---
ai_translation: true
---
```markdown
---
sidebar_position: 1
summary: >-
  Docusaurus is a static website generator used to build documentation websites. It utilizes React and Markdown, supports themes, internationalization, search, plugins, and offline support. You can generate a new Docusaurus website via the command line and then launch a development server to preview your site locally. When you edit the `docs/intro.md` file, the website will automatically reload and display your changes.

# Tutorial Intro

Let's explore **Docusaurus in less than 5 minutes**.

## Getting Started

Begin by **creating a new site**.

Alternatively, **try Docusaurus immediately** with **[docusaurus.new](https://docusaurus.new)**.

### What you'll need

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:11
  - When installing Node.js, it's recommended to check all checkboxes related to dependencies.

## Generate a new site

Generate a new Docusaurus site using the **classic template**.

The classic template is automatically added to your project after running the command:

```bash
npm init docusaurus@latest my-website classic
```

You can enter this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command also installs all necessary dependencies needed to run Docusaurus.

## Start your site

Run the development server:

```bash
cd my-website
npm run start
```

The `cd` command changes the directory in which you're working. To work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes.
```
