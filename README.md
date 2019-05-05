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
  a. v-bind 事件绑定<br>
  b. v-bind可以省略，直接用：
  
Lesson04:<br>
  a. v-on 键盘鼠标事件<br>
  b. v-on:click<br>
  c. v-on:keyup.enter<br>
  d. v-on：可以简化为@<br>
  e. v-on 要使用methods
  ```javascript
  var app = new Vue ({
  	el: '#app',
	methods: {
 	        onClick: function() {
 			console.log('clicked')
 			},
 			onEnter: function() {
 				console.log('mouse enter');
 			},
 			onOut: function() {
 				console.log('mouse leave');
 			},
 			onSubmit: function() {
 				// e.preventDefault();
 				console.log('submitted');
 			},
 			onEnter: function() {
 				console.log('Entered');
 			}
		}        
  });
  ```
  
Lesson05:<br>
  a. v-model 双向绑定<br>
  b. v-model.trim 消除空格<br>
  c. v-model.lazy 推迟 当输入完才绑定<br>
  d. v-model.number 价格 年龄用于数字表达 转化成数字类型<br>

Lesson06:<br>
  a. v-model适用的3个标签<br>
  b. input<br>
  c. select<br>
      ```html
    <div id="app">
      {{ message }}
    </div>
      
      ctrl可多选，shift可全选<br>
  d. textarea

Lesson07:<br>
