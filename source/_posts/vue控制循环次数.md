---
title: vue控制v-for循环的次数
---
```html
<p v-for="(item,index) in array" v-if='index<=1'></p>
```

当前为只循环两次，可以更改v-if的数字，来进行循环次数的控制