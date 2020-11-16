## 特效

### 偏移量

- offsetParent用于获取定位的父级元素
- offsetParent和parentNode的区别

```javascript
var box = document.getElementById('box');
console.log(box.offsetParent);
console.log(box.offsetLeft);
console.log(box.offsetTop);
console.log(box.offsetWidth);
console.log(box.offsetHeight);
```

![1498743216279](media/1498743216279.png)

### 客户区大小

```javascript
var box = document.getElementById('box');
console.log(box.clientLeft);
console.log(box.clientTop);
console.log(box.clientWidth);
console.log(box.clientHeight);
```

![1498743269100](media/1498743269100.png)

### 滚动偏移

```javascript
var box = document.getElementById('box');
console.log(box.scrollLeft)
console.log(box.scrollTop)
console.log(box.scrollWidth)
console.log(box.scrollHeight)
```

![1498743288621](media/1498743288621.png)

### 案例 

- 匀速动画函数
- 变速动画函数
- 回到顶部
- 无缝轮播图
- 模拟滚动条
- 拖拽案例
- 放大镜案例

### 元素的类型

![1497169919418](media/1497169919418.png)