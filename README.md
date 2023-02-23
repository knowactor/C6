# C6

&lt;C Primer Plus>第六版学习仓库

rm a.exe

```
vscode的文本编辑器继承了linux上vim的功能。

用vscode打开源文件后，可能默认的模式是一般模式，这种模式下是不能输入字符的，对于用惯了windows的人来说是非常不习惯的。

如何将默认的模式更改为插入模式呢。

File-Preferences-Settings（打开设置），搜索`vim.startInInsertMode`，在Start in Insert mode前面打上勾。

————————————————

版权声明：本文为CSDN博主「paokuflying」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。

原文链接：https://blog.csdn.net/paokuflying/article/details/106469598

作者：倚南_Determined
链接：http://events.jianshu.io/p/94226ece3ea4
来源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
```

### 编程机制

## 1.9-1.11本书的组织结构

## 1.12复习题

### 1.可移植性意味着什么

### 2.解释源代码文件,目标代码文件,可执行文件

## 1.13编程练习

把英寸单位换算成厘米单位(1inc = 2.54cm

# chapter02 C语言展示

```c
#include<stdio.h>
int main(void){
    int num ;
    num  = 1;
    printf("I am a simple ");
    printf("computer.\n");
    printf("My favourite number is %d because it is the first.\n",num);
    
    return 0;
}
```

}

## 2.2 example explain

### 2.2.2 程序细节

#include 指令和头文件

头文件可以把

为什么不内置输入输出函数

main()函数

####  23:18注释的怎么解释的

#### 26:07花括号的解释

#### 26:55声明

#### 37:40命名

##### 可以用小写字母,大写字母,数字和下划线()来命名,而且名称的第一个字符或者下划线,不能是数字

声明变量的四个理由

容易出错:不声明编译出错

printf 作为一种格式化的打印方式

## 2.3简单的程序结构

## 2.6多个函数

## 2.7 调试程序

语法错误 

