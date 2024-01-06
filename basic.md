## 属性
属性包含了关于元素的一些额外信息，这些信息本身不应显现在内容中。本例中，class 是属性名称，editor-note 是属性的值。class 属性可为元素提供一个标识名称，以便进一步为元素指定样式或进行其他操作时使用。

替换文字属性 alt，是图像的描述内容，用于当图像不能被用户看见时显示，不可见的原因可能是：

无序列表（Unordered List）中项目的顺序并不重要，就像购物列表。用一个 `<ul> `元素包围。
有序列表（Ordered List）中项目的顺序很重要，就像烹调指南。用一个`<ol> `元素包围。

列表的每个项目用一个列表项目（List Item）元素 `<li> `包围。

## 链接
a 是 "anchor" （锚）的缩写，href 这个名字可能开始看起来有点令人费解，代表超文本引用（ hypertext reference）
```
<a href="https://www.mozilla.org/zh-CN/about/manifesto/">Mozilla Manifesto</a>
```




## CSS 基础
CSS 是一门样式表语言<br>
例如,
```
p {
  color: red;
}
```

**p:** selcetor，元素选择器，可以是p，li等；<br>

中括号内是声明，

margin: 当你在 margin 或 padding 这样的属性上设置两个值时，第一个值影响元素的上下方向（在这个例子中设置为 0）；第二个值影响左右方向。(这里，auto 是一个特殊的值，它将可用的水平空间平均分配给左和右）


## Javascript
### 变量（Variable）
用 var 或者 let 进行声明。例如，
```js
let myVariable;
// 定义变量后可以进行赋值，如
myVariable = "李雷";
// 也可以在定义的时候赋值，如
let myVariable = "李雷";
```

注意变量可以有不同的数据类型 ：
js 中的注释使用`//`或者 
```js
/*
这是注释
*/
```
### 条件语句
if else 语句
```
let iceCream = "chocolate";
if (iceCream === "chocolate") {
  alert("我最喜欢巧克力冰淇淋了。");
} else {
  alert("但是巧克力才是我的最爱呀……");
}

```
