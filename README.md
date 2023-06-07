# JavaScript30
JavaScript30 code
可能与课程代码略有不同（我采用的方法是先上课后coding 最后对照效果修改测试） 

### day1:   
使用JS移除 class='playing' 的 CSS 时， 我选择的监听事件为 'keyup'。  
理由：当使用 'tansitionend' 时，如果我连续按键，  
那么最终 class='playing' 的 CSS 将不会被移除。

### day2:
时钟：运用绝对布局、旋转、Date对象、时间间隔函数setInterval。

### day3:
css：使用 :root 创建css全局变量 实现默认css样式。  
JavaScript：
1. 使用监听事件 input 实时监听 input元素的变化。  
2. 使用 URL.createObjectURL() || webkitURL.createObjectURL() 将上传的图片文件转换为 BLOB 预览。

### day4:
Array api

### day5:
transform: translateY(0) 保持原来的纵向位置  

监听transitionend事件时 因为使用了 this.classList.toggle() 为避免多次执行  
故 当e.propertyName.includes('grow') 执行一次this.classList.toggle()即可

### day6:  
使用Fetch 发送跨域请求 fetch(url) 返回Promise对象  
/\B(?=(\d{3})+(?!\d))/g  全局匹配 不是任意数字 而是 一个或多个 三位数 与前面 数字或字母 的分界 的位置  
input 事件 change  是改变值后 失去焦点时 触发  
input 事件 keyup   是按键弹起后         触发

### day7:  
Array find()     返回符合条件的第一个元素  
Array filter()   返回一个数组 该数组包含所有符合条件的元素  
**<a href="https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Array/splice" >Array splice()</a>**   
  **<a href="https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Array/slice" >Array slice()</a>**  
**<a href="https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment">解构赋值</a>**
