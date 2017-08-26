
# 梯度下降法

在求解机器学习算法的模型参数，即无约束优化问题时，梯度下降（Gradient Descent）是最常采用的方法之一，另一种常用的方法是最小二乘法。

## 概念

### 梯度
在微积分里面，对多元函数的参数求∂偏导数，把求得的各个参数的偏导数以向量的形式写出来，就是梯度。比如函数$f(x,y)$, 分别对$x$,$y$求偏导数，求得的梯度向量就是$(∂f/∂x, ∂f/∂y)^T$,简称$grad f(x,y)$或者$▽f(x,y)$。对于在点(x0,y0)的具体梯度向量就是(∂f/∂x0, ∂f/∂y0)T.或者▽f(x0,y0)，如果是3个参数的向量梯度，就是(∂f/∂x, ∂f/∂y，∂f/∂z)T,以此类推。

　　　　那么这个梯度向量求出来有什么意义呢？他的意义从几何意义上讲，就是函数变化增加最快的地方。具体来说，对于函数f(x,y),在点(x0,y0)，沿着梯度向量的方向就是(∂f/∂x0, ∂f/∂y0)T的方向是f(x,y)增加最快的地方。或者说，沿着梯度向量的方向，更加容易找到函数的最大值。反过来说，沿着梯度向量相反的方向，也就是 -(∂f/∂x0, ∂f/∂y0)T的方向，梯度减少最快，也就是更加容易找到函数的最小值。
行间公式显示为：
$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$

下面看看行内公示显示为：$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$神烦狗
<script type="text/javascript" src="http://chart.googleapis.com/chart?cht=tx&chl=\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a})"></script>


           $J(θ_0,θ_1...,θ_n)=12m∑i=0_m*(hθ(x_0,x_1,...x_n)−y_i)2$










```{java, echo=FALSE}
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
```
