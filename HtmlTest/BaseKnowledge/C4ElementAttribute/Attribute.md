# ElementAttribute

## 属性介绍

每一个元素都有着其特定的一些属性，可以通过申明对元素进行修改
**含属性的元素格式**为：
&emsp;&emsp;<元素名 元素="申明属性"> 元素内容</元素名>

## 属性实例

```html
<!DOCTYPE >
<html>
  <head>
    <meta charset="UTF-8" />
    <style>
      h1.intro1 {
        color: blueviolet;
      }
      p.intro2 {
        color: green;
      }
    </style>
  </head>
  <body>
    <a href="http://www.61.com">这是一个测试链接</a>
    <hr />
    <!-- 申明一个分界线 -->
    <h1 class="intro1">这是class测试1</h1>
    <br />
    <!-- 换行 -->
    <p class="intro2">这是class测试2</p>
    <!-- 注意这里申明新属性的代码位置 -->
  </body>
</html>
```
