# 部分空間

次に，部分空間の定義について学びます。

<div class="def">
<p>
ベクトル空間 $V$ の空でない部分集合が次の①,②をみたすとき，$W$ を $V$ の部分空間という。

①　$\bm{x},\bm{y}\in W$ に対して，$\bm{x}+\bm{y}\in W$<br>
②　$\bm{x}\in W,r\in \bm{\rm K}$ に対して，$r\bm{x}\in W$
</p>
</div>

<p>
次の定理は問題を解くときによく使います。
</p>

<div class="theorem">
<span class="theorem-number">定理4.1</span>
<p>
<span class="thorem-title">($\bm{0}$ と部分空間)</span>

ベクトル空間 $V$ の部分空間 $W$ と，$V$ の零ベクトル $\bm{0}$ に対して，
$$\bm{0}\in W$$
が成り立つ。
</p>
</div>

<div class="ex">
<span class="ex-circle1">例</span>
<p>
次の $\bm{\rm R}^2$ の部分集合 $W_1,W_2$ は $\bm{\rm R}^2$ の部分空間であるか，それぞれ調べよ。
<p>
$(1)　
W_1
=\left\{
	\begin{bmatrix}
		x\\y
	\end{bmatrix}
	\middle|
	\ x-y=0 
\right\}$
</p>
<p>
$(2)　
W_2
=\left\{
	\begin{bmatrix}
		x\\y
	\end{bmatrix}
	\middle|
	\ x+y=1 
\right\}$
</p>
</p>
</div>

解答

$(1)$

空集合でないことの確認（定理の確認）

$\bm{0}=\begin{bmatrix}0 \cr 0\end{bmatrix}$ とすると，$0-0=0$ より $\bm{0}\in W$。したがって空集合でない。

①の確認：

$\bm{v}_1=\begin{bmatrix}x_1 \cr y_1\end{bmatrix},\bm{v}_2=\begin{bmatrix}x_2 \cr y_2\end{bmatrix}\in W$ とすると，
$\bm{v}_1+\bm{v}_2=\begin{bmatrix}x_1+x_2 \cr y_1+y_2\end{bmatrix}$で，
$(x_1+x_2)-(y_1+y_2)=(x_1-y_1)+(x_2-y_2)=0+0=0$
より，$\bm{v}_1+\bm{v}_2\in W$

②の確認：

$\bm{v}=\begin{bmatrix}x \cr y\end{bmatrix}\in W,c\in \bm{\rm R}$ とすると，
$c\bm{v}=\begin{bmatrix}cx \cr cy\end{bmatrix}$ で，
$cx-cy=c(x-y)=c\cdot 0=0$ より，$c\bm{v}\in W$

$(2)$

定理4.1.1から，もし $W$ が $\bm{\rm R}^2$ の部分空間ならば，$W$ は $\bm{\rm R}^2$ の零ベクトル $\bm{0}=\begin{bmatrix}0 \cr 0\end{bmatrix}$ を含まなければならない。しかし，$0+0=0\neq 1$ だから $\bm{0}\notin W$ である。よって $W$ は $\bm{\rm R}^2$ の部分空間ではない。

<div class="prob">
<span class="prob-label">練習</span>
<p>
次の $R[x]_3$ の部分集合 $W_1,W_2$ は $R[x]_3$ の部分空間であるか，それぞれ調べよ。 
</p>
<p>
$(1)$　$W_1= \left \{\ f(x) \in R[x]_3 \ \middle| \ f'(x)=1 \ \right\}$
</p>
<p>
$(2)$　$W_2= \left \{\ f(x) \in R[x]_3 \ \middle| \ \displaystyle \int_{0}^{1}{f(x)}=0 \ \right\}$
</p>
</div>