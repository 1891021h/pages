# １次独立

次に，高校でも少し学んだベクトルの１次結合について議論します。

<div class="def">
<div class="def-label">定義</div>
<p>
ベクトル空間 $V$ のベクトル $\bm{v}_1,\bm{v}_2,\dots ,\bm{v}_k$ とスカラー $c_1,c_2,\dots ,c_k$ に対して，

$$
\bm{v}=c_1\bm{v}_1+c_2\bm{v}_2+\dots +c_k\bm{v}_k
$$

を $\bm{v}_1,\bm{v}_2,\dots ,\bm{v}_k$ の１次結合という。
</p>
</div>

<p>
ここで，１次結合が $\bm{0}$ に等しいとした次の関係式
$$
c_1\bm{v}_1+c_2\bm{v}_2+\dots +c_k\bm{v}_k=\bm{0}
$$
を考えてみます。
この関係式は，スカラーがすべて $0$，つまり $c_1=c_2=\cdots =c_k=0$ のときは必ず成り立ちます。この関係は当たり前なので，自明な１次関係式と呼ばれます。逆に，ここまでやらないと１次結合を $\bm{0}$ にできないような特別な場合に名前をつけてあげたのが，下の定義です。
</p>

<div class="def">
<div class="def-label">定義</div>
<p class="def-text">
$\bm{v}_1,\bm{v}_2,\dots ,\bm{v}_k \in V$ とスカラー $c_1,c_2,\dots ,c_k$ に対して，
$$
c_1\bm{v}_1+c_2\bm{v}_2+\dots +c_k\bm{v}_k=\bm{0}
$$
をみたすスカラー $c_1,c_2,\dots ,c_k$ は，
$$
c_1=c_2=\cdots =c_k=0
$$
に限るときに，$\bm{v}_1,\bm{v}_2,\dots ,\bm{v}_k$ は１次独立であるという。
</p>
</div>

<div class="eg-label">例4.4.1</div>
<div class="eg-text">
$V=\bm{\rm R}^3$ の基本ベクトル $\bm{e}_1,\bm{e}_2,\bm{e}_3$ は１次独立である。
$$
\bm{e}_1=
\begin{bmatrix} 1 \\ 0 \\ 0\\\end{bmatrix},
\bm{e}_2=
\begin{bmatrix} 0 \\ 1 \\ 0\\\end{bmatrix},
\bm{e}_3=
\begin{bmatrix} 0 \\ 0 \\ 1\\\end{bmatrix}
$$
実際，$c_1\bm{e}_1+c_2\bm{e}_2+c_3\bm{e}_3=\bm{0}$ が成り立つのは $c_1=c_2=c_3=0$ のときしかないことが（直観的に）わかる。  
</div>

１次独立でないとき，１次従属であるといいます。

