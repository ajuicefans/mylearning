# 1.什么是JavaScript？

## 1.1 概述

JavaScript是一门世界上最流行的脚本语言

Java与JavaScript毫无关系

JavaScript 10天开发出来的；网景公司

==**一个合格的后端人员，必须要精通JavaScript**==



## 1.2 历史

> [JavaScript发展历史](https://blog.csdn.net/kese7952/article/details/79357868?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522167941432616800226543161%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fblog.%2522%257D&request_id=167941432616800226543161&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_ecpm_v1~rank_v31_ecpm-1-79357868-null-null.blog_rank_default&utm_term=JavaScript&spm=1018.2226.3001.4450)

EMCAScript可以理解为JavaScript的一个标准

（2020.01.04）的最新版本已经到 es6 版本

但大部分浏览器还只停留在支持 es5 的代码上

开发环境--线上环境，版本不一致！

> 即使迭代了这么多版本，但是JS的核心没有变；
>
> 例如：变量、流程控制、对象、数组、关键字......



# 2.快速入门

## 2.1 引入JavaScript

1. 内部标签使用

   ```html
   <script>
   	//...
   </script>
   ```

2. 外部引入

   ajuicefans.js

   ```javascript
   //...
   ```

   test.html

   ```html
   <script src="ajuicefans.js"></script>
   ```

   ---

### 测试代码：

1. 内部标签使用

```html
<!--在html文件中写 内部标签使用-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>1.我的第一个JavaScript程序</title>

<!--  script标签内，写JS代码-->
  <script>
    alert('hello,world!');
  </script>
    
</head>
<body>

<!--这里也可以存放-->
</body>
</html>
```

2. 外部引入

```html
<!--在js文件中写 外部引入-->

<!--在html文件中写 可以写的位置见上一个代码块注释 -->
<!--注意：script标签必须成对出现-->
	<script src="js/ajuicefans.js"></script>

<!--不用显示定义type，也默认就是JavaScript-->
	<script type="text/javascript"></script>	

<!--在 ajuicefans.js 文件中写的代码-->
alert('hello,world!')
```

---



## 2.2 基本语法入门