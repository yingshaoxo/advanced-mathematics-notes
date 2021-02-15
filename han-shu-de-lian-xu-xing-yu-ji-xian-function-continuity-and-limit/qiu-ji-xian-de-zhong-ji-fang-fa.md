# 求极限的终极方法

## 0：0 或者 无穷：无穷

$$
\frac{0}{0}\ or\ \frac{\infty}{\infty}
$$

### 如果有根号

想办法去掉根号

$$
\begin{aligned}
& \frac{\sqrt{a}-\sqrt{b}}{x} \\
=& \frac{(\sqrt{a}-\sqrt{b}) \cdot(\sqrt{a}+\sqrt{b})}{x} \\
=& \frac{a-b}{x}
\end{aligned}
$$

### 如果分母比分子复杂太多，倒换一下

分子和分母同时取-1次方，值不变

$$
\lim _{t \rightarrow+\infty} \frac{\mathrm{e}^{-t}}{t^{-50}}=\lim _{t \rightarrow+\infty} \frac{t^{50}}{\mathrm{e}^{t}}
$$

### 实在不行，用洛必达法则\(L'Hôpital's rule\)

两边同时求导，直到

* 分子或分母与x无关，比如都是常数的时候为止。
* 把x代入原式，得到常数为止。

## 无穷+-无穷 or 0+-无穷

### x趋向于正无穷

#### 有根号

类似的没有分母，或者分母不统一的式子，要通分

最简单的方法就是分母加个1，原值不变

$$
\begin{aligned}
& \lim _{x \rightarrow-\infty} x\left(\sqrt{x^{2}+100}+x\right) \\
=& \lim _{x \rightarrow-\infty} \frac{x\left(\sqrt{x^{2}+100}+x\right)}{1} \\
=& \lim _{x \rightarrow-\infty} \frac{\left(\sqrt{x^{2}+100}+x\right)}{1} \cdot \frac{\sqrt{x^{2}+100}-x}{\sqrt{x^{2}+100}-x} \\
=& \lim _{x \rightarrow-\infty} \times \frac{\left(x^{2}+100\right)-x^{2}}{\sqrt{x^{2}+100}-x} \\
=& \lim _{x \rightarrow-\infty} \frac{100 x}{\sqrt{x^{2}+100}-x}
\end{aligned}
$$

#### 无根号，但是有次数是1/x

做“倒代换”

$$
\begin{array}{l}
\lim _{x \rightarrow+\infty}\left[x^{2}\left(e^{\frac{1}{x}}-1\right)-x\right] \\
=\lim _{t \rightarrow 0^{+}} \frac{1 \cdot\left(e^{t}-1\right)}{t^{2}}-\frac{1}{t} \\
=\lim _{t \rightarrow 0^{+}} \frac{e^{t}-1-t}{t^{2}}
\end{array}
$$

### x趋向于负无穷

由于我们更习惯做正无穷的题，所以我们令t=-x

$$
\begin{aligned}
& \lim _{x \rightarrow-\infty} \frac{100 x}{\sqrt{x^{2}+100}-x} \\
=& \lim _{t \rightarrow \infty} \frac{-100 t}{\sqrt{t^{2}+100}+t} \\
=& \lim _{t \rightarrow \infty} \frac{-100 t}{t\left(\sqrt{\frac{t^{2}+10^{0}}{t^{2}} t^{2}}+1\right)} \\
=& \operatorname{lin}_{t \rightarrow \infty} \frac{-100}{\sqrt{1+\frac{100}{t^{2}}}+1}
\end{aligned}
$$

## 遇到带有取整符号的式子

一般使用，夹逼准则+放缩法

$$
\frac{10}{x}-1<\left[\frac{10}{x}\right] \leqslant \frac{10}{x}
$$

### 若x-&gt;0-，则lim \[x\] = -1

## 无穷的0次方

$$
\infty ^ 0
$$

$$
a^{b} \Rightarrow e^{b \cdot \ln (a)}
$$

$$
\begin{aligned}
& \lim _{x \rightarrow+\infty}\left(x+\sqrt{1+x^{2}}\right)^{\frac{1}{x}} \\
=& e^{\lim _{x \rightarrow+\infty} \frac{1}{x} \cdot \ln \left(x+\sqrt{1+x^{2}}\right)} \\
=& e^{\lim _{x \rightarrow+\infty} \frac{\sqrt{1+x^{2}}}{1}} \\
=& e^{0} \\
=& 1
\end{aligned}
$$

## 1的无穷次方

$$
1^\infty
$$

![](../.gitbook/assets/image%20%2828%29.png)

