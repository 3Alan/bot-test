---
ai_translation: true
---
```markdown
---
sidebar_position: 2
summary: >-
  - Document Translation: Copy the `docs/intro.md` file to the `i18n/fr` folder and translate its content.

  - Start Localized Site: Use the command `npm run start -- --locale fr` to start the localized site.

  - Add Language Dropdown: In the `docusaurus.config.js` file, add `{ type: 'localeDropdown' }` to `navbar.items`.

  - Build Localized Site: Use the command `npm run build -- --locale fr` to build the site for a specific language, or use `npm run build` to build the site for all languages.
---

# Translate your site

Let's translate the `docs/intro.md` to French.

## Configure i18n

Modify the `docusaurus.config.js` to add support for the `fr` locale:

```js title="docusaurus.config.js"
export default {
  i18n: {
    defaultLocale: 'en',
    locales: ['en', 'fr'],
  },
};
```

## Translate a doc

Copy the `docs/intro.md` file to the `i18n/fr` folder:

```bash
mkdir -p i18n/fr/docusaurus-plugin-content-docs/current/

cp docs/intro.md i18n/fr/docusaurus-plugin-content-docs/current/intro.md
```

Translate `i18n/fr/docusaurus-plugin-content-docs/current/intro.md` into French.

## Start your localized site

Start your site with the French locale:

```bash
npm run start -- --locale fr
```

Your localized site is accessible at [http://localhost:3000/fr/](http://localhost:3000/fr/) and the `Getting Started` page is translated.

:::caution

In development, you can only use one locale at a time.

:::

## Add a Locale Dropdown

To navigate seamlessly across languages, add a locale dropdown.

Modify the `docusaurus.config.js` file:

```js title="docusaurus.config.js"
export default {
  themeConfig: {
    navbar: {
      items: [
        // highlight-start
        {
          type: 'localeDropdown',
        },
        // highlight-end
      ],
    },
  },
};
```

The locale dropdown now appears in your navbar:

![Locale Dropdown](./img/localeDropdown.png)

## Build your localized site

Build your site for a specific locale:

```bash
npm run build -- --locale fr
```

Or build your site to include all the locales at once:

```bash
npm run build
```
```
