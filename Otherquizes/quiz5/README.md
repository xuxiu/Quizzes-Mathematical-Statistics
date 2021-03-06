![Q_banner](https://github.com/QuantLet/Styleguide-and-Validation-procedure/blob/master/pictures/banner.png)

## ![qlogo](https://github.com/QuantLet/Styleguide-and-Validation-procedure/blob/master/pictures/qloqo.png) **Quiz Five**

```yaml

Name of QuantLet : NMMS5

Published in : Null

Description : 'Quiz 5 Numerical Methods of Mathematical Statistics; 
Prove 18 under standard normal distribution' 

Keywords : 'Weak Law of Large Numbers, Convergence Theory, Convergence properties'

Author : Luis Alejandro Sarmiento Abogado

Submitted : Tue, December 02 2015 by Luis Alejandro Sarmiento Abogado

Datafile : Null

```
[Quiz five.pdf](https://github.com/saabogal/NMS567337-Q1/files/50983/Quiz5.pdf)

```tex

\documentclass[english]{article}
\usepackage[T1]{fontenc}
\usepackage[utf8]{luainputenc}
\usepackage{color}
\usepackage{stackrel}
\usepackage{esint}
\usepackage{babel}
\begin{document}

\title{\textcolor{blue}{\large{}Numerical Methods of Mathematical Statistics }}

\maketitle

\section{Quiz 5.0 (5-2)}

Prove theorem 18 under standard normal distribution:\\
We start from the fact that the pdf of a standard normal distribution
is $\frac{1}{\sqrt{2\pi}}e^{\frac{-x^{2}}{2}}$; And its characteristic
function according to Theorem 17 is $\frac{1}{\sqrt{2\pi}}\stackrel[-\infty]{\infty}{\int}e^{it^{T}x}e^{\frac{-x^{2}}{2}}dx$.
So to prove theorem 18 we follow the subsequent transformations:
\begin{itemize}
\item $\frac{1}{\sqrt{2\pi}}\stackrel[-\infty]{\infty}{\int}e^{\left\{ \frac{-1}{2}\left(t^{2}-2itx+x^{2}\right)\right\} -\frac{t^{2}}{2}}dx$ 
\item $\frac{1}{\sqrt{2\pi}}\stackrel[-\infty]{\infty}{\int}e^{\left\{ \frac{-1}{2}\left(t^{2}-2itx+x^{2}\right)\right\} -\frac{t^{2}}{2}}dx=exp\frac{-t^{2}}{2}$
Thus by theorem 18 we equalize:
\item $\frac{1}{\sqrt{2\pi}}e^{\frac{-x^{2}}{2}}=\frac{1}{\sqrt{2\pi}}\stackrel[-\infty]{\infty}{\int}e^{it^{T}x}e^{\frac{-t^{2}}{2}}dt\longrightarrow\frac{1}{\sqrt{2\pi}}\frac{1}{\sqrt{2\pi}}\stackrel[-\infty]{\infty}{\int}e^{\left\{ \frac{-1}{2}(t^{2}-2itx-x^{2}\right\} +\frac{1}{2}x^{2}}dt\longrightarrow\frac{1}{\sqrt{2\pi}}\frac{1}{\sqrt{2\pi}}\stackrel[-\infty]{\infty}{\int}e^{\frac{-1}{2}(t-x)^{2}+\frac{1}{2}x^{2}}dt\longrightarrow\frac{1}{\sqrt{2\pi}}e^{\frac{-x^{2}}{2}}$
\end{itemize}
Thus proving theorem 18
\end{document}

```

