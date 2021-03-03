# ベクトル空間

まずは，ベクトル空間の定義について学びます。

<div class="def">
<p>
集合 $V$ は空集合ではないとする。任意の $\bm{x},\bm{y}\in V$ と任意の $c \in K$ に対して，
和 $\bm{x}+\bm{y}$ およびスカラー倍 $c\bm{x}$ という演算が定義されていて，次の①～⑧が成り立つとき，$V$ はベクトル空間であるという。
<div style="padding-left:1rem;">
①　和に関する交換法則<br>　　$\bm{x}+\bm{y}=\bm{y}+\bm{x}$<br>

②　和に関する結合法則<br>　　$(\bm{x}+\bm{y})+\bm{z}=\bm{x}+(\bm{y}+\bm{z})$

③　零ベクトル<br>　　$\bm{x}+\bm{0}=\bm{0}+\bm{x}=\bm{0}$

④　逆ベクトル<br>　　$\bm{x}+\bm{x'}=\bm{x'}+\bm{x}$

⑤　スカラー倍に関する結合法則<br>　　$(ab)\bm{x}=a(b\bm{x})$

⑥　単位元<br>　　$1\bm{x}=\bm{x}$

⑦　スカラーに関する分配法則<br>　　$(a+b)\bm{x}=a\bm{x}+b\bm{x}$

⑧　ベクトルに関する分配法則<br>　　$a(\bm{x}+\bm{y})=a\bm{x}+a\bm{y}$
</div>
</p>
</div>

<div class="eg-label">例 4.1.1</div>
<div class="eg-text">
<p>
$n$ 次の列ベクトルの集合
$$
\bm{\rm R}^n
=\left\{
	\bm{x}=
	\begin{bmatrix}
		x_1 \\ \vdots \\ x_n
	\end{bmatrix}
	\ \middle| \ 
	a_i \in \bm{\rm R}, 1 \leq i \leq n
\right\}
$$
は，ふつうの行列の和とスカラー倍の定義によってベクトル空間となる。
</p>
<p>
とくに $\bm{\rm R}^2
\equiv \left\{
	\, (x,y)
	\, \middle| \, 
	x,y\in \bm{\rm R}\ 
\right\}
$ は，よく知っている $xy$ 平面と同じものであると考えることができる。
</p>
</div>

<div class="ex">
<span class="ex-circle1">例</span>
<p>
$\bm{\rm R}^3
=\left\{
	\begin{bmatrix}
		x\\y\\z
	\end{bmatrix}
	\middle|
	\ x,y,z\in \bm{\rm R} 
\right\}$ について，以下の各問いに答えよ。

$(1)$　和とスカラー倍の定義を記せ。

$(2)$　$(1)$ の定義によって，$\bm{\rm R}^3$ がベクトル空間となっていることを確めよ（性質①～⑧を満たすことを示せ）。 
</p>
</div>

解答

$(1)$

自然な和とスカラー倍の定義は，任意の
$\bm{x}=\begin{bmatrix}x_1 \cr x_2\cr x_3\end{bmatrix}, \bm{y}=\begin{bmatrix}y_1\cr y_2\cr y_3\end{bmatrix},\bm{z}=\begin{bmatrix}z_1\cr z_2\cr z_3\end{bmatrix}\in \bm{\rm R}^3$ と任意の $a,b\in K$ に対して，

$$
\begin{array}{ll}
\bm{x}+\bm{y} = \begin{bmatrix}x_1 \cr x_2\cr x_3\end{bmatrix}+\begin{bmatrix}y_1\cr y_2\cr y_3\end{bmatrix} 
\stackrel{\mathrm{def}}{=}
\begin{bmatrix}x_1+y_1 \cr x_2+y_2\cr x_3+y_3\end{bmatrix}\cr
c\bm{x}=c\begin{bmatrix}x_1 \cr x_2\cr x_3\end{bmatrix}
\stackrel{\mathrm{def}}{=}
\begin{bmatrix}cx_1 \cr cx_2\cr cx_3\end{bmatrix}
\end{array}
$$

$(2)$
いけてへん

<div class="prob">
<span class="prob-label">れんしゅう</span>
<p>
実数を係数とする高々 $n$ 次の多項式全体を $R[x]_n$ と書くことにする。 いま，$n=2$ として $R[x]_2$ について考える。 

$(1)$　$R[x]_2$ の和とスカラー倍の定義を記せ。

$(2)$　$(1)$ の定義によって，$R[x]_2$ がベクトル空間となっていることを確かめよ。
</p>
</div>