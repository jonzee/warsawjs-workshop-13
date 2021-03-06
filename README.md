# warsawjs-workshop-13
Quiz game prepared for #VueJS workshops

## Config
```
# run app in developer mode
cd quiz
npm i && npm run dev

# publish app at your_username.github.io/warsawjs-workshop-13-quiz
cd quiz
npm run publish
```

## Plan
**`single-file` - single file app**
* [x] question card
* [x] question list
* [x] progress bar (semantic-ui component)

**`modules` - vue-cli**
* [x] `vue init webpack quiz`
* [x] `npm install semantic-ui-vue --save`
* [x] `npm install semantic-ui-css --save`
* [x] npm & webpack
* [x] split to modules

**`routing` - vue router**
* [x] `npm install vue-router --save`
* [x] outer layout
* [x] routes: intro, game, settings

**`network` - fetching questions**
* [x] `npm install axios --save`
* [x] loading indicator

**`vuex-store` - adding vuex to app**
* [x] `npm install vuex --save`
* [x] added settings with simple vuex example
* [x] move all data logic to store

## Vue.js features
**Template syntax**
* [x] `{{ msg }}` - interpolation
* [x] `v-bind`, `:` - one way binding
* [x] `v-model` - two-way (inputs etc.)
* [x] `v-html` - parse html
* [x] `v-if, v-else`, `v-show` - conditionals
* [x] `v-for` - render in loop
* [x] `v-on`, `@` - events
* [x] `v-once` - render once
* [x] `v-cloak` - blank page before render

**Components**
* [x] data
* [x] props
* [x] methods
* [x] computed
* [x] lifecycle
* [x] $on(eventName)
* [x] $emit(eventName)
* [x] nested components

**Router**
* [x] router-view
* [x] router-link
* [x] $router.push('/')
* [x] nested routes

**Vuex**
* [x] state
* [x] actions (dispatch)
* [x] getters
* [x] mutations (commit)

## Other
**Tools**
* [x] vue-cli
* [x] vue dev-tools
* [x] npm & webpack

**Credits**
* [yes/no API](https://yesno.wtf) - API with yes/no gif's :)
* [OpentDB](https://opentdb.com/api.php?amount=5&type=boolean) - API with questions
* [Semantic UI](https://semantic-ui-vue.github.io/) - libs with styles & vue components
* [Milionare Quiz](https://github.com/Valian/warsawjs-workshop-12-quiz) - repo from previus workshop
