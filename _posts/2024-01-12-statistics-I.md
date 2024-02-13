---
layout: post
title: Differential Equations I
category: Mathematics
---
# Intro to LaTeX

Hi there! Here is a brief introduction to LaTeX. It's a great system for creating beautifully typeset scientific documents. The main difference between LaTeX and your standard word processing program is that you write code that tells LaTeX what you want it to display and the program handles all the little things that make your math look great.

Let's start with some basics. You can type text normally but when you want to type some math start and end your expression with a \$. For example, if I type the Pythagorean Theorem, as long as I surround my equation with dollar signs I get $a^2 +b^2 = c^2$. If I want to emphasize an equation simply put TWO dollar signs around the mathematics. For example, a similar expression with two dollar signs around it looks like this: 

$$ x_1^n + x_2^n = x_3^n. $$ 

(check out the code to see how to generate subscripts!)

In LaTeX we use the curly braces, { }, to group things. If we want to raise $e$ to the $42$nd power and we just type it with no grouping we get $e^42$ which is not what we want. Surrounding the $42$ with curly braces gives $e^{42}$.

The really really really great thing about latex is the HUGE library of mathematical symbols, every symbol starts with a $\backslash$, so if I want a nice pi, I just type $\backslash$pi in math mode like so: $\pi$. Want an integral? Try $\backslash$int, want a fraction? Try $\backslash$frac{a}{b} (this gives $\frac{a}{b}$) Here is a more
complicated example:
$$\int_a^b f \left(\frac{x}{2} \right) \ dx = 2\left( F\left(\frac{b}{2} \right) - F\left(\frac{a}{2}\right) \right)$$
(those nice-sized parentheses come from using the $\backslash$left( and $\backslash$right) commands). If you are wondering what the latex command for a symbol is, just try and guess it. If that doesn't work, google it!

There are a few little tricks to making your math look nice, one is the align environment which lets you type multiple lines of aligned mathematical expressions. For instance: 

$$\begin{aligned}
(x^2+y^2)(z^2+w^2) & = (xz)^2 + (yz)^2 + (xw)^2 + (yw)^2 \\
& =  (xz)^2 + 2wxyz + (yw)^2 + (yz)^2 - 2 wxyz + (xw)^2 \\
&= (xz+yw)^2 + (yz-xw)^2 
\end{aligned}$$ 

here the $\backslash\backslash$ is a line break and the $\&$ is an alignment character.

# Sample Proofs


**Problem 1**. *$1^3+2^3+\ldots +n^3 = \left[ \frac{n(n+1)}{2}\right]^2$
for all natural numbers.*

*Proof.* We proceed by induction. When $n=1$ we have
$$1^3 + \ldots + n^3 = 1^3 =1$$ 
and
$$\left[ \frac{n(n+1)}{2}\right]^2=\left[ \frac{1(1+1)}{2}\right]^2 = 1^2 =1.$$
Thus the equation holds when $n=1$.
Now assume the equation holds for some $n \in \mathbb N$. Then by our assumption we have 
$$\begin{aligned}
1^3 + \ldots + n^3 + (n+1)^3& =   \left[ \frac{n(n+1)}{2}\right]^2 + (n+1)^3 = (n+1)^2\left( \frac{n^2}{4} + (n+1)\right) \\
&=(n+1)^2\left( \frac{n^2+4n+4}{4} \right) = (n+1)^2\frac{(n+2)^2}{4}  \\ &=  \left[ \frac{(n+1)(n+2)}{2}\right]^2.
\end{aligned}$$ 
Therefore, by induction, the equation holds for all $n\in \mathbb N$. ◻


**Problem 2**. *Prove $A \subseteq B \Rightarrow A \cap C \subseteq B \cap C$*


*Proof.* Assume $A \subseteq B$ and let $x\in A \cap C$. If $x \in  A \cap C$, then $x\in A$ and $x \in C$. As $x\in A$, by assumption, we have that $x \in B$. Thus $x \in B$ and $x \in C$, giving $x\in B \cap C$. Therefore if $A \subseteq B$, then $A \cap C \subseteq B \cap C$. ◻

