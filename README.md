# css-layout

## 箭头：
```html
.sx-arrow-down{
  border-style:solid dashed dashed dashed;
  border-width:10px;
  border-color:#f00 transparent transparent transparent;
  width:0;height:0;
}
.sx-arrow-up{
  border-style:dashed dashed solid dashed;
  border-color:transparent transparent #f00 transparent;
  border-width:10px;
  width:0;height:0;
}
.sx-arrow-left{
  border-style:dashed solid dashed dashed;
  border-color:transparent #f00 transparent  transparent;
  border-width:10px;
  width:0;height:0;
}
.sx-arrow-right{
  border-style:dashed dashed dashed solid;
  border-color:transparent transparent transparent  #f00;
  border-width:10px;
  width:0;height:0;
}
```

## 阴影

```html
.box-shadow{  
  box-shadow:-10px 0 10px red, /*左边阴影*/  
  10px 0 10px yellow, /*右边阴影*/  
  0 -10px 10px blue, /*顶部阴影*/  
  0 10px 10px green; /*底边阴影*/  
}
```
