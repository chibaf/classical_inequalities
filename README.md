# classical inequalities

Hardy's inequality

$$
\int^\infty_0|f(t)|^p dt \ge\left(1-\frac{1}{p}\right)^p\int^\infty_0\left(\frac{1}{t}\int^\infty_0|f(x)|dx\right)^p dt
$$


Hardy's inequality differential type

$$
\int^\infty_0|u'(t)|^p dt \ge \left(1-\frac{1}{p}\right)^p\int^\infty_0\frac{|u(t)|^p}{t^p}dt
$$

Hardy, Littlewood, Polya

$$
\int^\infty_0f(t)^pt^{p-r} dt\ge \left(\frac{|r-1|}{p}\right)^p\int^\infty_0F(t)^pt^{-r}dt
$$

where

$$
F(t)=
\begin{array}{ll}
\int^t_0 f(s)ds, & r>1 \\
\\
\int^\infty_0 f(s)ds, & r<1
\end{array}
$$

Hardy's inequality discrete type

$$
\sum^\infty_{n=1} x^p_n \ge \left(1-\frac{1}{p}\right)^p\sum^\infty_{n=1}\left(\frac{x_1+x_2+\cdots+x_n}{n}\right)^p
$$

weighted one dimensional hardy's inequality power type (1)

$$
1< p <\infty \;\; {\rm and} \;\; \alpha< 1-1/p
$$

$$
\int^\infty_0\left |u'(t)\right|^p t^{\alpha t}dt \ge \left(1-\alpha-\frac{1}{p}\right)^p\int^\infty_0 \left |u(t)\right|^p t^{(\alpha-1)p}dt
$$

weighted one dimensional hardy's inequality power type (2)

$$
1< p <\infty \;\; {\rm and} \;\; \alpha> 1-1/p
$$

$$
\int^\infty_0\left |u'(t)\right|^p t^{\alpha t}dt \ge \left(\alpha-1+\frac{1}{p}\right)^p\int^\infty_0 \left |u(t)\right|^p t^{(\alpha-1)p}dt
$$

weighted one dimensional hardy's inequality integral type (1)

$$
1< p <\infty \;\; {\rm and} \;\; \alpha< 1-1/p
$$
$$
\int^\infty_0\left |f(t)\right|^p t^{\alpha p}dt \ge \left(1-\alpha-\frac{1}{p}\right)^p\int^\infty_0\left(\int_0^t \left |f(x)\right|dx\right)^p t^{(\alpha-1)p}dt
$$

weighted one dimensional hardy's inequality power type (2)

$$
1< p <\infty \;\; {\rm and} \;\; \alpha> 1-1/p
$$
$$
\int^\infty_0\left |f(t)\right|^p t^{\alpha t}dt \ge \left(\alpha-1+\frac{1}{p}\right)^p\int^\infty_0\left(\int^\infty_t\left|f(x)\right|dx\right)^p t^{(\alpha-1)p}dt
$$

weighted hardy's inequality; $C$ is independent of $u(t)$

$$
\int^\infty_0\left|u'(t)\right|^p w(t)^pdt \ge C \int^\infty_0\left|u(t)\right|^p v(t)^p dt \quad {\rm for} \; v(t)\ge 0,\;w(t)\ge 0
$$

Hardy-Sobolev inequality; $C$ is independent of $u(t)$

$$
\int^\infty_0\left|u'(t)\right|^p w(t)^pdt \ge C \left(\int^\infty_0\left|u(t)\right|^q v(t)^q dt \right)^{p/q} \quad {\rm for} \; 1 < p \le q < +\infty
$$

When 

$$
1<p\le q<\infty,\;p'=p/(p-1),\;\int^\infty_0|v(x)|dx<\infty,\;\int^\infty_0|w(x)|dx<\infty
$$

Then the following two statements (1) and (2) are equivalent

(1) when

$$
\int^\infty_0|f(x)|^pw(x)^p dx<\infty
$$

Then

$$
\int^\infty_0|f(x)|^p w(t)^p dt \ge C_1\left(\int^\infty_0\left|\int^t_0|f(x)|dx\right|^q w(t)^q dt\right)^{p/q}
$$

$$
\frac{1}{C_1}:=\sup_{t>0}\left(\int^\infty_t v(s)^q ds\right)^{p/q}\left(\int^t_0 w(s)^{-p'}\right)^{p-1}<\infty
$$

there is a constant $C_1$ which is independent of $f(t)$

(2)

$$
\frac{1}{C_1}:=\sup_{t>0}\left(\int^\infty_t v(s)^q ds\right)^{p/q}\left(\int^t_0 w(s)^{-p'}\right)^{p-1}<\infty
$$

where

$$
0<C_2\le \infty,\; 1/\infty=0
$$

(3) When $C_1$ the best constant satisfying (2)

Then

$$
\left(q^{p/q}(q'^{p-1})\right)^{-1}C_2 \le C_1 \le C_2,\quad q'=q/(q-1)
$$



## references
古典的不等式の精密化、堀内利郎、内田老鶴圃、２０２３ 
http://www.rokakuho.co.jp/data/books/0088.html

TeX2img Website
https://tex2img.tech/index.en.html
