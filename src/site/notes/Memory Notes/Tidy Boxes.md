---
{"dg-publish":true,"permalink":"/memory-notes/tidy-boxes/"}
---


> [!question] Question
> You are given <mark class="hltr-pink">10 boxes</mark>, each large enough to contain exactly <mark class="hltr-pink">10 wooden building blocks</mark>, and a total of <mark class="hltr-pink">100 blocks in 10 different colours</mark>. There may not be the same number in each colour, so you may not be able to pack the blocks into the boxes in such a way that each box contains only one colour of block. Show that it is possible to do it so that **<mark class="hltr-red">each box contains at most two different colours.</mark>**


> [!check]- Solution
> As always, start with a smaller version - just **1 box and 10 bricks of the same colour**. Here, a solution is obvious - put them all into one box.
> Then, progress to the next smallest version - **2 boxes and 20 bricks in 2 colours**. Here, still, a solution is obvious - no matter how you put them into the boxes, you still have at most 2 different colours.
> 
> At **3 boxes, and 30 bricks**, things are less simple. However, we know one thing - <mark class="hltr-pink">the least common colour happens at most 10 times, and the most common colour happens at least 10 times.</mark> This can be seen by considering the average; each colour has 10 bricks. For a colour to then have less than the average, another must have more.
> Using this information, we know that we can fit one colour entirely into a box, and perhaps even have room to spare. Filling that room with the other colours, <mark class="hltr-pink">the problem is now a case of 2 boxes and 20 bricks in 2 colours</mark>, which we know is solvable.
> 
> It would seem that we have a idea to follow - putting the least common colour in first. We should try **4 boxes and 40 bricks** to confirm this. By the same proof, we know at least one colour  entirely fits into a box. 
> To fill the remaining space in just 2 colours, <mark class="hltr-pink">we need another colour to have at least 9 bricks</mark> (in the worst case, where the least common colour is a single brick). As seen before, we know the most common colour happens at least 10 times, so this can always happen.
> Now, that box is full - we have **3 boxes and 30 bricks** left. This is the same problem as earlier, so we can solve that.
> 
> **This logic then carries through all the way to 10 bricks.**




---

> [!connections]
> [[Memory Notes/Mathematical Interviews\|Mathematical Interviews]]