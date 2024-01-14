---
sidebar_position: 3
summary: >-
  1. Docusaurus 为每个博客文章创建一个页面，还创建了博客索引页面、标签系统和 RSS。

  2. 第一步是创建一个文件并输入一些信息，例如标题、作者、标签等。

  3. 将文件保存到“blog”文件夹中，并确保文件名以“.md”结尾。

  4. 然后，您可以在
  [http://localhost:3000/blog/greetings](http://localhost:3000/blog/greetings)
  查看您的新博客文章。
---

# Create a Blog Post

Docusaurus creates a **page for each blog post**, but also a **blog index page**, a **tag system**, an **RSS** feed...

## Create your first Post

Create a file at `blog/2021-02-28-greetings.md`:

```md title="blog/2021-02-28-greetings.md"
---
slug: greetings
title: Greetings!
authors:
  - name: Joel Marcey
    title: Co-creator of Docusaurus 1
    url: https://github.com/JoelMarcey
    image_url: https://github.com/JoelMarcey.png
  - name: Sébastien Lorber
    title: Docusaurus maintainer
    url: https://sebastienlorber.com
    image_url: https://github.com/slorber.png
tags: [greetings]
---

Congratulations, you have made your first post!

Feel free to play around and edit this post as much you like.
```

A new blog post is now available at [http://localhost:3000/blog/greetings](http://localhost:3000/blog/greetings).
