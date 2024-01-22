---
sidebar_position: 3
summary: |-
  Docusaurus 会为每个博客文章创建一个页面，同时也会创建一个博客索引页面、标签系统和 RSS 源。

  要创建第一个博客文章，需要在 `blog/2021-02-28-greetings.md` 中创建一个文件。

  然后，就可以在 `http://localhost:3000/blog/greetings` 中看到新创建的博客文章。
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
