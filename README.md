# vsc-vue3-fundamentals-with-composition-api
VueSchools - Vue.js 3 Fundamentals with the Composition API


## Links
- [Vue.js Playground](https://sfc.vuejs.org/)
- [Tips and Gotchas for Using key with v-for in Vue.js 3](https://vueschool.io/articles/vuejs-tutorials/tips-and-gotchas-for-using-key-with-v-for-in-vue-js-3/)
- [Caveat when Unwrapping in Templates](https://vuejs.org/guide/essentials/reactivity-fundamentals.html#caveat-when-unwrapping-in-templates)
- [Declaring Reactive State](https://vuejs.org/guide/essentials/reactivity-fundamentals.html#declaring-reactive-state-1)
- [How Reactivity Works in Vue](https://vuejs.org/guide/extras/reactivity-in-depth.html#how-reactivity-works-in-vue)
- [Project Scaffolding](https://vuejs.org/guide/scaling-up/tooling.html#project-scaffolding)

## Methods

- **v-model** - two way binding
  - ### modifiers
  - .lazy
  - .number
  - .trim

- **v-for** - loop over arrays, objects v-for="({id, label}, index) in items" :key="id"

- **v-on || @** - action v-on:click="" 
  - :click
  - :keyup
    - .enter
  - :submit
    - .prevent

- **v-bind || :** - binds any attribute

### In functions in script section for ref elements need to use .value as it is proxy

Computed is used only to change represatatoing data and should not be used to modufy existing data. For arrays better to spread and do things that motify [playground](https://tinyurl.com/y8nxb3n8)


# .

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Vue (Official)](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Recommended Browser Setup

- Chromium-based browsers (Chrome, Edge, Brave, etc.):
  - [Vue.js devtools](https://chromewebstore.google.com/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)
  - [Turn on Custom Object Formatter in Chrome DevTools](http://bit.ly/object-formatters)
- Firefox:
  - [Vue.js devtools](https://addons.mozilla.org/en-US/firefox/addon/vue-js-devtools/)
  - [Turn on Custom Object Formatter in Firefox DevTools](https://fxdx.dev/firefox-devtools-custom-object-formatters/)

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
