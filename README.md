# ASCIIMathML
数字方程式实现方案

## 原文地址：
> http://math.chapman.edu/~jipsen/mathml/asciimathjax.html

## demo代码实现
1. 只需在HTML页面引用MathJax.js（无需下载，无需安装！）
2. 想要的数学公式有相关案例，也可自己编辑只需定义`script`的type为 `type="math/asciimath"`供MathJax识别。

`<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/2.0-latest/MathJax.js?config=TeX-MML-AM_HTMLorMML-full"> </script>`

`<script type="math/asciimath">f(x)=sum_(n=0)^oo(f^((n))(a))/(n!)(x-a)^n</script>`

`<script type="math/asciimath" id="MathJax-Element-12">d/dxf(x)=lim_(h->0)(f(x+h)-f(x))/h</script>`
