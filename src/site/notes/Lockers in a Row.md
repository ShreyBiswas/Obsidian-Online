---
{"dg-publish":true,"permalink":"/lockers-in-a-row/","dgPassFrontmatter":true}
---

> [!question] Question
> Lockers in a row are numbered $1,2,3,\dots,1000$. Initially, <mark class="hltr-pink">they're all open</mark>.
> A person walks by, closing every locker.
> Another person walks by, opening every other locker $(2, 4,6,8,10,\dots)$.
> Another person walks by, swapping the state of every third locker $(3,6,9,12,\dots)$. That is, opening a shut locker, and closing an open one.
> 
> This goes on until <mark class="hltr-pink">no more lockers are changed</mark>.
> 
> Which lockers are <mark class="hltr-pink">closed</mark>?


> [!check]- Solution
> First, we should figure out when the lockers start changing. As the first locker changed increases by 1 each time, it's when the 1000th person passes by, only changing the final locker.
> 
> Then, we can think about one particular locker. <mark class="hltr-pink">The only people who change its state are those whos number are a factor of the locker number.</mark>
> For example, the 12th locker is closed by the 1st, 2nd, 3rd, 4th, 6th, and 12th people.
> The first person closes it, while the second opens it. The 3rd shuts it, 4th opens. 6th shuts, and 12th opens - so this locker is left open.
> Because there are <mark class="hltr-pink">an even number of factors, the locker is <mark class="hltr-red">left open</mark></mark>.
> 
> So, to find the lockers that are closed, we need to find all the numbers with an <mark class="hltr-pink">odd number of factors</mark>.
> Most numbers have an even number. If you take one factor, and divide the number by that factor, you'll get a complementary number. This would happen in pairs, giving you two factors - so an even number of factors overall.
> The only exception are <mark class="hltr-pink">square numbers</mark>, where the square root doesn't give you a different number. <mark class="hltr-pink">Square numbers have an odd number of factors</mark>.
> 
> Therefore all square numbers are left closed.


---

> [!connections]
> [[Memory Notes/Mathematical Interviews\|Mathematical Interviews]]