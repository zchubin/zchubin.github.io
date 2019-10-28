# zchubin.github.io
------
[zhongchubin](https://zchubin.github.io/zcb.html "主页")

# 这是我的博客伴生文档

> MYLOGO
>> ![favicon.ico](https://zchubin.github.io/favicon.ico "MyLogo")

为了方便以后要的维护，本文档将记录本博客所有可能遗忘`html\css`中提及的`class`、`id`和`元素`。

## HTML中的解释

### `<head>`中的新元素

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, user-scalable=0, shrink-to-fit=no" />
```
> 为了使移动端的页面在不同的手机上同样的大小来显示，
> 我们可以将页面的宽度固定，
> 然后获取设备的宽度，可以得到我们之前设定的宽度与设备宽度的比例，
> 再使用HTML5新增的viewport来对页面进行缩放，并固定不允许用户再重新缩放。

![layoutviewport](https://img-blog.csdn.net/20161101152020082)
![visulviewport](https://img-blog.csdn.net/20161101151953235)

|   属性名称   |                                寓意                                |
|-------------|--------------------------------------------------------------------|
|    width    |设置layout viewport的宽度，为正整数，使用字符串‘width-device’表示设备宽度|
|    height   |             设置layout viewport的高度，同上，这个很少使用             |
|initial-scale|               设置页面的初始缩放值，为一个数字，可以为小数              |
|minimum-scale|               允许用户的最小缩放值，为一个数字，可以带小数              |
|maximum-scale|               允许用户的最大缩放值，为一个数字，可以带小数              |
|user-scalable|    是否允许用户进行缩放，值为”no”或”yes”, no 代表不允许，yes代表允许     |



## CSS中的解释


