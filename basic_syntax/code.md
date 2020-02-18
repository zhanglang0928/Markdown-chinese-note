代码
====

 ## 1. 代码块

1.1 使用缩进来 "Tab 键" or "空格键" 插入代码块：

    <html> // Tab开头
        <title>Markdown</title>
    </html> // 四个空格开头

 1.2 使用\`\`\`来插入代码块：

插入代码并定义类型用\`\`\`开头和结尾，并在紧跟着第一个\`\`\`后可注明语言类型

\`\`\`C language  
#include<stdio.h> 

int main(){  
    printf("Hello World!");  
    return 0;  
}
\`\`\`

```C language
#include<stdio.h>  

int main(){  
    printf("Hello World!"); 
    return 0;  
}
```

**代码块前后需要有至少一个空行，且每行代码前需要有至少一个 Tab 或四个空格**；

## 2. 行内插入代码

也可以通过 \`\`，插入行内代码（\` 是 `Tab` 键上边、数字 `1` 键左侧的那个按键）：

例如 `<title>Markdown</title>`,  
C语言中printf语句 `printf("Hello World!");`

## 3. 转换规则

代码块中的文本（包括 Markdown 语法）都会显示为原始内容，而特殊字符会被转换为 HTML [字符实体](https://zh.wikipedia.org/wiki/XML%E4%B8%8EHTML%E5%AD%97%E7%AC%A6%E5%AE%9E%E4%BD%93%E5%BC%95%E7%94%A8%E5%88%97%E8%A1%A8)。