# Vue 3 Fundamentals

### Fundamentals

- v-if & v-show
- Conditional apply style & class
- Reducing duplication with mixins
    - OOP design
- Composition API
- slots
- props validating
- teleport
- provide/inject to supply data to deeply nested component
- add (+) as postfix to convert variable to number
    - id = “1” ⇒ +id = 1 // number

### Vuex

- **state**: Store data model
    - Get: **this.$store.state.xxx**
- **mutations**: Update state data
    - Update: **this.$store.commit(’action’, payload)**
- **getters**: Business logic to retrieve value
    - Get: **this.$store.getters.xxx**
- modules
    - Root scope
    - namespaced
        
        ⇒ Get state by namespace **store.state.namespace.attribute**
        
        ⇒ Call action by namespace **commit(’namespace/action’, payload)**
        
        ⇒ Getters by namespace **store.getters[’namespace/getter’]** 
        
    - mapState / mapGetters / mapActions/ mapMutations

### Directives

### Filters

### Vue styled system

[https://codesandbox.io/s/vue-styledsystem-gl9z8?file=/src/components/Heading.js](https://codesandbox.io/s/vue-styledsystem-gl9z8?file=/src/components/Heading.js)

### Vue Plugins

[https://5balloons.info/create-publish-you-first-vue-plugin-on-npm-the-right-way/](https://5balloons.info/create-publish-you-first-vue-plugin-on-npm-the-right-way/)

[https://docs.npmjs.com/creating-and-publishing-private-packages](https://docs.npmjs.com/creating-and-publishing-private-packages)

[https://gemfury.com/help/npm-registry/#package-json](https://gemfury.com/help/npm-registry/#package-json)

### Best practices

[https://blog.bitsrc.io/4-best-practices-for-large-scale-vue-js-projects-9a533450bdb2](https://blog.bitsrc.io/4-best-practices-for-large-scale-vue-js-projects-9a533450bdb2)

### Sharing reusable component

[https://medium.com/js-dojo/sharing-reusable-vue-js-components-with-lerna-storybook-and-npm-7dc33b38b011](https://medium.com/js-dojo/sharing-reusable-vue-js-components-with-lerna-storybook-and-npm-7dc33b38b011)

### F.I.R.S.T principal

[https://addyosmani.com/](https://addyosmani.com/first/)

### Best practices

[https://www.telerik.com/blogs/10-good-practices-building-maintaining-large-vuejs-projects](https://www.telerik.com/blogs/10-good-practices-building-maintaining-large-vuejs-projects)

### Structure guidelines

[https://vueschool.io/articles/vuejs-tutorials/how-to-structure-a-large-scale-vue-js-application/](https://vueschool.io/articles/vuejs-tutorials/how-to-structure-a-large-scale-vue-js-application/)

### Dynamic component

[https://medium.com/geekculture/dynamic-components-in-vue-3-7504d5ffcb6c](https://medium.com/geekculture/dynamic-components-in-vue-3-7504d5ffcb6c)
