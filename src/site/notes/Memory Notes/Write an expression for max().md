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
> We know that <mark class="hltr-pink">the mean is exactly halfway</mark> between both $x$ and $y$ - and so, it is $\frac{{|x-2|}}{2}$ away. 
> 
> It is now simple to see that <mark class="hltr-pink">adding that value to the mean</mark> gives us the higher of the two values, or the maximum.
> $$\frac{x+y}{2}+\frac{|x-2|}{2}=\max(x,y)$$


> [!question] Extension I
> What about $\min(x,y)$?

> [!check]- Solution I
> Simply subtract from the mean, rather than add.
> <mark class="hltr-pink">$$\frac{x+y}{2}-\frac{|x-y|}{2}$$</mark>


> [!question] Extension II
> What about $\max(x,y,z)$?

> [!check]- Solution II
> You can rewrite $\max(x,y,z)$ as $\max(\max(x,y),z)$. 
> Therefore, you can just insert the output of the first equation into itself, to get the final value.



---

> [!connections]
> [[Memory Notes/Mathematical Interviews\|Mathematical Interviews]]