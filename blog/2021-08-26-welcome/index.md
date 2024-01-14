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
  Docusaurus 博客功能是内置的，只需在 blog 目录下添加 Markdown 文件或文件夹即可。 博客作者可以添加到 authors.yml 中。
  博客文章的日期可以从文件名中提取，例如 2019-05-30-welcome.md。
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
