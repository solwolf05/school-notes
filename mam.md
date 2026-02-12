# Mathematical Methods

## Unit 1

### Rationalising the Denominator

Use difference of two squares.

$$
a^2-b^2 = (a+b)(a-b)
$$

Example:

$$
\begin{align}
&\frac{1}{1 + \sqrt{ 2 }} \\
= &\frac{1}{1 + \sqrt{ 2 }} \cdot \frac{1 - \sqrt{ 2 }}{1-\sqrt{ 2 }} \\
= &\frac{1-\sqrt{ 2 }}{-1} \\
= &\sqrt{ 2 } - 1
\end{align}
$$

### Solving Quadratic Equations

$$
ax^2+bx+c
$$

#### Easy Way

##### Monic

Factors of $c$ that add to $b$.

$$
\begin{align}
&x^2 + 7x + 12 = 0 \\
&(x + 3)(x + 4) = 0 \\
&x = -3 \\
&x = -4
\end{align}
$$

##### Non-Monic

Factors of $c + a$ that add to $b$.

$$
\begin{align}
&2x^2 + 7x + 6 = 0 \\
&2x^2 + 4x + 3x + 6 = 0 \\
&2x(x + 2) + 3(x + 2) = 0 \\
&(2x + 3)(x + 2) = 0 \\
&x = -\frac{3}{2} \\
&x = -2
\end{align}
$$

#### Completing the Square

##### Monic

1. Add $\frac{b}{2}^2$ and $-\frac{b}{2}^2$ to the expression
2. Turn the $x$'s into a big square
3. Simplify
4. Add the leftovers
5. Solve

$$
\begin{align}
&x^2 - 4x + 5 = 0 \\
\text{1. \hspace{1.5em}} &x^2 - 4x + \left( \frac{4}{2} \right)^2 + 5 - \left( \frac{4}{2} \right)^2 = 0 \\
\text{2. \hspace{1.5em}} &\left( x - \frac{4}{2} \right)^2 + 5 - \left( \frac{4}{2} \right)^2 = 0 \\
\text{3. \hspace{1.5em}} &\left( x - 2 \right)^2 + 5 - 2 = 0 \\
\text{3. \hspace{1.5em}} &\left( x - 2\right)^2 + 3 = 0 \\
\text{4. \hspace{1.5em}} &\left( x - 2 \right)^2 = -3 \\
&x - 2 = \pm \sqrt{ -3 } \\
&x = 2 \pm \sqrt{ -3 } \\
\end{align}
$$

##### Non-Monic

1. Factorise
2. Same as monic

$$
\begin{align}  
&3x^2 + 2x + 3 = 0 \\
\text{1.\hspace{1.5em}} &3\left(x^2 + \frac{2}{3}x + 1\right) = 0\\
\text{2.\hspace{1.5em}} &3\left( x^2 + \frac{2}{3}x + \left( \frac{1}{3} \right)^2 + 1 - \left( \frac{1}{3}  \right)^2 \right) = 0 \\
\text{\hspace{1.5em}} &3\left( x^2 + \frac{2}{3}x + \left( \frac{1}{3} \right)^2 + 1 - \frac{1}{9} \right) = 0 \\
&3\left(\left( x + \frac{1}{3} \right)^2 + 1 - \frac{1}{9} \right) = 0 \\
&3\left(\left( x + \frac{1}{3} \right)^2 + \frac{8}{9} \right) = 0 \\
&\left( x + \frac{1}{3} \right)^2 + \frac{8}{9} = 0 \\
&\left( x + \frac{1}{3} \right)^2 = -\frac{8}{9} \\
&x + \frac{1}{3} = \pm \sqrt{-\frac{8}{9}} \\
&x = -\frac{1}{3} \pm \sqrt{-\frac{8}{9}} \\
\end{align}  
$$