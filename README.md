# Shopify Slate Tools

Shopify's defunct Slate tools occasionally updated w/ some security patches

### For Existing Slate projects

Replace the following dependency:

```json
{
  "devDependencies": {
    "@shopify/slate-tools": "1.0.0-beta.19"
  }
}
```

With:

```json
{
  "devDependencies": {
    "@five23/slate-tools": "https://github.com/five23/slate-tools"
  }
}
```

### With NPM

```bash
npm install https://github.com/five23/slate-tools --save-dev
```

### With Yarn

```bash
yarn add --dev https://github.com/five23/slate-tools
```
