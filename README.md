# Vue.js-Learing
Lesson01:<br>
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
Lesson02:<br>
  a. v-for 用于遍历
  
Lesson03:<br>
  a. v-bind 事件绑定
  b. v-bind可以省略，直接用：
  
Lesson04:<br>
  a. v-on 键盘鼠标事件
  b. v-on:click
  c. v-on:keyup.enter
  d. v-on：可以简化为@
