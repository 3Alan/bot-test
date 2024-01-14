---
sidebar_position: 1
summary: |-
  1. 在 `src/pages` 目录下添加 Markdown 或 React 文件，即可创建一个独立页面。
  2. Markdown 文件名即为页面 URL；React 文件导出默认函数并通过 `Layout` 组件布局。
  3. 创建 React 页面时，页面路径为 `http://localhost:3000/页面文件名`；
  4. 创建 Markdown 页面时，页面路径为 `http://localhost:3000/页面文件名`。
---

# Create a Page

Add **Markdown or React** files to `src/pages` to create a **standalone page**:

- `src/pages/index.js` → `localhost:3000/`
- `src/pages/foo.md` → `localhost:3000/foo`
- `src/pages/foo/bar.js` → `localhost:3000/foo/bar`

## Create your first React Page

Create a file at `src/pages/my-react-page.js`:

```jsx title="src/pages/my-react-page.js"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

A new page is now available at [http://localhost:3000/my-react-page](http://localhost:3000/my-react-page).

## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

A new page is now available at [http://localhost:3000/my-markdown-page](http://localhost:3000/my-markdown-page).
