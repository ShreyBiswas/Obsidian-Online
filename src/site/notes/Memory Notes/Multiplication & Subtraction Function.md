---
{"dg-publish":true,"permalink":"/memory-notes/multiplication-and-subtraction-function/"}
---

> [!question] Question
> There is a function $f(x)$, which follows two rules. Firstly, it can never be zero $(f(x)\neq_{0})$.
> Secondly, <mark class="hltr-pink">$f(x)\times f(y)=f(x-y)$</mark> - the output of the difference between numbers, is equal to the output of the numbers separately, multiplied together.
> What is $f(3)$?


> [!check]- Solution 1
> The equation can be rewritten:
> <mark class="hltr-pink">$$f(x)f(y)=f(x-y)$$</mark>
> <mark class="hltr-pink">$$\implies f(x)=\frac{f(x-y)}{f(y)}$$</mark>
> 
> From this result, we can get a definite value for $f(x)$ if we can get the numerator and denominator of the fraction to be the same.
> This is easily achieved if <mark class="hltr-pink">$y=\frac{x}{2}$</mark>, resulting in $\frac{f\left( \frac{x}{2} \right)}{f\left( \frac{x}{2} \right)}=1$.
> This is <mark class="hltr-pink">true for all $x$</mark>, and therefore $f(3)=1$.


 > [!check]- Solution 2
 > We can try looking at different values of $x$.
 > For example, $f(1)$. This can be written as $f(3-2)=f(3)f(2)$, but also as $f(4-3)=f(4)f(3)$.
 > By looking at <mark class="hltr-pink">$f(3)f(4)=f(3)f(2)\implies f(4)=f(2)$</mark>, and seeing how this is true not just for 4 and 2, but <mark class="hltr-pink">any two values</mark> of $x$, we can see that <mark class="hltr-pink">all values of $x$ have the same $f(x)$.</mark>
 > 
 > We can then look at the special case, $f(0)$. We can easily see <mark class="hltr-pink">$f(0)=f(1-1)=f(1)f(1)=f(1)^2$</mark>. As we just proved that all values of $x$ are the same, <mark class="hltr-pink">$f(0)=f(1)$</mark>, and so <mark class="hltr-pink">$f(0)=f(1)^2=f(0)^2$</mark>. 
 > 
 > If $f(0)=f(0)^2$, then it can only be one of two values for which this is true - <mark class="hltr-pink">0 or 1</mark>. 
 > As mentioned in the question, <mark class="hltr-pink">$f(x)\neq{0}$</mark>, and so $f(0)=1$.
 > Finally, $f(0)=f(3)=1$.


---

> [!connections]
> [[Memory Notes/Mathematical Interviews\|Mathematical Interviews]]