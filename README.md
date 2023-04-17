# Vue VSCode Snippets

![vue-snippet-hero](https://s3-us-west-2.amazonaws.com/s.cdpn.io/28963/vue-snippet-hero.gif)

## Description

These snippets were built to supercharge a workflow in the most seamless manner possible.

This repo was built particularly for real world use. It doesn't catalogue the API definitions, rather, it focuses on developer ergonomics from the point of Vue of real world use. Included are the pieces I personally get sick of typing, and boilerplate that is helpful to stub out quickly.

_Versions Supported: Vue 2 and Vue 3_

![SnippetDemo](https://s3-us-west-2.amazonaws.com/s.cdpn.io/28963/SnippetDemo.gif)

## Installation

_Either_

- click the extensions button (lowest square icon in the editor), and type in Vue VSCode Snippets, select the one by yogeshgalav

_or_

- go here [vscode Extensions Marketplace](https://marketplace.visualstudio.com/items?itemName=yogeshgalav.vue-section)

```javascript
ext install Vue VSCode Snippets
```

You can enable tab completion (recommended) by opening `Code > Preferences > Settings` (on a Mac) and applying `"editor.tabCompletion": "onlySnippets"` to your personal settings

## Snippets

### Vue

| Snippet            | Purpose                                                      |
| ------------------ | ------------------------------------------------------------ |
| `vsection`            | Single file component base with CSS Scoped                   |
| `vsetup`            | Single file component base with CSS Scoped                   |
| `scriptsetup`            | Single file component base with CSS Scoped                   |
| `vsection-ts`            | Single file component base with CSS Scoped                   |
| `vsection-ts-class`   | Single file component base with Typescript Class Format      |
| `vsection-css`        | Single file component base with CSS                          |
| `vsection-pcss`       | Single file component base with PostCSS                      |
| `vsection-styl`       | Single file component base with Stylus                       |
| `vsection-ts`         | Single file component base with Typescript                   |
| `vsection-ns`         | Single file component with no styles                         |
| `v3section`    | Single File component setup Composition API with SCSS        |
| `v3section-reactive` | Single File component Composition API with Reactive and SCSS |
| `v3section-ts` | Single File component Composition API with Reactive and SCSS |
| `v2section`          | Single File component Composition API with SCSS              |
| `v2section-sass`       | Single file component base with SASS                         |
| `v2section-less`       | Single file component base with LESS                         |
| `v2section-pcss`       | Single file component base with LESS                         |
| `v2section-scss`       | Single file component base with LESS                         |
| `v2section-styl`       | Single file component base with LESS                         |
| `v2section-ts`       | Single file component base with LESS                         |
| `v2section-ns`       | Single file component base with LESS                         |

### Template

| Snippet           | Purpose                             |
| ----------------- | ----------------------------------- |
| `vfor`            | v-for directive                     |
| `vmodel`          | Semantic v-model directive          |
| `vmodel-num`      | Semantic v-model number directive   |
| `von`             | v-on click handler with arguments   |
| `vslot-named`     | Named slot                          |
| `vel-props`       | Component element with props        |
| `vsrc`            | Image src binding                   |
| `vstyle`          | Inline style binding                |
| `vstyle-obj`      | Inline style binding with objects   |
| `vclass`          | Class binding                       |
| `vclass-obj`      | Class binding with objects          |
| `vclass-obj-mult` | Multiple conditional class bindings |
| `vanim`           | Transition component with JS hooks  |
| `vnuxtl`          | Nuxt Routing Link                   |
| `vroutename`      | router-link Named Routing           |
| `vroutenameparam` | router-link Named with Parameters   |
| `vroutepath`      | router-link Path Routing Link       |
| `vemit-child`     | Emit event from child component     |
| `vemit-parent`    | Emit event to parent component      |

### Vue SFC Composition API

| Snippet             | Purpose                                               |
| ------------------- | ----------------------------------------------------- |
| `vprops`          | defineProps with type and default                                        |
| `vemits`          | defineEmits declaration                                                  |
| `reactive`        | Vue Composition API - reactive                        |
| `reactive-setup`  | Vue Composition API - reactive with setup boilerplate |
| `computed`        | Vue Composition API - computed                        |
| `watch`           | Vue Composition API - watcher single source           |
| `watch-array`     | Vue Composition API - watch as array                  |
| `watcheffect`     | Vue Composition API - watchEffect                     |
| `ref`             | Vue Ref                                               |
| `mounted`       | Lifecycle hook - onMounted                            |
| `beforemount`   | Lifecycle hook - onBeforeMount                        |
| `beforeupdate`  | Lifecycle hook - onBeforeUpdate                       |
| `updated`       | Lifecycle hook - onUpdated                            |
| `errorcaptured` | Lifecycle hook - onErrorCaptured                      |
| `unmount`     | Lifecycle hook - (destroyed) onUnmounted              |
| `beforeunmount` | Lifecycle hook - (beforeDestroy) onBeforeUnmount      |
| `useinoptions`    | Use Composition API in Options API                    |

### Vue Optional API

| Snippet           | Purpose                                                                  |
| ----------------- | ------------------------------------------------------------------------ |
| `vdata`           | Component data as a function                                             |
| `vmethod`         | Vue method                                                               |
| `vcomputed`       | Vue computed property                                                    |
| `vwatcher`        | Vue watcher with new and old value args                                  |
| `vbeforecreate`   | beforeCreate lifecycle method                                            |
| `vcreated`        | created lifecycle method                                                 |
| `vbeforemount`    | beforeMount lifecycle method                                             |
| `vmounted`        | vmounted lifecycle method                                                |
| `vbeforeupdate`   | beforeUpdate lifecycle method                                            |
| `vupdated`        | updated lifecycle method                                                 |
| `vbeforedestroy`  | beforeDestroy lifecycle method                                           |
| `vdestroyed`      | destroyed lifecycle method                                               |
| `v2props`         | Props with type and default                                              |
| `vimport`         | Import one component into another                                        |
| `vimport-dynamic` | Import one component that should be lazy loaded by webpack               |
| `vcomponents`     | Import one component into another within the export statement            |
| `vimport-export`  | Import one component into another and use it within the export statement |
| `vmapstate`       | import mapState from Vuex into vue component component                   |
| `vmapgetters`     | import mapGetters from Vuex into vue component component                 |
| `vmapmutations`   | import mapMutations from Vuex into vue component component               |
| `vmapactions`     | import mapActions from Vuex into vue component component                 |
| `vfilter`         | Vue filter                                                               |
| `vmixin`          | Create a Vue Mixin                                                       |
| `vmixin-use`      | Bring a mixin into a component to use                                    |
| `vc-direct`       | Vue create a custom directive                                            |
| `vimport-lib`     | Import a library                                                         |
| `vimport-gsap`    | Import GreenSock                                                         |
| `vanimhook-js`    | Using the Transition component JS hooks in methods                       |
| `vcommit`         | Commit to Vuex store in methods for mutation                             |
| `vdispatch`       | Dispatch to Vuex store in methods for action                             |
| `vtest`           | A simple unit testing component                                          |


### Vuex

| Snippet         | Purpose                        |
| --------------- | ------------------------------ |
| `vstore`        | Base for Vuex store.js         |
| `vgetter`       | Vuex Getter                    |
| `vmutation`     | Vuex Mutation                  |
| `vaction`       | Vuex Action                    |
| `vmodule`       | Vuex Module                    |
| `vstore-import` | Import vuex store into main.js |
| `vstore2`       | Updated Base for Vuex store    |

### Vue Router

| Snippet              | Purpose                                       |
| -------------------- | --------------------------------------------- |
| `vrouter`            | Vue Router base                               |
| `vscrollbehavior`    | Vue Router scrollBehavior                     |
| `vbeforeeach`        | Vue Router global guards beforeEach           |
| `vbeforeresolve`     | Vue Router global guards beforeResolve        |
| `vaftereach`         | Vue Router global guards afterEach            |
| `vbeforeenter`       | Vue Router per-route guard beforeEnter        |
| `vbeforerouteenter`  | Vue Router component guards beforeRouteEnter  |
| `vbeforerouteupdate` | Vue Router component guards beforeRouteUpdate |
| `vbeforerouteleave`  | Vue Router component guards beforeRouteLeave  |

### Vue Config

| Snippet   | Purpose                                                              |
| --------- | -------------------------------------------------------------------- |
| `vplugin` | Import a plugin to main.js or plugins file                           |
| `vconfig` | vue.config.js file, example imports a sass file into every component |

### Nuxt Config

| Snippet | Purpose                                                 |
| ------- | ------------------------------------------------------- |
| `nfont` | link to include fonts in a nuxt project, in nuxt-config |
| `ncss`  | link to css assets such as normalize                    |

### Nuxt Page

| Snippet           | Purpose                          |
| ----------------- | -------------------------------- |
| `nasyncdata`      | Nuxt asyncData                   |
| `nasyncdataaxios` | Nuxt asyncData with Axios module |
| `nfetch`          | Nuxt Fetch                       |
| `nfetchaxios`     | Nuxt Fetch with Axios module     |
| `nhead`           | Nuxt Head                        |
| `nparam`          | Nuxt Route Params                |

### Extra (plaintext)

| Snippet     | Purpose                 |
| ----------- | ----------------------- |
| `gitignore` | .gitignore file presets |

## Contributing

This is an open source project open to anyone. Contributions are welcome [github](https://github.com/yogeshgalav/vue-section)

If you are contributing a snippet, please be sure to add the documentation for it in the tables in the README, the pull request cannot be accepted without this addition. Thanks!
