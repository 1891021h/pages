# １次独立なベクトルの最大個数
<p>
ベクトルの組の中から１次独立なベクトルを選んで抜き出してくることを考えるとき，<b>最大で</b>何個抜き出せるか調べてみましょう。最初に，１次独立なベクトルの最大個数の定義を示します。
</p>

<div class="def">
<p class="def-text">
ベクトルの組の中に $r$ 個の１次独立なベクトルがあり，どの $r+1$ 個のベクトルも１次従属であるとき，１次独立なベクトルの最大個数が $r$ であるという。
</p>
</div>

これが定義ですが，直接的には次の定理を使って問題を解くことになります。
<div class="theorem">
<span class="theorem-title">定理3.1</span>
<p>
$\left\{\bm{v}_1,\bm{v}_2, \ldots ,\bm{v}_k\right\}$ の１次独立な最大個数が $r$ である
<p>
$\iff$　$\left\{\bm{v}_1,\bm{v}_2, \ldots ,\bm{v}_k\right\}$ の中に $r$ 個の１次独立なベクトルがあり，他の $m-r$ 個のベクトルはこの $r$ 個のベクトルの１次結合で書ける。
</p>
</p>
</div>

<div class="ex">
<span class="ex-circle1">例</span>
<p>
次のベクトルの組の中から，最大個数の１次独立なベクトルの組を抜き出しなさい。また，他のベクトルを，抜き出したベクトルの１次結合で表しなさい。

$$
\bm{v}_1=
\left[ \begin{array}{rrrr} 1\cr1\cr3\cr0 \end{array} \right],
\bm{v}_2=
\left[ \begin{array}{rrrr} 1\cr2\cr0\cr-1 \end{array} \right],
\bm{v}_3=
\left[ \begin{array}{rrrr} 1\cr3\cr-3\cr-2 \end{array} \right],
\bm{v}_4=
\left[ \begin{array}{rrrr} -2\cr4\cr1\cr-1 \end{array} \right],
\bm{v}_5=
\left[ \begin{array}{rrrr} -1\cr-4\cr7\cr0 \end{array} \right]
$$

</p>
</div>

自分の選んだ抜き出し方が最大個数となる抜き出し方になっているか，釈然としない人もいるかもしれません。しかし，定理3.1により，残りのベクトルが抜き出したベクトルの１次結合で表されることを確かめれば，最大個数であることが保証されます。
定理として述べておきましょう。

<div class="theorem">
<span class="theorem-title">定理3.2</span>
<p>
$\left\{\bm{v}_1,\bm{v}_2, \ldots ,\bm{v}_k\right\}$ から最大個数の１次独立なベクトルを抜き出すには，<br>

①　各ベクトルを列ベクトルとする行列 $A$ を階段行列に変形する。

②　その階段行列において主成分を持つ列の列ベクトルを抜き出す。

</p>
</div>