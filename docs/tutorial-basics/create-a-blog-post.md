---
sidebar_position: 3
summary: |-
  Docusaurus 会为每一篇博客文章创建一个页面，同时还会创建一个博客索引页面、一个标签系统、RSS 供稿等。

  要在博客中创建第一篇帖子，需要在 blog/2021-02-28-greetings.md 中创建文件，其中包含文章的标题、作者、标签等信息。

  保存文件后，就能在 http://localhost:3000/blog/greetings 看到新的博客文章。

  同时，Docusaurus 还会为博客自动生成索引页面、标签页面和 RSS 供稿。
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
