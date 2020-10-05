# HTML常用标签
## <a>标签
>可以创建通向其他网页、文件、同一页面内的位置、电子邮件地址或任何其他 URL 的超链接

### 常用属性

- **download**
- **rel**
- **target**
- **href**

#### download

​		download后面附加的http  URL必须是同源的，blob:URL和data：URL则不受同源限制

#### rel

​		指定了目标对象到链接对象的关系。最常用的是定义`rel=stylesheet`还有其他的取值`nofollow`、`noopener``noreferrer`和`prefetch`、`preload`会涉及到安全或者性能方面

#### target

​		`_self`:当前页面加载

​		`_blank`:新窗口打开

​		`_parent`:父窗口加载

​		`_top`:祖先窗口打开

#### href

​		包含指向的URL和URL片段。URL片段可以配合id选择器将页面移动到相应元素

**ps:**

1. `href="#top"`或`href="#"`可以直接返回顶部.
2. `href=javascript:void(0)`伪代码





## <table>相关标签

| 标签  |    描述    |
| :---: | :--------: |
| table |  表格数据  |
| thead |   列头行   |
| tbody |   内容行   |
| tfoot |   汇总行   |
|  tr   |  表格的行  |
|  th   | 表头单元格 |
|  td   | 数据单元格 |

**ps:**

1. 由于浏览器的纠错能力，即便不写`<thead>` `<tbody>` `<tfoot>`，也会自动矫错，但不建议省略
2. 在上古时代还存在一种利用`<table>`的布局，时代的眼泪



## <img>标签

### 属性

- src
- alt
- srcset
- sizes



#### src

​		图像的URL

#### alt

​		图像的备用文本（用于图像未加载的代替，提升可访问性）

#### srcset,sizes

​		用于高分辨率屏幕



***

**总结:**HTML的学习，其实只要过一遍，有个眼缘就行。最终需要结合css和JavaScript的