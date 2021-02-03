# 求极限的方法

## 洛必达法则 <a id="firstHeading"></a>

L'Hôpital's rule

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

### 基本恒等变形

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

### 基本无穷小量替换

![](../.gitbook/assets/image%20%284%29.png)



$$
\lim _{x \rightarrow 1} \ln x \sim x-1
$$

### 泰勒公式

用来等价替换与抵消。

$$
\begin{array}{ll}
\sin x=x-\frac{x^{3}}{3 !}+o\left(x^{3}\right), & \cos x=1-\frac{x^{2}}{2 !}+\frac{x^{4}}{4 !}+o\left(x^{4}\right) \\ \\
\arcsin x=x+\frac{x^{3}}{3 !}+o\left(x^{3}\right), & \tan x=x+\frac{x^{3}}{3}+o\left(x^{3}\right) \\ \\
\arctan x=x-\frac{x^{3}}{3 !}+o\left(x^{3}\right), & \ln (1+x)=x-\frac{x^{2}}{2}+\frac{x^{3}}{3}+o\left(x^{3}\right) \\ \\
\mathrm{e}^{x}=1+x+\frac{x^{2}}{2 !}+\frac{x^{3}}{3 !}+o\left(x^{3}\right), & (1+x)^{\alpha}=1+\alpha x+\frac{\alpha(\alpha-1)}{2 !} x^{2}+o\left(x^{2}\right)
\end{array}
$$



