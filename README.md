# select

---

下拉框和自动补全的样式

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="dist/select.css">

### 下拉框

````html
<div class="ui-select" style="width: 100px">
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
````

### 其他 DOM 结构

````html
<div class="ui-select" style="width: 100px">
  <a href="#" class="ui-select-trigger">
    默认选项
    <i class="iconfont" title="下三角形">&#xF03C;</i>
  </a>
  <div class="ui-select-content">
    <ul>
      <li class="ui-select-item"><a href="#">选项 1</a></li>
      <li class="ui-select-item ui-select-disabled"><a href="#">选项 2</a></li>
      <li class="ui-select-item"><a href="#">选项 3</a></li>
    </ul>
  </div>
</div>
````

### trigger 在外面的下拉框

````html
<a href="#" class="ui-select-trigger" style="display:block; width: 98px">
  默认选项
  <i class="iconfont" title="下三角形">&#xF03C;</i>
</a>
<div class="ui-select" style="width: 100px">
  <ul class="ui-select-content">
    <li class="ui-select-item"><a href="#">选项 1</a></li>
    <li class="ui-select-item ui-select-disabled"><a href="#">选项 2</a></li>
    <li class="ui-select-item"><a href="#">选项 3</a></li>
  </ul>
</div>
````
