---
sidebar_position: 3
summary: |-
  Docusaurus 为每个博客文章创建一个页面，还创建了一个博客索引页面、一个标签系统、一个 RSS 源等。

  要创建第一个博客文章，只需在 `blog/2021-02-28-greetings.md` 中创建一个文件，其中包含标题、作者、标签等信息。

  保存文件后，就可以在 `http://localhost:3000/blog/greetings` 中看到新创建的博客文章了。

  Docusaurus 会自动生成博客索引页面，其中列出了所有博客文章，并按时间顺序排列。

  博客文章还可以按标签进行分类，在博客索引页面中，可以点击标签来查看所有属于该标签的博客文章。
---

# Create a Blog Post

Docusaurus creates a **page for each blog post**, but also a **blog index page**, a **tag system**, an **RSS** feed...

## Create your first Post1

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
