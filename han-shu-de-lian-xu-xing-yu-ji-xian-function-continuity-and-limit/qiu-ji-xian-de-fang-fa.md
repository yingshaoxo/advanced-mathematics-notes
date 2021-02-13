# 求极限的基本方法

## [https://www.khanacademy.org/math/ap-calculus-ab/ab-limits-new/ab-1-7/v/flow-chart-of-limit-strategies](https://www.khanacademy.org/math/ap-calculus-ab/ab-limits-new/ab-1-7/v/flow-chart-of-limit-strategies) <a id="firstHeading"></a>

## 洛必达法则\(L'Hôpital's rule\) <a id="firstHeading"></a>

使用条件: 

1. `0/0` or `∞/∞` 型 分式
2. 分子与分母皆可以求出导数

![](../.gitbook/assets/image%20%285%29.png)

![](../.gitbook/assets/image%20%2824%29.png)

### 基本求导公式

$$
\begin{align*}
\\

(C)^\prime &= 0    &\text{(C is a constant)} \\ \\

(x^n)^\prime &= nx^{n-1} \\ \\

(a^x)^\prime &= a^x\ln{a}    &(e^x)^\prime &= e^x \\ \\

(\log_a{x})^\prime &= \frac{1}{x\ln{a}}    &(\ln{x})^\prime &= \frac{1}{x} \\ \\ \\


(\sin{x})^\prime &= \cos{x}    &(\cos{x})^\prime &= -\sin{x} \\ \\

(\tan{x})^\prime &= \sec^2{x}    &(\cot{x})^\prime &= -\csc^2{x} \\ \\

(\sec{x})^\prime &= \sec{x}\tan{x}    &(\csc{x})^\prime &= -\csc{x}\cot{x} \\ \\ \\


(\arcsin{x})^\prime &= \frac{1}{\sqrt{1 - x^2}}    &(\arccos{x})^\prime &= -\frac{1}{\sqrt{1 - x^2}} \\ \\

(\arctan{x})^\prime &= \frac{1}{1 + x^2}    &(arccot{x})^\prime &= -\frac{1}{1 + x^2} \\ \\

\end{align*}
$$

$$
\left(\ln \left(x+\sqrt{1+x^{2}}\right)\right)^{\prime}=\frac{1}{\sqrt{1+x^{2}}}
$$

## 基本恒等变形

$$
\begin{align*}
&\csc x = \frac{1}{\sin x}
\\ \\
&\sec x = \frac{1}{\cos x}
\\ \\
&\cot x = \frac{1}{\tan x}
\\ \\ \\
&\sin ^2{x} + \cos ^2{x} = 1
\\ \\
&1 + \tan ^2{x} = \sec ^2{x}
\\ \\
&1 + \cot ^2{x} = \csc ^2{x}
\\ \\ \\
&\tan{x} = \frac{\sin{x}}{\cos{x}}
\\ \\
&\cot{x} = \frac{\cos{x}}{\sin{x}}
\end{align*}
$$

$$
\begin{align*}
&\sin 2 \alpha=2 \sin \alpha \cos \alpha
\\ \\
&\cos 2 \alpha=\cos ^{2} \alpha-\sin ^{2} \alpha=1-2 \sin ^{2} \alpha=2 \cos ^{2} \alpha-1
\end{align*}
$$

$$
\begin{array}{l}
\sin (\alpha \pm \beta)=\sin \alpha \cdot \cos \beta \pm \cos \alpha \cdot \sin \beta 
\\ \\
\cos (\alpha \pm \beta)=\cos \alpha \cdot \cos \beta \mp\sin \alpha \cdot \sin \beta 
\\ \\
\tan (\alpha \pm \beta)=\frac{\tan \alpha \pm \tan \beta}{1 \mp \tan \alpha \cdot \tan \beta}
\end{array}
$$

## 极限的四则运算

![](../.gitbook/assets/image%20%2826%29.png)

## 基本无穷小量替换

**Can be only applied when x -&gt; 0**

> **实际上是由泰勒公式推导出来的。**

![](../.gitbook/assets/image%20%284%29.png)



$$
\lim _{x \rightarrow 1} \ln x \sim x-1
$$

## 泰勒公式\(Taylor's theorem\)

**Can be only applied when x -&gt; 0**

用来等价替换与抵消。

$$
\begin{array}{ll}
\sin x=x-\frac{x^{3}}{3 !}+o\left(x^{3}\right), & \cos x=1-\frac{x^{2}}{2 !}+\frac{x^{4}}{4 !}+o\left(x^{4}\right) \\ \\
\arcsin x=x+\frac{x^{3}}{3 !}+o\left(x^{3}\right), & \tan x=x+\frac{x^{3}}{3}+o\left(x^{3}\right) \\ \\
\arctan x=x-\frac{x^{3}}{3}+o\left(x^{3}\right), & \ln (1+x)=x-\frac{x^{2}}{2}+\frac{x^{3}}{3}+o\left(x^{3}\right) \\ \\
\mathrm{e}^{x}=1+x+\frac{x^{2}}{2 !}+\frac{x^{3}}{3 !}+o\left(x^{3}\right), & (1+x)^{\alpha}=1+\alpha x+\frac{\alpha(\alpha-1)}{2 !} x^{2}+o\left(x^{2}\right)
\end{array}
$$

## 例子

![](../.gitbook/assets/image%20%2825%29.png)

