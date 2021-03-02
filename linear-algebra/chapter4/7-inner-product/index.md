# 内積

<div class="def">
<p class="def-text">
$\bm{\rm R}$ 上のベクトル空間 $V$ のベクトル $\bm{x},\bm{y}$ に対して，実数 $\langle \bm{x},\bm{y} \rangle$ を対応させる対応づけ $\langle\,,\,\rangle$ が次の①～④を満たすとき，この対応を $V$ の内積という。

①　$\ip{\bm{x}}{\bm{x}}\geqq 0$ であり，等号は $\bm{x}=\bm{0}$ のときのみ成立する。
②　$\ip{\bm{x}}{\bm{y}}=\ip{\bm{y}}{\bm{x}}$
③　$\ip{\bm{x}+\bm{y}}{\bm{z}}=\ip{\bm{x}}{\bm{z}}+\ip{\bm{y}}{\bm{z}}$
④　$\ip{r\bm{x}}{\bm{y}}=r\ip{\bm{x}}{\bm{y}}$

内積が定義されたベクトル空間を，計量ベクトル空間という。
</p>
</div>

<div class="eg-label">例4.7.1</div>
<div class="eg-text">
<div class="eg-title">(標準内積)</div>
$\bm{\rm R}^n$ のベクトル $\bm{x}=\begin{bmatrix}x_1\\ x_2\\ \vdots\\ x_n \end{bmatrix}$ と $\bm{y}=\begin{bmatrix}y_1\\ y_2\\ \vdots\\ y_n \end{bmatrix}$ に対して，

$$
\begin{eqnarray}
    \ip{x}{y}&=&x_1y_1+x_2y_2+\cdots+x_ny_n\notag\cr
    &=&\sum_{k=1}^{n}{x_ky_k}\notag\cr
    &=&\bm{x}^\mathsf{T}\bm{y}\notag
\end{eqnarray}
$$
</div>

と定義すると，これは $\bm{\rm R}^n$ の内積である。

$\because$

<div class="ex">
<span class="ex-circle1">例</span>
<p>

$\bm{x}=\begin{bmatrix}x_1\cr x_2\end{bmatrix},\bm{y}=\begin{bmatrix}y_1\cr y_2\end{bmatrix}\in\bm{\rm R}^2$ に対して，
$$
\ip{\bm{x}}{\bm{y}}=x_1y_1+2x_2y_2
$$
と定めると，これは $\bm{\rm R}^2$ の内積であることを示しなさい。
</p>
</div>

<div class="prob">
<span class="prob-label">練習</span>
<p>

$a<b$ とし，$C[a,b]$ を区間 $[a,b]$ で連続な実数値関数全体からなるベクトル空間とする。このとき，$f,g\in C[a,b]$ に対して
$$
\ip{f}{g}=\int_a^bf(x)g(x)dx
$$
と定義すると，$\ip{f}{g}$ は $C[a,b]$ の内積であることを示しなさい。
</p>
</div>