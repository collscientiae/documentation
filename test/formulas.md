title: Formula Test
subtitle: Testing formulas with some Unicode twist

# $$

Formula inside `$$` on separate line:

    $$\int_0^{\infty} \!\! f(ä) \; \mathrm{d}ä$$

$$\int_0^{\infty} \!\! f(ä) \; \mathrm{d}ä$$

# $

    $\int_0^{\infty} \!\! f(x) \, \mathrm{d}x$

inside `$` inline text $\int_0^{\infty} \!\! f(x) \, \mathrm{d}x$ here

# ASCIIMath

This

    ''sin((2*x+1)/(x+1)^2) = 0''

gives ''sin((2*x+1)/(x+1)^2) = 0'' via enclosing in `''`.

# Equation environment

This is equation \eqref{eq:cubes} with my custom label `EQC` referenced via `\eqref{eq:cubes}`.

    \begin{equation}
    x^3 + y^3 = z^3
    \label{eq:cubes}
    \tag{EQC}
    \end{equation}

\begin{equation}
x^3 + y^3 = z^3
\label{eq:cubes}
\tag{EQC}
\end{equation}

## Align environemnt

Important: you have to double-escape the backslashes in \eqref{eq:multiline}.
Also, special signs like the `*` in `align*` do not work right now ...

    \begin{align} 
    a_1 &= b_1+\frac{a_1}{b_2 - a_2} \\\\
    a_2 &= b_2+c_2-d_2+e_2
    \label{eq:multiline}
    \end{align}

\begin{align} 
a_1 &= b_1+\frac{a_1}{b_2 - a_2} \\\\
a_2 &= b_2+c_2-d_2+e_2
\label{eq:multiline}
\end{align}
