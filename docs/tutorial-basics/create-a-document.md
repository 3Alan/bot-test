---
sidebar_position: 2
summary: |-
  文档是由页面组成的，页面之间可以通过侧边栏、上一个/下一个导航和版本连接起来。


  可以创建一个 Markdown 文件 `docs/hello.md`，然后在 `sidebars.js` 中明确创建侧边栏。

  侧边栏可以通过 `sidebar_label` 和 `sidebar_position` 来自定义标签和位置。

  也可以在 `sidebars.js` 中创建侧边栏。
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
