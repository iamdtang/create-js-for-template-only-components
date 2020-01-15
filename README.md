# create-js-for-template-only-components

In order to enable [`template-only-glimmer-components`](https://guides.emberjs.com/release/configuring-ember/optional-features/#toc_template-only-glimmer-components) in an existing application, a `.js` file needs to be created for any existing template-only components. This will maintain backwards compatibility for existing templates while new template-only components gain the advantages of this feature. This script will create those missing `.js` files for you.

Run the following from the root of your project:

```
npx create-js-for-template-only-components .
```

Working with Emblem?

```
TEMPLATE_EXTENSION=".emblem" npx create-js-for-template-only-components
```

This does not work with pods.