# Vue.js-Learing
01:
  开头需要引入<script src="https://cdn.jsdelivr.net/npm/vue"></script>
  v-model=""：双向绑定
  v-show="":可以隐藏信息
  <body>
    <div id="app">
      {{ message }}
    </div>
  </body>
  <javascript>
    var app = new Vue({
    el: '#app',
    data: {
    message: 'Hello Vue!'
    }
  })
  </javascript>
