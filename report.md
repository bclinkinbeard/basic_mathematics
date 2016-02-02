# Typesetting Mathematics

[Literasee](http://literasee.io) (via the [marked](https://github.com/chjj/marked) markdown interpreter)
includes [MathJax](https://www.mathjax.org/) which provides typeset quality mathematics as part of any web-based content one produces. Mathematics is included via standard [TeX/LaTeX](https://www.latex-project.org/) markup. Dozens of examples follow showing
just how much is possible (don't forget to view the [source](https://raw.githubusercontent.com/Literasee/basic_mathematics/master/report.md)).

## In-line math:

The cube root of $x$ is denoted $\sqrt[3]{x}$.

Let $x\_i = i$, then $\sum\_{i=1}^n x\_{i} = x\_1 + x\_2 + \cdots + x\_n = n(n-1)/2$.

Using L'Hôpital's rule one can easily show that $\lim\_{n \rightarrow \infty} \frac{2n + 5}{n} = 2$.

The Continuum Hypothesis (assuming the Axiom of Choice) can be stated as: $2^{\aleph\_0} = \aleph\_1$


## Centered math:

#### Basic limit notation:

$$
\lim\_{n \rightarrow \infty} \frac{2n + 5}{n} = 2
$$

#### Stokes Theorem:

$$
\int\_{\partial \Omega} = \int\_\Omega d\omega
$$

#### Three parameter logistic IRT model:

$$
p\_i (\theta) = c\_i + {1 - c\_i \over 1 + e^{-a\_i(\theta - b\_i)}}
$$

#### A Cross Product Formula

$$\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\\\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\\\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0
\end{vmatrix}  $$

#### The Cauchy-Schwarz Inequality

$$\displaystyle \left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$


## Aligned equations:

$\begin{align} f(x) & = (a+b)^2 \\\\ & = a^2+2ab+b^2 \\\\ \end{align}$

$\begin{align} MSE(\hat{\theta}) & = \mathbb{E}[(\hat{\theta} - \theta)^2] \\\\ & = \dfrac{1}{n} \sum\limits\_{i=1}^n (\widehat{\theta}\_{i} - \theta\_i)^2 \\\\ \end{align}$


### Matrices:

$\left( \begin{matrix} a & b \\\\ c & d \end{matrix} \right) \left( \begin{matrix} 0 \\\\ 1 \end{matrix} \right) = \left( \begin{matrix} b \\\\ d \end{matrix} \right)$

$\left( \begin{matrix} 1 & 2 & \cdots & 10 \\\\ 2 & 3 & \cdots & 11 \\\\ \vdots & \vdots & \ddots & \vdots \\\\ 10 & 11 & \cdots & 20 \end{matrix} \right)$



### Conditional equations:

$$f(x) = \begin{cases}1 & -1 \le x < 0 \\\\ \frac{1}{2} & x = 0 \\\\ 1 - x^2 & \text{otherwise} \end{cases}$$


### Mixtures of inline and centered mathematics:

When $a \ne 0$, there are two solutions to the quadratic equation $ax^2 + bx + c = 0$ and they are

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

The _Golden Ratio_ is an irrational number equal to $\frac{1 + \sqrt{5}}{2}$. The ratio, often expressed as $\varphi$, can be expressed as a continued fraction as follows:

$$\textrm{Golden Ratio} \equiv \varphi=1+\cfrac1{1+\cfrac1{1+\cfrac1{1+\cfrac1{1+\ddots}}}}$$

### Numerous Math fonts

Bulletin Board font: $\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$

Math bold font: $\mathbf{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$

Math typewriter font: $\mathtt{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$

Math sans-serif font: $\mathsf{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$

Math Roman font: $\mathrm{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$

Math calligraphic letters: $\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ}$

Math script letters: $\mathscr{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ}$

Math "fraktur" (old German) letters: $\mathfrak{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$
