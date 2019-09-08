# 基础入门教程

## 前置基本能力

> 作为一名合格的**程序员**在学习任何编程语言前都必要熟练掌握两个基本技能：

* 一是基本的熟练键盘盲打，这是基本代码输入能力，打字速度太慢，代码输入效率就会太低。   
    * 打字速度提升可以通过金山打字通的每天坚持练习来提高。[金山打字通下载地址](https://www.51dzt.com/)

* 二是对英语的有一定的掌握程度，不一定是要能达到英语4-6级能力，但起码对常见的编程方面的用到的单词要熟练掌握。
    * 英语水平的提高需要时间的积累，并非短期可以提高，靠谱的学习方法在于每天坚持学习一点点，慢慢提升单词量（每天把自己遇到的不认识单纯抄下来，通过金山词霸等类似学习软件学习读音和词意）和语感。

## 常用基础编程工具类软件

### Visual Studio Code 入门

> VS Code是微软推出的新一代**免费开源**的现代化**轻量级**代码编辑器，支持几乎所有主流的开发语言的语法高亮、智能代码补全、自定义快捷键、括号匹配和颜色区分、代码片段、代码对比 Diff、GIT命令 等特性，支持插件扩展，并针对网页开发和云端应用开发做了优化。**VS Code**跨平台支持 Win、Mac 以及 Linux，运行流畅，可以算得上是微软的难得良心之作。

* VS Code 官方网址 [https://code.visualstudio.com/](https://code.visualstudio.com/)

![e124bbcbd8d722e5cc05a78d1e1d9625.jpeg](tool_files/vscode.jpg)

#### VS Code 基本功能介绍
![79c75870d378f46a309a60710c273850.png](tool_files/Image.png)

#### 常用快捷键

Ctrl + Shift + E 资源管理器
Ctrl + Shift + F 搜索
Ctrl + Shift + G 源代码管理器
Ctrl + Shift + D 调试
Ctrl + Shift + X 插件扩展
F1 或 Ctrl+ Shift + p 打开命令面板
Shift + Alt + F 代码格式化
Ctrl+ F 查找
Ctrl+ H 查找替换
Ctrl+ N 新建文件
Ctrl+ S 保存
Alt + ↑ 或 Alt + ↓ 上下移动一行
Shift + Alt + ↑ 或 Shift + Alt + ↓ 向上向下复制一行
![8e8db919ef09c1c67c0d48edbd94fd8d.jpeg](tool_files/vscode2.jpg)

#### 扩展插件入门
扩展插件的查找与安装：
![插件扩展](tool_files/vs-tool.png)

##### 常用的插件
* 中文语言包 Chinese (Simplified) Language Pack for Visual Studio Code
* MarkDown预览增强 Markdown Preview Enhanced
* 代码拼写检查器 Code Spell Checker
* 浏览器预览增强 open in browser
* 检查英文语句中的中文符号 sneak mark
* VS Code图标 vscode-icons
* 格式化代码工具 beautify
* HTML代码提示器 HTML Snippets
* CSS样式提升器 HTML CSS Support
* 各种皮肤主题 例如：One Dark Pro，Bimbo，Atom One Dark Theme

### MarkDown 入门
> **Markdown**是一种可以使用普通文本编辑器编写的比HTML更加简单易学的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式，同时MarkDown又能转换成HTML,PDF等多种格式。

#### MarkDown基础语法
> 以下是MarkDown的一些比较基础的语法，不同的MarkDown工具有更多更强大的语法功能实现。**在日常编写MarkDown文档过程中需要特别注意的是==中文符号和空格==。**

* 标题
> Markown的标题标记能显示出文章的结构。行首插入1-6个 # ，每增加一个 # 表示更深入层次的内容，对应到标题的深度由 1-6 阶。

![标题](tool_files/Markdown1.png)

``` markdown
    # 一级标题
    ## 二级标题
    ### 三级标题
    #### 四级标题
    ##### 五级标题
    ###### 六级标题
```
* 文本加粗

 **文本加粗**

 ``` markdown
    **文本加粗**
 ```

 * 斜体

  *斜体*

``` markdown
    *斜体*
 ```

* 下划线

 <u>下划线</u>

 ``` markdown
    <u>下划线</u>
 ```

* 删除线

  ~~删除线~~ 

``` markdown
    ~~删除线~~ 
 ```

* 分割线

    下面是一条分割线
*** 

``` markdown
    下面是一条分割线
    *** 
 ```

* 引用文本

> 这是介绍MarkDown引用文本语法的文字。

``` markdown
    > 这是介绍MarkDown引用文本语法的文字。
 ```

* 符号列表或者数字列表
    
     * 圆点符号列表
     1. 数字序号列表
     2. 数字序号列表

``` markdown
     * 圆点符号列表
     1. 数字序号列表
     2. 数字序号列表
 ```
 * 高亮

    ==文本的高亮==

``` markdown
     ==文本的高亮==
 ```
* 代办事项
 ~~谁是最好的语言~~

    * [ ] JavaScript
    * [ ] Java
    * [ ] C++
    * [x] MarkDown
``` markdown   
    * [ ] JavaScript
    * [ ] Java
    * [ ] C++
    * [x] MarkDown
 ```
* 插入连接
    [MarkDown百度百科](https://baike.baidu.com/item/markdown/3245829?fr=aladdin)

``` markdown   
     [MarkDown百度百科](https://baike.baidu.com/item/markdown/3245829?fr=aladdin)

 ```
* 插入图片

> Markdown支持嵌入网络图片或者直接拖入本地图片，其中本地图片格式支持 jpg、png 和 gif。

![](http://is4-ssl.mzstatic.com/image/thumb/Purple118/v4/f6/a3/f3/f6a3f3b8-8243-05ad-41f2-2fe69ae9d0d5/source/512x512bb.jpg)

``` markdown   
    ![](http://is4-ssl.mzstatic.com/image/thumb/Purple118/v4/f6/a3/f3/f6a3f3b8-8243-05ad-41f2-2fe69ae9d0d5/source/512x512bb.jpg)
 ```

* 插入表格

    | 帐户类型 | 免费帐户 | 标准帐户 | 高级帐户 |
    | --- | --- | --- | --- |
    | 帐户流量 | 60M | 1GB | 10GB |
    | 设备数目 | 2台 | 无限制 | 无限制 |
    | 当前价格 | 免费 | ￥8.17/月 | ￥12.33/月|

``` markdown  

        | 帐户类型 | 免费帐户 | 标准帐户 | 高级帐户 |
        | --- | --- | --- | --- |
        | 帐户流量 | 60M | 1GB | 10GB |
        | 设备数目 | 2台 | 无限制 | 无限制 |
        | 当前价格 | 免费 | ￥8.17/月 | ￥12.33/月|

 ```

* 插入源代码
> 插入源代码功能是为程序员量身定做的。用 ```上下包裹一段代码，并指定一种语言（指定语言可以显示语法高亮）。

``` markdown  
    ``` html
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <meta http-equiv="X-UA-Compatible" content="ie=edge">
            <title>Document</title>
        </head>
        <body>     

        </body>
        </html>

    ```

 ```
 #### MarkDown编辑工具推荐
> 可以去使用不同风格的MarkDown工具，最后选择一款自己的喜欢的MarkDown软件。

 [VSCode](https://code.visualstudio.com/)
 [Typore](https://www.typora.io/)
 [印象笔记](https://help.yinxiang.com/)
 [Cmd MarkDown 作业部落](https://www.zybuluo.com/cmd/)

 ### Git & GitHub 入门
 #### Git 简介
![git](tool_files/git.png)**[Git下载地址](https://git-scm.com/)**

> Git是什么？**Git 是 Linux 的创始人 Linus Torvalds 开源的一款分布式版本控制系统，以帮助开发者更好的对项目进行版本管理。每一个优秀的开发者在进行项目开发时都会第一时间给自己的项目加上 Git，以便能更好的追踪代码修改，进行版本回溯等操作。在多人协作的开发过程中，Git 更是必不可少的。**

* git基本原理：
> git版本管理工具，有3个工作区：
> 1. 工作目录
> 2. 暂存区-----存放工作中更改的文件，避免项目代码丢失。
> 3. 代码仓库-----当开发功能足够成为一个版本时，提交到仓库。其实就是将暂存区中代码复制一份存储到代码仓库中。   
 
* Git的基本工作流程
![](tool_files/git-flow.png)
#### git bash 命令行模式的基本特点：
> * 简洁，迅速，高效

* git bash 基础命令
> pwd (print working directory) 查看当前所在路径--绝对路径
> cd(change directory) 切换目标
> mkdir(make directory) 创建目录
> touch 创建文件
> ls(list) 查看当前目录下的内容
> cat 查看文件内容（一次性将内容全部显示）
> clear 清屏
> q(quit) 退出

Git有两种操作界面，**命令行模式**和图形界面模式，我们主要使用命令行模式。在Windows下我们安装好Git并点击Git Bash 图标启动Git之后会出现一个命令行窗口如下图所示：
![git](tool_files/git-2.jpg)

* Git Bash 命令行模式是使用的Linux系统命令行，所有和Window系统有一些差异，例如上图中 /c/Users 这个路径就和Window系统的下现实 C:\Users 路径显示略有不同，但实际上都是显示的同一个目录路径，实际上 /c/Users = C:\Users 。

**[Git官方教程](https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%85%B3%E4%BA%8E%E7%89%88%E6%9C%AC%E6%8E%A7%E5%88%B6)**

#### GitHub 简介
> GitHub是什么？**Github是一个基于it的代码托管平台，Github 由Chris Wanstrath, PJ Hyett 与Tom Preston-Werner三位开发者在2008年4月创办。这个星球上最流行的开源托管服务。目前已托管上百万的git项目，很多知名开源项目迁入GitHub，比如Ruby on Rails、jQuery、Ruby、Erlang/OTP；近年流行的开源库往往在GitHub首发，例如：BootStrap、Node.js、CoffeScript等。**

* 注册GitHub账号

[GitHub网址](https://github.com/)
![GitHub](tool_files/git-1.jpg)

* 首先我们登陆GitHub官网按照提示一步一步申请免费的账号，并且初始化仓库。
* 然后打开Git Bash 在命令行模式下通过cd 命令进入对应目录，在下图我进入的桌面(Desktop)目录

![Git Bash](tool_files/git1.png)

* 我们首先设置对应GitHub账号用户名和邮件

![git config](tool_files/git2.png)

>   git config  --global user.name 你自己的注册名
>   git config  --global user.email  你自己的注册邮件

* 从远程GitHub仓库克隆刚刚初始化的项目

![git clone](tool_files/git3.png)

> git clone  https://github.com/**你自己的仓库地址**

* 进入克隆目录，然后当完成对文件的编辑保存好之后，我们先将修改后的文件添加到缓存区。

![Git Bash](tool_files/git4.png)

> git add .
> git commit -m "代码提交的信息" 

* 将提交的结果推送代码到远程GitHub仓库(（在这个过程，系统会要求我们输入远程GitHub的账号和密码，按提示输入即可，由于还原系统的问题，我们就不使用SSH方式登录，但是在后面我们会在单独介绍SSH免密登录）。)

![Git push](tool_files/git5.png)

>  git push origin master

### **Vue.js**

![Vue](tool_files/logo.png)
**[Vue.js官方网站](https://cn.vuejs.org/)**

### vue简介

> **Vue.js**是现今三大流行前端框架之一(Angular.js,React.js,Vue.js),是一个只要拥有的html,css,javascript基础，就能很快学会的易用灵活的用于构建用户界面的渐进式前端框架。

#### Vue.js新手入门

* 使用Vue.js非常简单，在HTML页面中使用**script**标签导入**Vue.js**文件就可以了。
如下例：

``` javascript

    <!-- 可以通过CDN直接使用网上的资源 -->

    <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>

    <!-- 也可以使用本地资源 -->

    <script src="vue.js"></script>
```

* 接下来我们就可以来写一个Hello Vue.js!

```html

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
* Vue.js的Demo
    * vue-demo.html HTML主体文件， vue.js Vue框架文件 ，main.js Vue实例文件  
``` javascript
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>Vue入门</title>
        
    </head>
    <body>
        
            <div id="app">
                <input type="text" v-model='name'> <span v-show='name'>你的名字：{{name}}</span><br>
                <input type="text" v-model='age'> <span v-show='age'>你的年龄：{{age}}</span><br>
                <input type="text" v-model='sex'> <span v-show='sex'>你的性别：{{sex}}</span><br>
                <ul>
                    <li v-for='food in foodList'>{{ food }}</li>
                </ul>
            
            </div>

            <!-- 导入Vue框架 -->
            <script src="vue.js"></script>
            <script src="main.js"></script>
    </body>
    </html>

```
*   vue-demo.html

``` javascript
        //vue实例
    var app = new Vue({
        el: '#app',
        data: {
        name: null,
        age:null ,
        sex:null,
        foodList:['葱','姜','蒜']
        }
    });
```
* main.js

##### Vue.js 的语法特点
> 双括号{{}}语法，Vue.js通过{{ }}来实现数据的渲染。
> 指令 (Directives) 是带有 v- 前缀的由Vue.js定义的特殊属性。例如：v-for,v-bind,v-show等等这些指令，除了Vue.js自带的属性，我们还可以自定义Vue指令。
> el是Element的缩写，el属性对应的是Vue框架挂载在HTML中对应的视图
> data是Vue实例的数据属性

#### v-for指令

> 通过v-for指令来实现循环数组遍历，使用特定语法 v-for='alias in expression'，为当前遍历的元素提供别名,通常使用在ul或者ol标签中li选项中。

``` html

    <div id="app">
           <ul>
                <!-- <li v-for="food in foodList">{{ food }} </li> -->
                <li v-for='food in foodList'>
                        {{food.name}} ￥：{{food.discount ? food.price*food.discount : food.price}} 折扣率{{food.discount}}
                </li>
            </ul>

    </div>

    <script src="vue.js"></script>
    <script src="v-for.js"></script>

```
* vue-01.html

``` javascript
    var app = new Vue({
    el:'#app',
    data:{
        // foodList:['可乐','薯条','炸鸡']
        foodList:[
            {name:'可乐',price:3,discount:0.9},
            {name:'薯条',price:5,discount:0.8},
            {name:'炸鸡',price:10,discount:0},
        ]
    }
    })
```
* v-for.js