---
sidebar_position: 1
summary: >-
  1. 在 `src/pages` 目录下添加 Markdown 或 React 文件，即可创建独立页面。

  2. 页面路径与文件名相对应，例如 `src/pages/foo.md` 对应页面 `localhost:3000/foo`。

  3. 可以创建 React 页面或 Markdown 页面，React 页面使用 JavaScript 编写，而 Markdown 页面使用
  Markdown 语法编写。

  4. 创建新页面后，需要运行 `npm start` 或 `yarn start` 来启动开发服务器，然后才能在浏览器中访问新页面。

  5. 新页面将在 `localhost:3000` 下可用。
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
