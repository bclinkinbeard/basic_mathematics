# Typesetting Mathematics

[Literasee](http://literasee.io) (via the [Kramdown](http://kramdown.gettalong.org/) markdown interpreter) 
includes [MathJax](https://www.mathjax.org/) which provides 
typeset quality mathematics as part of any web-based content one produces.

## In-line math:

The cube root of $x$ is denoted $\sqrt[3]{x}$.

In-line summation notation: $\sum\_{i=1}^n x\_{i} = x\_1 + x\_2 + \cdots + x\_n$.


## Centered math:

Basic limit notation:

$$
\lim\_{n \rightarrow \infty} \frac{2n + 5}{n} = 2
$$

Stokes Theorem: 

$$
\int\_{\partial \Omega} = \int\_\Omega d\omega
$$

Three parameter logistic IRT model:

$$
p\_i (\theta) = c\_i + {1 - c\_i \over 1 + e^{-a\_i(\theta - b\_i)}}
$$

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


### AMS LaTeX 

MathJax supports AMS-LaTeX:

Bulletin Board Font: $\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$
