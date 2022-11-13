---
{"dg-publish":true,"permalink":"/memory-notes/write-an-expression-for-max/"}
---

> [!question] Question
> Write a mathematical expression to give <mark class="hltr-pink">$\max(x,y)$</mark>.
> *You can use the simple mathematical expressions <mark class="hltr-pink">$+,-,\div,\times$</mark>, as well as <mark class="hltr-pink">$x^2$</mark> and <mark class="hltr-pink">$\sqrt{ x }$</mark>. By using the square and positive root, you can also get a modulus <mark class="hltr-pink">$|x|$</mark>.*


> [!check]- Solution
> First, it's important to realise we don't know what's larger, $x$ or $y$. Because of this, it's helpful to think of expressions that give us a definite number, no matter whether the larger number is first or second.
> $x+y$ always outputs the total. $x-y$ doesn't, but with the modulus, $|x-y|$ does.
> The sum $x+y$ could be more meaningful by dividing it by 2, to get the mean: $\frac{x+y}{2}$. This is a little more helpful.
> We know that <mark class="hltr-pink">the mean is exactly halfway</mark> between both $x$ and $y$ - and so, it is 