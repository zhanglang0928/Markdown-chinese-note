代码块和语法高亮
===============

代码块
-----

与原来使用缩进来添加代码块的语法不同，这里使用 \`\`\` \`\`\` 来包含多行代码：

![code](images/code.png 'Code Blocks')

```
<p>code here</p>
```

>三个 \`\`\` 要独占一行。

代码高亮
----

在上面的代码块语法基础上，在第一组 \`\`\` 之后添加代码的语言，如 'C' ，即可将代码标记为 `C`：

![code_C](images/code_C.png 'C Code')

```C
#include<stdio.h>

int main(){
  printf("Hello World!");
  return 0;
}
```
