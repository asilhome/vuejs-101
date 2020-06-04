# Vue.js 101
Learn Vue.js gradually starting from basic html up to project scaffolding.

## 101
### 1. Vue Instance
Learn how to turn **html** into a *dynamic* page just using `CDN`.
- debugging tools
- properties (Data), computed, methods & lifecycle
- template syntax, basic javascript (array)
- events
- v-model
- demonstrate add, update, delete, load, search functions

```
Vue()   # root of an application
```

### 2. Vue Components
Learn how to create a simple component.
- register component using x-template
- global & local component
- template, props, emit

```
Vue.component()
```

## 102
Prototyping mode with `local development server`.
```bash
npm install -g @vue/cli
npm install -g @vue/cli-service-global
# or
npm install -g @vue/cli @vue/cli-service-global
```

### 3. Single File Component
Learn to migrate components into separate `vue` files.

```bash
vue serve
```

## 103
Project mode with full tooling.

### 4. Project Scaffolding
```bash
vue create <project>
```

## References
[Vue.js](https://vuejs.org/), [Vue API](https://vuejs.org/v2/api/), [Vue CLI](https://cli.vuejs.org/guide/)