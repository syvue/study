
## vue.js

![Vue](logo.png)

### vue简介

> **Vue.js**是现今三大流行前端框架之一(Angular.js,React.js,Vue.js),是一个只要拥有的html,css,javascript基础，就能很快学会的易用灵活的用于构建用户界面的渐进式前端框架。

### Vue.js新手入门

* 使用Vue.js非常简单，在HTML页面中使用**script**标签导入**Vue.js**文件就可以了。
如下例：
``` javascript
<!-- 可以通过CDN直接使用网上的资源 -->
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<!-- 也可以使用本地资源 -->
<script src=vue.js"></script>
```
* 接下来我们就可以来写一个Hello Vue.js!
  
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Hello!Vue.js</title>
    <!-- 导入Vue.js -->
    <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
</head>
<body>
     <div id="app">
          {{ message }}
     </div>


     <script>
         var app = new Vue({
             el: 'app',
             data: {
                 message: 'Hello Vue.js!!!!'
             }
         })
     
     </script>

    </body>
</html>
```

