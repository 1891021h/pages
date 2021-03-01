# たくさんの一次結合の書き方

ベクトル $\bm{u}_1,\bm{u}_2,\ldots,\bm{u}_n$ を，ベクトル $\bm{v}_1,\bm{v}_2,\ldots,\bm{v}_m$ の一次結合で表すことを考えます。まず愚直に書き並べてみると，

<div>
$$
\left\{
\begin{array}{llll}
    \bm{u}_1=p_{11}\bm{v}_1+p_{21}\bm{v}_2+\cdots +p_{m1}\bm{v}_m\cr
    \bm{u}_2=p_{12}\bm{v}_1+p_{22}\bm{v}_2+\cdots +p_{m2}\bm{v}_m\cr
    \quad\vdots\cr
    \bm{u}_n=p_{1n}\bm{v}_1+p_{2n}\bm{v}_2+\cdots +p_{mn}\bm{v}_m\cr
\end{array}
\right.
$$
</div>

となります。これを，

<div>
$$
\left\{
\begin{array}{cccc}
\bm{u}_1=
\begin{bmatrix}\bm{v}_1&\bm{v_2}&\cdots&\bm{v}_m\end{bmatrix}
\left[
    \begin{array}{cccc}
        p_{11} \cr p_{21} \cr \vdots \cr p_{m1}
    \end{array}
\right]\cr
\bm{u}_2=
\begin{bmatrix}\bm{v}_1&\bm{v_2}&\cdots&\bm{v}_m\end{bmatrix}
\left[
    \begin{array}{cccc}
        p_{12} \cr p_{22} \cr \vdots \cr p_{m2}
    \end{array}
\right]\cr
\vdots\cr
\bm{u}_n=
\begin{bmatrix}\bm{v}_1&\bm{v_2}&\cdots&\bm{v}_m\end{bmatrix}
\left[
    \begin{array}{cccc}
        p_{1n} \cr p_{2n} \cr \vdots \cr p_{mn}
    \end{array}
\right]
\end{array}
\right.
$$
</div>
と書きなおしましょう。

最後に，これを縦ではなく横に $\begin{bmatrix}\bm{u}_1&\bm{u}_2&\cdots&\bm{u}_n\end{bmatrix}$ と並べましょう。このようにすると，行列を使って，
<div>
$$
\begin{bmatrix}\bm{u}_1&\bm{u}_2&\cdots&\bm{u}_n\end{bmatrix}=
\begin{bmatrix}\bm{v}_1&\bm{v}_2&\cdots&\bm{v}_m\end{bmatrix}
    \begin{bmatrix}
        p_{11}&p_{12}&\cdots&p_{1n} \\
        p_{21}&p_{22}&\cdots&p_{2n} \\ 
        \vdots \\
        p_{n1}&p_{n2}&\cdots&p_{mn}
    \end{bmatrix}
$$
</div>
と書き表すことができます。