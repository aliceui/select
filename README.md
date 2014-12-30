# select

---

下拉框和自动补全的样式

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="dist/select.css">

`````html
<style>
@font-face {
    font-family: "rei";
    src: url("https://i.alipayobjects.com/common/fonts/rei.eot?20140611"); /* IE9 */
    src: url("https://i.alipayobjects.com/common/fonts/rei.eot?20140611#iefix") format("embedded-opentype"), /* IE6-IE8 */
    url("https://i.alipayobjects.com/common/fonts/rei.woff?20140611") format("woff"), /* chrome 6+銆乫irefox 3.6+銆丼afari5.1+銆丱pera 11+ */
    url("https://i.alipayobjects.com/common/fonts/rei.ttf?20140611")  format("truetype"), /* chrome銆乫irefox銆乷pera銆丼afari, Android, iOS 4.2+ */
    url("https://i.alipayobjects.com/common/fonts/rei.svg?20140611#rei") format("svg"); /* iOS 4.1- */
}

.nico-insert-code .iconfont {
  font-family:"rei"!important;
  font-style: normal!important;
  font-weight: normal;
  cursor: default;
  -webkit-font-smoothing: antialiased;
}
</style>
`````

### 下拉框

支持不同结构

- li 中可以没有 a
- `ui-select-content` 也可以增加一个 DOM 结构

````html
<div class="ui-select" style="width: 120px">
  <a href="#" class="ui-select-trigger">
    默认选项
    <i class="iconfont" title="下三角形">&#xF03C;</i>
  </a>
  <ul class="ui-select-content">
    <li class="ui-select-item"><a href="#">选项 1</a></li>
    <li class="ui-select-item ui-select-item-disabled"><a href="#">选项 2</a></li>
    <li class="ui-select-item"><a href="#">选项 3</a></li>
  </ul>
</div>
<div class="ui-select" style="width: 120px">
  <a href="#" class="ui-select-trigger ui-select-disabled">
    默认选项
    <i class="iconfont" title="下三角形">&#xF03C;</i>
  </a>
  <div class="ui-select-content">
    <ul>
      <li class="ui-select-item">选项 1</li>
      <li class="ui-select-item ui-select-item-disabled">选项 2</li>
      <li class="ui-select-item">选项 3</li>
    </ul>
  </div>
</div>
````

### trigger 在外面的下拉框

````html
<a href="#" class="ui-select-trigger" style="display:block; width: 118px">
  默认选项
  <i class="iconfont" title="下三角形">&#xF03C;</i>
</a>
<div class="ui-select" style="width: 120px">
  <ul class="ui-select-content">
    <li class="ui-select-item"><a href="#">选项 1过长过长过长</a></li>
    <li class="ui-select-item ui-select-item-disabled"><a href="#">选项 2</a></li>
    <li class="ui-select-item"><a href="#">选项 3</a></li>
  </ul>
</div>
````
