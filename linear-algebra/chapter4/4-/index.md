# 1次独立

次に，1次結合について考察します。1次独立か1次従属かを判定できるようになることが目標です。まずは，1次結合の定義から見てみましょう。

<div class="def">
<p>
ベクトル空間 $V$ の ベクトル $\bm{v}_1,\bm{v}_2,\dots ,\bm{v}_k$ とスカラー $c_1,c_2,\dots ,c_k$ に対して，
$$
\bm{v}=c_1\bm{v}_1+c_2\bm{v}_2+\dots +c_k\bm{v}_k
$$
を $\bm{v}_1,\bm{v}_2,\dots ,\bm{v}_k$ の1次結合という。
</p>
</div>

<p>
ここで，1次結合が $\bm{0}$ に等しいとした関係式
$$
\bm{v}=c_1\bm{v}_1+c_2\bm{v}_2+\dots +c_k\bm{v}_k
$$
を考えてみます。
</p>

<div class="theorem">
<span class="theorem-title">定理4.1</span>
<p>
ベクトル空間 $V$ の部分空間 $W$ と，$V$ の零ベクトル $\bm{0}$ に対して，
$$\bm{0}\in W$$
が成り立つ。
</p>
</div>

<div class="eg-label">例１</div>
<div class="eg-text">
<p>
例
</p>
</div>

<div class="ex">
<span class="ex-circle1">れ</span><span class="ex-circle2">だ</span>
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

<div class="prob">
<span class="label">れんしゅう</span>
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