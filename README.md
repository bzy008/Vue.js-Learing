# Vue.js-Learing
01:<br>
  a. 开头需要引入<script src="https://cdn.jsdelivr.net/npm/vue"></script><br>
  b. v-model=""：双向绑定<br>
  c. v-show="":可以隐藏信息<br>
  d. 格式
  ```html
    <div id="app">
      {{ message }}
    </div>
  ```
  ```javascript
    var app = new Vue({
    el: '#app',
    data: {
    message: 'Hello Vue!'
    }
  })
  ```
