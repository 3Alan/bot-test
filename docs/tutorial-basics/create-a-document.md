---
sidebar_position: 2
summary: >-
  文档是一组页面，通过侧边栏、前/后页导航和版本控制相连。在 docs/hello.md 中创建一个Markdown文件，就会在
  http://localhost:3000/docs/hello 上生成一个新的文档。Docusaurus 根据 docs
  文件夹创建一个侧边栏，可以添加元数据来自定义侧边栏标签和位置。也可以在 sidebars.js
  中显式创建侧边栏，将项目添加到预定义的侧边栏或自定义你的侧边栏。
---

# Create a Document

Documents are **groups of pages** connected through:

- a **sidebar**
- **previous/next navigation**
- **versioning**

## Create your first Doc

Create a Markdown file at `docs/hello.md`:

```md title="docs/hello.md"
# Hello

This is my **first Docusaurus document**!
```

A new document is now available at [http://localhost:3000/docs/hello](http://localhost:3000/docs/hello).

## Configure the Sidebar

Docusaurus automatically **creates a sidebar** from the `docs` folder.

Add metadata to customize the sidebar label and position:

```md title="docs/hello.md" {1-4}
---
sidebar_label: 'Hi!'
sidebar_position: 3
---

# Hello

This is my **first Docusaurus document**!
```

It is also possible to create your sidebar explicitly in `sidebars.js`:

```js title="sidebars.js"
export default {
  tutorialSidebar: [
    'intro',
    // highlight-next-line
    'hello',
    {
      type: 'category',
      label: 'Tutorial',
      items: ['tutorial-basics/create-a-document'],
    },
  ],
};
```
