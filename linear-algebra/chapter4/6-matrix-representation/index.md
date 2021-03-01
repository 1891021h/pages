# 基底の変換

ベクトル空間の基底の取り方は一通りではありません。ここでは，何か２組の基底をとってきて，それらの関係を調べてみましょう。

$V$ を $n$ 次元ベクトル空間として，$\lbrc \bm{u}_1,\bm{u}_2,\ldots,\bm{u}_n\rbrc$ と $\lbrc \bm{v}_1,\bm{v}_2,\ldots,\bm{v}_n \rbrc$ を $V$ の２組の基底とします。基底のベクトルの個数は同じだったことに注意しましょう。そうすると，各 $\bm{u}_j \in V$ は $\bm{v}_1,\bm{v}_2,\ldots,\bm{v}_n$ の一次結合で（一意的に）表せて，以下のような関係式が得られます。

<div>
$$
\left\{
\begin{array}{llll}
    \bm{u}_1=p_{11}\bm{v}_1+p_{21}\bm{v}_2+\cdots +p_{n1}\bm{v}_n\cr
    \bm{u}_2=p_{12}\bm{v}_1+p_{22}\bm{v}_2+\cdots +p_{n2}\bm{v}_n\cr
    \quad\vdots\cr
    \bm{u}_n=p_{1n}\bm{v}_1+p_{2n}\bm{v}_2+\cdots +p_{nn}\bm{v}_n\cr
\end{array}
\right.
$$
</div>

となります。これを行列を使って，
<div>
$$
\begin{bmatrix}\bm{u}_1&\bm{u}_2&\cdots&\bm{u}_n\end{bmatrix}=
\begin{bmatrix}\bm{v}_1&\bm{v}_2&\cdots&\bm{v}_n\end{bmatrix}
    \begin{bmatrix}
        p_{11}&p_{12}&\cdots&p_{1n} \\
        p_{21}&p_{22}&\cdots&p_{2n} \\ 
        \vdots \\
        p_{n1}&p_{n2}&\cdots&p_{nn}
    \end{bmatrix}
$$
</div>
と書き表すことができます。

<div class="ex">
<span class="ex-circle1">例</span>
<p>
ベクトルの組
$$
\bm{u}_1=
    \left[
        \begin{array}{rrr}
            1 \\ 0 \\ 0
        \end{array}
    \right],
\bm{u}_2=
    \left[
        \begin{array}{rrr}
            0 \\ 1 \\ 1
        \end{array}
    \right],
\bm{u}_3=
    \left[
        \begin{array}{rrr}
            0 \\ -1 \\ 1
        \end{array}
    \right]
$$
と，
$$
\bm{v}_1=
    \left[
        \begin{array}{rrr}
            1 \\ 1 \\ 0
        \end{array}
    \right],
\bm{v}_2=
    \left[
        \begin{array}{rrr}
            -1 \\ 1 \\ 0
        \end{array}
    \right]
\bm{v}_3=
    \left[
        \begin{array}{rrr}
            0 \\ 0 \\ 1
        \end{array}
    \right]
$$
について，以下の問いに答えなさい。

$(1)$　$\lbrc \bm{u}_1,\bm{u}_2,\bm{u}_3\rbrc$ および $\lbrc \bm{v}_1,\bm{v}_2,\bm{v}_3\rbrc$ は $\bm{\rm R}^3$ の基底であることを確かめなさい。

$(2)$　$\lbrc \bm{u}_1,\bm{u}_2,\bm{u}_3\rbrc$ から $\lbrc \bm{v}_1,\bm{v}_2,\bm{v}_3\rbrc$ への基底の変換行列を求めなさい。
</p>
</div>