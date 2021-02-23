# ベクトル空間

まずは，ベクトル空間の定義について学びます。

<div class="def">
<p>
空でない集合 $V$ に，和 $\bm{x}+\bm{y}$ およびスカラー倍 $c\bm{x}$ という演算が定義されていて，次の①～⑧が成り立つとき，$V$ はベクトル空間であるという。<br>
①　和に関する交換法則：$\bm{x}+\bm{y}=\bm{y}+\bm{x}$ <br>②　和に関する結合法則：$(\bm{x}+\bm{y})+\bm{z}=\bm{x}+(\bm{y}+\bm{z})$<br>③　零ベクトル：$\bm{x}+\bm{0}=\bm{0}+\bm{x}=\bm{0}$<br>④　逆ベクトル：$\bm{x}+\bm{x'}=\bm{x'}+\bm{x}$<br>⑤　スカラー倍に関する結合法則：$(ab)\bm{x}=a(b\bm{x})$<br>⑥　単位元：$1\bm{x}=\bm{x}$<br>⑦　スカラーに関する分配法則：$(a+b)\bm{x}=a\bm{x}+b\bm{x}$<br>⑧　ベクトルに関する分配法則：$a(\bm{x}+\bm{y})=a\bm{x}+a\bm{y}$
</p>
</div>

<div class="eg-label">例１</div>
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

<div class="prob">
<span class="prob-label">れんしゅう</span>
<p>
実数を係数とする高々 $n$ 次の多項式全体を $R[x]_n$ と書くことにする。 いま，$n=2$ として $R[x]_2$ について考える。 

$(1)$　$R[x]_2$ の和とスカラー倍の定義を記せ。

$(2)$　$(1)$ の定義によって，$R[x]_2$ がベクトル空間となっていることを確かめよ。
</p>
</div>

<div class="theorem">
<span class="theorem-title">定理4.1</span>
<p>ここに定理が入ります。いけてる</p>
</div>