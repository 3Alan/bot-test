---
sidebar_position: 1
summary: |-
  - Docusaurus 可以管理您的文档的多个版本。
  - 创建一个新的文档版本：```npm run docusaurus docs:version 1.0```
  - 在导航栏中添加一个版本下拉列表，以便在版本之间无缝导航。
  -可以在各自的文件夹中编辑已发布的文档：

  `versioned_docs/version-1.0/hello.md` 更新 `http://localhost:3000/docs/hello`，
  `docs/hello.md` 更新 `http://localhost:3000/docs/next/hello`。
---

# Manage Docs Versions

Docusaurus can manage multiple versions of your docs.

## Create a docs version

Release a version 1.0 of your project:

```bash
npm run docusaurus docs:version 1.0
```

The `docs` folder is copied into `versioned_docs/version-1.0` and `versions.json` is created.

Your docs now have 2 versions:

- `1.0` at `http://localhost:3000/docs/` for the version 1.0 docs
- `current` at `http://localhost:3000/docs/next/` for the **upcoming, unreleased docs**

## Add a Version Dropdown

To navigate seamlessly across versions, add a version dropdown.

Modify the `docusaurus.config.js` file:

```js title="docusaurus.config.js"
export default {
  themeConfig: {
    navbar: {
      items: [
        // highlight-start
        {
          type: 'docsVersionDropdown',
        },
        // highlight-end
      ],
    },
  },
};
```

The docs version dropdown appears in your navbar:

![Docs Version Dropdown](./img/docsVersionDropdown.png)

## Update an existing version

It is possible to edit versioned docs in their respective folder:

- `versioned_docs/version-1.0/hello.md` updates `http://localhost:3000/docs/hello`
- `docs/hello.md` updates `http://localhost:3000/docs/next/hello`
