# create-electron-nuxt-app

> Electron Nuxt app template

Template of Electron Nuxt incorporating security and using IPC Renderer, IPC Main and handlers to compile successfully.

It was developed following the [guide of Electron Builder security](https://nklayman.github.io/vue-cli-plugin-electron-builder/guide/security.html#node-integration) to reduce risks.

## Download template

```
npx degit luvitale/create-electron-nuxt-app electron-nuxt-app
```

## Build Setup

``` bash
# install dependencies
yarn install

# serve app with hot reload
yarn dev

# build electron application for production
yarn build

# yarn tests
yarn test


# lint all JS/Vue component files in `src/`
yarn lint

```

---

This project was generated with [electron-nuxt](https://github.com/michalzaq12/electron-nuxt) v1.7.1 using [vue-cli](https://github.com/vuejs/vue-cli). Documentation about the original structure can be found [here](https://github.com/michalzaq12/electron-nuxt/blob/master/README.md).
