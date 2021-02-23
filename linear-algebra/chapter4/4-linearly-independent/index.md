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
この関係式（１次関係という）は，スカラーがすべて $0$，つまり $c_1=c_2=\cdots =c_k=0$ のときは必ず成り立ちます。この関係は当たり前なので，自明な１次関係と呼ばれます。逆に，ここまでやらないと１次結合を $\bm{0}$ にできないような特別な場合に名前をつけてあげたのが，下の定義です。
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

<p>
１次独立でないとき，１次従属であるといいます。つまり少なくとも１つは $0$ でないスカラー $c_1,c_2,\dots ,c_k$ によって
$$
c_1\bm{v}_1+c_2\bm{v}_2+\dots +c_k\bm{v}_k=\bm{0}
$$
が成り立つとき，$\bm{v}_1,\bm{v}_2,\dots ,\bm{v}_k$ は１次従属です。このときは，$\bm{v}_1,\bm{v}_2,\dots ,\bm{v}_k$ の少なくとも１つが他のベクトルの１次結合で書けることになります。たとえば $c_2 \neq 0$ なら，
$$
\bm{v}_2=-\frac{c_1}{c_2}\bm{v}_1-\frac{c_3}{c_2}\bm{v}_3-\cdots -\frac{c_k}{c_2}\bm{v}_k
$$
といった具合です。
</p>

<div class="theorem">
<span class="theorem-title">定理4.4</span>
<p>

</p>
</div>

ここで，頻出の重要な例題をやってみます。
<div class="ex">
<span class="ex-circle1">例</span>
<p>
次のベクトルの組は１次独立であるかどうか判定し，１次従属ならば非自明な１次関係を１つ挙げよ。

$(1)$
<p>
$$
\bm{v}_1=
\left[ \begin{array}{rrr} 1\\2\\1 \end{array} \right],
\bm{v}_2=
\left[ \begin{array}{rrr} 1\\-1\\1 \end{array} \right],
\bm{v}_3=
\left[ \begin{array}{rrr} 1\\1\\-2 \end{array} \right]
$$
</p>

$(2)$
<p>
$$
\bm{v}_1=
\left[ \begin{array}{rrr} 1\\1\\1 \end{array} \right],
\bm{v}_2=
\left[ \begin{array}{rrr} 1\\2\\3 \end{array} \right],
\bm{v}_3=
\left[ \begin{array}{rrr} 1\\0\\-1 \end{array} \right]
$$
</p>
</p>
</div>

<div class="prob">
<span class="prob-label">練習</span>
<p>
次のベクトルの組は１次独立であるかどうか判定し，１次従属ならば非自明な１次関係を１つ挙げよ。

$(1)$
<p>
$$
\bm{v}_1=
\left[ \begin{array}{rrr} 3\\1\\2 \end{array} \right],
\bm{v}_2=
\left[ \begin{array}{rrr} 2\\-1\\1 \end{array} \right],
\bm{v}_3=
\left[ \begin{array}{rrr} -1\\1\\-1 \end{array} \right],
\bm{v}_4=
\left[ \begin{array}{rrr} 3\\2\\1 \end{array} \right]
$$
</p>
$(2)$
<p>
$$
\bm{v}_1=
\left[ \begin{array}{rrrr} 1\\2\\3\\-1 \end{array} \right],
\bm{v}_2=
\left[ \begin{array}{rrrr} 2\\1\\0\\2 \end{array} \right],
\bm{v}_3=
\left[ \begin{array}{rrrr} 1\\0\\-1\\3 \end{array} \right]
$$
</p>
</p>
</div>