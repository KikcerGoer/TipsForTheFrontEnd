<a id="top" href="#top"> CSS 属性小坑 :maple_leaf:</a> 
----
`一些Css属性的使用,会有一些特定的要求和环境,有的Css熟悉会配合其他css属性使用,这里我们将详细讨论它`

- [x] :maple_leaf: <a href="#verticalalignWhatNeed">`vertical-align 不起作用`</a>
- [x] :maple_leaf: <a href="#">``</a>
- [x] :maple_leaf: <a href="#">``</a>
- [x] :maple_leaf: <a href="#">``</a>

##### <a id="verticalalignWhatNeed" href="#verticalalignWhatNeed">vertical-align 不起作用</a>  :star2: <a href="#top"> :arrow_up: </a>
`我们都知道 vertical-align属性 可以让图片，文本等在元素中垂直居中,但是这明明是一个所有浏览器都支持的属性,但是有时候它却没有效果`<br/>

**`原因:`** `因为vertical-align只作用在` **`inline-block`** 或者 **`inline`** `，还有` **`table-cell`** `等元素内`
```css
 .navbar-logo-name{
   display: inline-block;
   vertical-align:baseline;
 }
```
* vertical-align 支持的属性值
* `baseline`： `把当前盒的基线与父级盒的基线对齐。如果该盒没有基线，就将底部外边距的边界和父级的基线对齐 `
* `sub`： `把当前盒的基线降低到合适的位置作为父级盒的下标（该值不影响该元素文本的字体大小） `
* `super`： `把当前盒的基线提升到合适的位置作为父级盒的上标（该值不影响该元素文本的字体大小）` 
* `text-top`： `把当前盒的top和父级的内容区的top对齐 `
* `text-bottom`：` 把当前盒的bottom和父级的内容区的bottom对齐` 
* `middle`：` 把当前盒的垂直中心和父级盒的基线加上父级的半x-height对齐` 
* `top`： `把当前盒的top与行盒的top对齐 `
* `bottom`： `把当前盒的bottom与行盒的bottom对齐`
  
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>
####  <a id="" href="#"></a>  :star2: <a href="#top"> :arrow_up: </a>







