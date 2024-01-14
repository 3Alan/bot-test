---
sidebar_position: 1
summary: >-
  1. 可以在 `src/pages` 目录下创建 Markdown 或 React 文件来创建独立页面。

  2. Markdown 文件名与页面 URL 路径一一对应，例如 `src/pages/foo.md` 对应 `localhost:3000/foo`。

  3. React 文件名与页面 URL 路径也一一对应，例如 `src/pages/foo/bar.js` 对应
  `localhost:3000/foo/bar`。

  4. 创建 Markdown 或 React 页面后，需要在本地运行项目才能访问这些页面。
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
