## Welcom to Commander Zhong's Blog
这个博客记载着博主的一些使用一些软件(如IDL, Python等)的一些小心得，主要是便于自己以后回顾，当然也可以供网友们参考。
 
### IDL
这部分记载关于**IDL**(Interactive Data Language)的心得。

#### 2019.10.20
在 _PLOT_ 中使用关键字 _[xyz]style=5_ 可以无边框。

#### 2019.10.22
关于变量作用范围: 在 _FUCTION_ 中对传入的变量进行操作是会改变变量的。

#### 2019.11.05
矩阵运算符号为 _#_ ；

数组运算时要注意**IDL**的数组坐标，以二维为例：A[i,j]为第i-1列，第j-1行的数组元素；

数组矩阵计算举例：
```markdown
>a=[[1,2,3],[2,2,4],[5,3,1]]
a = 
1 2 3
2 2 4
5 3 1
>b=[1,2,3]
b = 
1 2 3
>a#b
ans = 
20 15 14
```

### Python
这部分为**Python**的学习心得。

```markdown
Syntax highlighted code block

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
