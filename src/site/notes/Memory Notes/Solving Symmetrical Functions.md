---
{"dg-publish":true,"permalink":"/memory-notes/solving-symmetrical-functions/"}
---

> [!question] Question
> If $2x^4-11x^3+16x^2-11x+2=0$, <mark class="hltr-pink">what are the possible values of $x+\frac{1}{x}$</mark>?


> [!check]- Solution
> An issue which immediately arises when trying to raise $\left( x+\frac{1}{x} \right)$ to different powers, is that we <mark class="hltr-pink">can only get even powers of $x$</mark>. Even when adding different powers, we could only get even ones.
> In fact, the only way to get an odd power is with the original - $x+\frac{1}{x}$.
> 
> So, if we try to add together powers of $x$ to reconstruct the original equation, the only odd powers we can get are $x^1$ and $x^{-1}$.
> 
> Therefore, we need to manipulate our original equation into a form only containing those. The highest odd power, <mark class="hltr-pink">$x^3$, needs to be taken to $x^1$</mark>.
> $$2x^4-11x^3+16x^2-11x+2=0$$
> $$\implies x^2(2x^2-11x+16-11x^{-1}+2x^{-2})=0$$
> <mark class="hltr-red">$$\implies 2x^2-11x+16-11x^{-1}+2x^{-2}=0$$.</mark>
> 
> We can get $2x^2$ from $2\left( x+\frac{1}{x} \right)^2=2(x^2+2+x^{-2})$.
> Subtracting this from the equation, we're left with $-11x+12-11x^{-1}$. We can get $-11x$ from $11\left( x+\frac{1}{x} \right)$.
> Subtracting that, we find that we'd only need to add 12 more to reach the original equation.
> 
> So, representing $x+\frac{1}{x}=y$, we can rewrite the equation we're trying to find as:
> <mark class="hltr-pink">$$2y^2-11y+12=0$$</mark>
> This can easily be solved to $(2y-3)(y-4)=0$, and so our answer for values of $x+\frac{1}{x}$ are $\frac{3}{2}$ and $4$.


---

> [!connections]
> [[Memory Notes/Mathematical Interviews\|Mathematical Interviews]]