---
{"dg-publish":true,"permalink":"/memory-notes/modular-arithmetic/"}
---


> [!definition]
> Modular Arithmetic deals with the remainders of division.
> For example, $a \mod{b}$ means divide $\frac{a}{b}$, and discard everything that isn’t the remainder.
> For example, $11\mod{8} = 3$.

These can greatly simplify [[Memory Notes/Modulus Questions\|Modulus Questions]]

#### Congruence

This introduces the idea that numbers can be congruent - they return the same answer for a particular modulus.
*19 is congruent to 11 mod 8*, since they are both equal to 3.


#### Operations

Many operations work the same even under Modular Arithmetic.
For example, given:
$$a = b\mod m$$
Multiplying $a$ by some number will simply also multiply $b$ by that number.
$$ak = bk \mod m$$
This also applies multiplying two modular statements - if $a = b\mod m$ and $c = d \mod m$:
$$ac = bd \mod m$$

Addition works the same as well, both inside and outside of modulus:
$$ a + k = b + k \mod m$$
Even powers work the same:
$$a^k = b^k \mod m$$



---


#Maths