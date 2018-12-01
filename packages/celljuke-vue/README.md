
# celljuke-vue
> An example component library built with Vue CLI 3.
## Installation
### Directly in the browser
Drop the library in with a `<script>` tag alongside Vue:
```html
<div id="app">
<!-- ... use components here ... -->
</div>
<script src="https://unpkg.com/vue"></script>
<script src="https://unpkg.com/celljuke-vue"></script>
<script>
new Vue({ el: '#app' })
</script>
```
Or, if you only want to use a small subset of components, drop them in individually:
```html
<div id="app">
<!-- ... use component here ... -->
</div>
<script src="https://unpkg.com/vue"></script>
<script src="https://unpkg.com/celljuke-vue/HelloA"></script>
<script>
new Vue({ el: '#app' })
</script>
```
### In a module system
Install the library with NPM:
```bash
npm install celljuke-vue
```
Then either import the library and either globally register all components with:
```js
import CelljukeVue from 'celljuke-vue'
Vue.use(CelljukeVue)
```
or import and locally register a single component with:
```js
import { HelloA } from 'celljuke-vue'
export default {
components: { CelljukeVue }
}
```
#### Individually packaged components
If you only want to use a small subset of components, import only individually packaged components to reduce the size of your application:
```js
import HelloA from 'hello-vue-components/HelloA'
import HelloB from 'hello-vue-components/HelloB'
```
