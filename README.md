# vue2-highlightjs
I created this as other versions are not compatible or broke and wanted minimalist package size.

## Quickstart

### Installation

Simply install the [npm package `vue-highlightjs`](https://www.npmjs.com/package/vue-highlightjs):

    npm install --save vue-highlightjs

### Using vue-highlightjs

In your main JavaScript file (eg. `main.js`):

```javascript
// Import Vue and vue-highlgihtjs
import Vue from 'vue'
import VueHighlightJS from 'vue-highlightjs'
import 'highlight.js/styles/default.css' // or other highlight.js theme

// Tell Vue.js to use vue-highlightjs
Vue.use(VueHighlightJS)
```

In your template, in order to highlight javascript code:

```html
<!-- If your source-code lives in a variable called 'sourcecode' -->
<pre v-highlightjs="sourcecode"><code class="javascript"></code></pre>

<!-- If you want to highlight hardcoded source-code -->
<pre v-highlightjs><code class="javascript">const s = new Date().toString()</code></pre>
```
---
