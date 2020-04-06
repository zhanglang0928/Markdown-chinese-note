图像
====

插入图片的语法和插入超链接的语法基本一致，只是**在最前面多一个** `!`。也分为行内式和参考式两种。

行内式
-----

```markdown
![GitHub](https://avatars2.githubusercontent.com/u/3265208?v=3&s=100 "GitHub,Social Coding")
```

![GitHub](https://avatars2.githubusercontent.com/u/3265208?v=3&s=100 "GitHub,Social Coding")

方括号中的部分是图片的替代文本，括号中的 'title' 部分和链接一样，是可选的。

参考式
----

```markdown
![GitHub][github]

[github]: https://avatars2.githubusercontent.com/u/3265208?v=3&s=100 "GitHub,Social Coding"
```

![GitHub][github]

[github]: https://avatars2.githubusercontent.com/u/3265208?v=3&s=100 "GitHub,Social Coding"

指定图片的显示大小和位置
----------------------

Markdown 不支持指定图片的显示大小，不过可以通过直接插入`<img />`标签来指定相关属性：

    alt：链接的显示名即![]括号内的名称
    title：照片文件名
    width：宽度
    height：高度

```html
<img src="https://avatars2.githubusercontent.com/u/3265208?v=3&s=100" alt="GitHub" title="GitHub,Social Coding" width="50" height="50" />
```

<img src="https://avatars2.githubusercontent.com/u/3265208?v=3&s=100" alt="GitHub" title="GitHub,Social Coding" width="50" height="50" />

可以用`<div>`和`align`来控制图片位置：

    center：居中对齐
    left：靠左对齐（可不用设置，默认此对齐方式）
    right：靠右对齐

```html
<div align="center">
<img src="https://avatars2.githubusercontent.com/u/3265208?v=3&s=100" alt="GitHub" title="GitHub,Social Coding" width="50" height="50" />
</div>
```
<div align="center">
<img src="https://avatars2.githubusercontent.com/u/3265208?v=3&s=100" alt="GitHub" title="GitHub,Social Coding" width="50" height="50" />
</div>