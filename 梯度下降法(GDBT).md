```{echo=FALSE}
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
```
# 梯度下降法

在求解机器学习算法的模型参数，即无约束优化问题时，梯度下降（Gradient Descent）是最常采用的方法之一，另一种常用的方法是最小二乘法。这里就对梯度下降法做一个完整的总结。
行间公式显示为：
$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$

下面看看行内公示显示为：$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$神烦狗
<script type="text/javascript" src="http://chart.googleapis.com/chart?cht=tx&chl=\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a})"></script>


           $$J(θ0,θ1...,θn)=12m∑i=0m(hθ(x0,x1,...xn)−yi)2$$
