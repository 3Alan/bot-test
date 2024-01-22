---
sidebar_position: 1
summary: >-
  1. Add Markdown or React files to `src/pages` to create a standalone page.

  2. The page path corresponds to the file name, e.g. `src/pages/foo.md` corresponds to page `localhost:3000/foo`.

  3. You can create either React pages or Markdown pages, React pages are written in JavaScript, whereas Markdown pages are written using
  Markdown syntax.

  4. After creating a new page, you need to run `npm start` or `yarn start` to start the dev server before you can access the new page in the browser.
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