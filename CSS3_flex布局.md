# flex布局

## 1 flex布局原理

### 1.1 布局原理

- flex是flexible Box的缩写，弹性布局，任何一个容器都可以指定为flex布局
  - 当我们为父盒子设为flex布局以后，子元素的**float**、**clear**和**vertical-align**属性将失效

- 采用flex布局的元素，成为flex容器（container），它的所有子元素成为flex项目（item）
  - 子容器可以横向排列也可以纵向排列

**通过给父盒子添加flex属性，来控制子盒子的位置和排列方式**

## 2 常见父项属性

- flex-direction：设置主轴的方向
  - row：默认值，从左到右，沿x轴
  - column：从上到下，沿y轴
- justify-content：设置主轴上的子元素排列方式（重要）
  - flex-start：默认值，从头部开始，如果主轴是x轴，则从左到右排列
  - center：在主轴居中对齐
  - space-around：平分剩余空间
  - space-between：先两边贴边，再平分剩余空间（重要）
  - flex-end：从尾部开始排列
- flex-wrap：设置子元素是否换行
- align-content：设置侧轴上的子元素排列方式（多行）
- align-items：设置側轴上的子元素排列方式（单行）
- flex-flow：复合属性，相当于同时设置了flex-direction和flex-wrap