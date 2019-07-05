# ASCIIMathML
数字方程式实现方案

## 原文地址：
> http://math.chapman.edu/~jipsen/mathml/asciimathjax.html

> https://github.com/mathjax/MathJax

> https://www.mathjax.org/

## 描述和结论
通过学习公式编辑相关知识以及查阅MathJax相关文档, 编写demo, 得出结论: 这个js库适合处理学科公式的相关场景, 能够满足当前的需求, 并有一定扩展空间(下图中 输入LaTex, 右键菜单能查看MathML和AsciiMath格式公式):
  
1. 输入: 即数据库中存储的是LaTex格式的数据;
2. 可以是svg, 图片 以及 html、css方式；
3. 输出内容的多端适配：能够适配手机端、pc端、pad端；
4. 格式转换：插件提供ASCIIMATH、MATHML、LaTex的相互转换

## demo代码实现
1. 只需在HTML页面引用MathJax.js（无需下载，无需安装！）
2. 想要的数学公式有相关案例，也可自己编辑只需定义`script`的type为 `type="math/asciimath"`供MathJax识别。

`<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/2.0-latest/MathJax.js?config=TeX-MML-AM_HTMLorMML-full"> </script>`

`<script type="math/asciimath">f(x)=sum_(n=0)^oo(f^((n))(a))/(n!)(x-a)^n</script>`

`<script type="math/asciimath" id="MathJax-Element-12">d/dxf(x)=lim_(h->0)(f(x+h)-f(x))/h</script>`
