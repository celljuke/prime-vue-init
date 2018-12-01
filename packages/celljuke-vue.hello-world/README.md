# celljuke-vue.hello-world
> A component that says "HelloA" with orange text.
## Installation
### Directly in the browser
Drop the component in with a `<script>` tag alongside Vue:
```html
<div id="app">
<!-- ... use component here ... -->
</div>
<script src="https://unpkg.com/vue"></script>
<script src="https://unpkg.com/celljuke-vue.hello-world"></script>
<script>
new Vue({ el: '#app' })
</script>
```
### In a module system
Install the component with NPM:
```bash
npm install celljuke-vue.hello-world
```
Then import the component:
```js
import HelloWorld from 'celljuke-vue.hello-world'
```
And either globally register it for use in all components:
```js
Vue.component(HelloWorld, 'celljuke-vue.hello-world')
```
or locally register it for use in an individual component:
```js
export default {
components: { HelloWorld }
}
```
## Usage
```html
<!-- No props or content are necessary. -->
<hello-wolrd></hello-wolrd>
```
