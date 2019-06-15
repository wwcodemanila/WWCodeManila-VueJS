# What is Vue?

![Vue](../_media/vue.png)

**Vue** (pronounced /vjuː/, like view) is an open-source JavaScript framework for building user interfaces and single-page applications. You can learn more about Vue from their [official site](https://vuejs.org/).

## Why Vue?

#### Approachable

Already know HTML, CSS and JavaScript? Then you are ready to start building things in no time!

#### Versatile
An incrementally adoptable ecosystem that scales between a library and a full-featured framework.

#### Performant
Small file size of only 20KB minified and zipped. Blazing fast virtual DOM and minimal optimization efforts.

!> To start using Vue JS, it is assumed that you have an intermediate level knowledge of HTML, CSS, and JavaScript. If you are totally new to frontend development, it might not be the best idea to jump right into a framework as your first step - grasp the basics then come back!

## Let's get started!

The easiest way to try out Vue.js is by creating an `index.html` file and including Vue in the head tag:

``` html
<!-- development version, includes helpful console warnings -->
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
```

or:

``` html
<!-- production version, optimized for size and speed -->
<script src="https://cdn.jsdelivr.net/npm/vue"></script>
```

With Vue's straightforward template syntax, it enables us to declaratively render data to the DOM:

``` html
<div id="app">
  {{ message }}
</div>
```
``` js
var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue!'
  }
})
```

---
### Hello Vue!

---