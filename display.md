# display

## summary
display 属性指定一个元素的box（盒）模型的渲染类型。
HTML中，display属性的默认值取决于HTML规范所描述的行为，或是浏览器／用户的默认样式。XML中的默认值为inline。

除了一些不同的渲染类型，值none使元素及元素的所有后代元素都不显示，且不占用原有的空间。

display 是CSS中最重要的用于控制布局的属性。每个元素都有一个默认的 display 值，这与元素的类型有关。对于大多数元素它们的默认值通常是 block 或 inline 。一个 block 元素通常被叫做块级元素。一个 inline 元素通常被叫做行内元素。

## block

<div>
div 是一个标准的块级元素。一个块级元素会新开始一行并且尽可能撑满容器。其他常用的块级元素包括 p 、 form 和HTML5中的新元素： header 、 footer 、 section 等等。

</div>

## inline
span 是一个标准的行内元素。一个行内元素可以在段落中 <span> 像这样 </span> 包裹一些文字而不会打乱段落的布局。 a 元素是最常用的行内元素，它可以被用作链接。

## none
另一个常用的display值是 none 。一些特殊元素的默认 display 值是它，例如 script 。 display:none 通常被 JavaScript 用来在不删除元素的情况下隐藏或显示元素。

它和 visibility 属性不一样。把 display 设置成 none 元素不会占据它本来应该显示的空间，但是设置成 visibility: hidden; 还会占据空间。

## 其他 display 值

还有很多的更有意思的 display 值，例如 list-item 和 table 。这里有一份详细的列表。之后我们会讨论到 inline-block 和 flex 。

## 额外加分点

就像我之前讨论过的，每个元素都有一个默认的 display 类型。不过你可以随时随地的重写它！虽然“人为制造”一个行内元素可能看起来很难以理解，不过你可以把有特定语义的元素改成行内元素。常见的例子是：把 li 元素修改成 inline，制作成水平菜单。