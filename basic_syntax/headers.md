标题
====

1. Setext 形式
--------------

```markdown
H1
==

H2
--
```

H1
==

H2
--

>`=` 和 `-` 的数量是没有限制的。通常的做法是使其和标题文本的长度相同，这样看起来比较舒服。也可以自己确定固定的个数，比如3个。  
>Setext 形式只支持 `h1` 和 `h2` 两种标题。

2. atx 形式
----------

- 2.1 可以用对称的 `#` 包括文本：

```markdown
####H4####

#####H5#####
```

####H4###

#####H5#####

- 2.2 也可以只在左边使用 `#`：

```markdown
####H4

#####H5
```

####H4

#####H5

- 2.3  `#` 左侧和靠近文本的`#`右侧都不可以有任何空白，否则就会定义成为标题。

```markdown
 # ##左侧使用了空格###

###内侧  使用了空格
```

 # ##左侧使用了空格###

###内侧  使用了空格

>在这一点上，可能各种 Markdown 的实现会有不同的结果，不过仍然需要我们遵守语法规则。