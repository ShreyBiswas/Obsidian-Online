---
{"dg-publish":true,"permalink":"/memory-notes/sum-of-primes-divisible-by-12/"}
---

> [!question] Question
> If $p$ and $q$ are <mark class="hltr-pink">primes</mark>, such that <mark class="hltr-pink">$pq+1$ is a perfect square</mark> greater than 100, prove that <mark class="hltr-pink">$p+q$ is divisible by 12.</mark>


> [!check]- Solution
> As $pq+1$ is a perfect square, we could say <mark class="hltr-pink">$pq+1=n^2$</mark> for some $n$.
> Therefore, $pq=n^2-1$.
> <mark class="hltr-pink">$\implies pq=(n+1)(n-1)$</mark>
> 
> > [!aside] 
> > We can't say $p=n+1$ and $q=n-1$ yet - what if $n^2-1$ has other factors (like if $n=5$ so $n^2-1=24$, $p$ and $q$ *could* be 4 and 6 as above. But, they could also be 3 and 8, or 2 and 12).
> > But, since $p$ and $q$ are prime and equal to $n^2-1$, they are the prime factor decomposition of $n^2-1$, and <mark class="hltr-pink">there are no other factors</mark>. 
> > As there are no other factors, we can now confidently say $p=n+1,q=n-1$.
> 
> As $p=n+1,q=n-1$, we can say $p=q+2$.
> 
> This means they have the same parity - they are both odd, or both even. As they are both prime and different numbers, neither can be 2 (the only even prime), so <mark class="hltr-pink">$p$ and $q$ are both odd and the number between them is even</mark>.
> Also, between the numbers $p, p+1, q$, there *must* be a multiple of 3. Again, as $p$ and $q$ are prime, it is neither of them, so <mark class="hltr-pink">the central number is a multiple of 3</mark>.
> 
> Since the central number is a multiple of 3 and a multiple of 2, <mark class="hltr-pink">it is a multiple of 6</mark>, with $p$ and $q$ either side.
> <mark class="hltr-pink">The sum $p+q$ can therefore be rewritten as $6a-1+6a+1=12a$</mark>, and so $p+q$ is a multiple of 12.



---

> [!connections]
> [[Memory Notes/Mathematical Interviews\|Mathematical Interviews]]