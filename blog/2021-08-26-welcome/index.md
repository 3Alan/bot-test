---
slug: welcome
title: Welcome
authors:
  - slorber
  - yangshun
tags:
  - facebook
  - hello
  - docusaurus
summary: >-
  Docusaurus 的博客功能由博客插件提供支持，只需将 Markdown 文件添加到 `blog` 目录即可。博客文章的日期可以从文件名中提取，如
  `2019-05-30-welcome.md`。博客文章文件夹便于共同定位博客文章图片。博客也支持标签。如果您不想要博客，只需删除此目录，并在
  Docusaurus 配置中使用 `blog: false` 即可。
---

[Docusaurus blogging features](https://docusaurus.io/docs/blog) are powered by the [blog plugin](https://docusaurus.io/docs/api/plugins/@docusaurus/plugin-content-blog).

Simply add Markdown files (or folders) to the `blog` directory.

Regular blog authors can be added to `authors.yml`.

The blog post date can be extracted from filenames, such as:

- `2019-05-30-welcome.md`
- `2019-05-30-welcome/index.md`

A blog post folder can be convenient to co-locate blog post images:

![Docusaurus Plushie](./docusaurus-plushie-banner.jpeg)

The blog supports tags as well!

**And if you don't want a blog**: just delete this directory, and use `blog: false` in your Docusaurus config.
