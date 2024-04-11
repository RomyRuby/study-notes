## box-shadow 属性

| 值         | 说明                                         |
| :--------- | :------------------------------------------- |
| *h-shadow* | 必需的。水平阴影的位置。允许负值             |
| *v-shadow* | 必需的。垂直阴影的位置。允许负值             |
| *blur*     | 可选。模糊距离                               |
| *spread*   | 可选。阴影的大小                             |
| *color*    | 可选。阴影的颜色。                           |
| inset      | 可选。从外层的阴影（开始时）改变阴影内侧阴影 |

## box-shadow实现双色边框

![image-20240222155636357](../../Pictures/前端学习笔记图片/image-20240222155636357.png)

```css
.double-border {
    border: 2px solid #0f69ef;
    box-shadow: 0 0 0 2px rgba(15, 105, 239, 0.2);
    border-radius: 6px;
  }
```

