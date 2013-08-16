# select

---

下拉框和自动补全的样式

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="dist/select.css">

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
    <li class="ui-select-item ui-select-disabled"><a href="#">选项 2</a></li>
    <li class="ui-select-item"><a href="#">选项 3</a></li>
  </ul>
</div>
<div class="ui-select" style="width: 120px">
  <a href="#" class="ui-select-trigger">
    默认选项
    <i class="iconfont" title="下三角形">&#xF03C;</i>
  </a>
  <div class="ui-select-content">
    <ul>
      <li class="ui-select-item">选项 1</li>
      <li class="ui-select-item ui-select-disabled">选项 2</li>
      <li class="ui-select-item">选项 3过长过长过长</li>
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
    <li class="ui-select-item"><a href="#">选项 1</a></li>
    <li class="ui-select-item ui-select-disabled"><a href="#">选项 2</a></li>
    <li class="ui-select-item"><a href="#">选项 3</a></li>
  </ul>
</div>
````
