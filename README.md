EDIT: Don't use me, I'm abandoned!

Check out some of these other Slate forks instead ->

* https://github.com/hayes0724/shopify-packer
* https://github.com/entozoon/slatest
* https://github.com/CocoaWebStudio/slate
* https://github.com/hayes0724/shopify-packer
* https://github.com/Process-Creative/Slate
* https://github.com/3daddict/themekit-webpack
* https://github.com/feruzfauzi/shopify-webpack-themekit
* https://github.com/the-couch/slater
* https://github.com/davidwarrington/theme-packer (<-- Webpack v5, docs!)

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
