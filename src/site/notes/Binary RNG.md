---
{"dg-publish":true,"permalink":"/binary-rng/","dgPassFrontmatter":true}
---

> [!question] Question
> You have a random number generator that returns either 0 or 1. How can you use it to randomly generate a number between 0 and 7, with an equal chance of each possible number?


> [!check]- Solution
> As it returns 0 or 1, using binary is likely a good way to look at this. Just by repeatedly using your RNG to create 0 or 1, you can create a bitstring of any length. The range of 0-7 can be represented fully using 3 bits, so we just need to generate 3 random bits.
> Each bit has a $\frac{1}{2}$ chance of being 0 or 1, so the distribution is fully even.



> [!question] Extension I
> Can you randomly generate any number between 0 and $n$?

> [!check] Solution I
> The main problem here is that if $n+1$ (the number of possible results) is not a direct power of 2, like 7 was, then we can't just generate $\log_{2}n$ random bits.
> However, it's very easy to adapt the algorithm. Calculate $\log_{2}n$ as before, but round upwards. This will give us some extra numbers - if we ever land on them, just discard the result and re-run the RNG.
> As this is an even distribution across all numbers, but with any number outside the range being invalid, this will be an even distribution across all valid numbers.


> [!question] Extension II
> What about between two arbitrary numbers $a$ and $b$?

> [!check] Solution II
> First, it helps to think about how we could map this to the previous versions of the question. This is easy enough - we just need to reduce $a$ to 0. We can do this by subtracting $a$ from both boundaries.
> Using the previous algorithm, we can now generate a random number between 0 and $b-a$. Then, just add $a$ back again for the final number.



---

> [!connections]
> [[Memory Notes/Mathematical Interviews\|Mathematical Interviews]]