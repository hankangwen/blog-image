# Blog-Image
这里放博客的图片

## Mark down表格
```
header 1 | header 2| header 3
---|---|---
row 1 col 1 | row 1 col 2 | row 1 col 2
row 2 col 1 | row 2 col 2 | row 1 col 2
```
header 1 | header 2| header 3
---|---|---
row 1 col 1 | row 1 col 2 | row 1 col 2
row 2 col 1 | row 2 col 2 | row 1 col 2

## Mark down插入图片
绝对路径和把图片转成base64那些不实用，不做介绍
### 1.相对路径
若markdown文件和图片位置分别为：

![test image size](https://codechina.csdn.net/hankangwen/blog-image/-/raw/master/pictures/2021/12/20_20_51_29_20211220205129.png)

图片的链接这样写：
```
![avatar](DocImage/1OpenSettings.jpg)
```
### 2.插入github等地址图片
1.借助PicGo把图片上传至gitcode。(手动上传也可以，但是太不方便了)

> picGo下载地址：[https://github.com/Molunerfinn/PicGo/releases](https://github.com/Molunerfinn/PicGo/releases)

图片的链接这样写：
```
![](https://codechina.csdn.net/hankangwen/blog-image/-/raw/master/pictures/2021/12/20_20_51_29_20211220205129.png)
```

## Mark down操作图片
Markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的```<img>```标签。
```
<img src="图片.png" alt="图片替换文本" width="500" height="200" align="bottom" />
```
最终效果：

<img src="https://codechina.csdn.net/hankangwen/blog-image/-/raw/master/pictures/2021/12/20_20_51_29_20211220205129.png" alt="图片替换文本" width="500" height="200" align="bottom" />
