---
layout: post
title: Sigma-Algebras and the Measurable Space
---

Sigma Algebras denoted: \\( \sigma \\)-Algebras are special kinds of sets used primarily in measure theory with applications in analysis and probability.

The technical definition is:

Let \\( X \\) be some set and let \\( \mathcal{P}(X) \\) represent its Power Set. Then a certain subset \\( \Sigma \subseteq \mathcal{P}(X) \\) is called a \\( \sigma-Algebra \\) if it satisfies the following properties:

* \\( X \\) is in \\( \Sigma \\) and \\( X \\) is the universal sets (set containing everything we care about)
* \\( \Sigma \\) is closed under complementation ie: If \\( A \\) is in \\( \Sigma \\) then so is its compllement
* \\( \Sigma \\) is closed under countable unionis ie: If \\( A_1 \\), \\( A_2 \\), \\( A_3 \\), . . . are in \\( \Sigma \\) then so is \\( A_1 \cup A_2 \cup A_3 \cup \\) . . .

From these properties it is pretty obvious to see that the smallest possible \\( \sigma \\)-Algebra set is: \\( \{X, \emptyset\} \\) whilst the largest possible set is: \\( 2^X \\) which is the Power Set of \\( X \\): \\( \mathcal{P}(X) \\).

---

Note that I said that \\( \sigma \\)-Algebras are used in measure theory. They are used to define something called Measurable Space.

So, the elements of a \\( \sigma \\)-Algebra are called Measurable Sets. If we now take an ordered pair (order is important): \\( (X, \Sigma) \\) where \\( X \\) is a set and \\( \Sigma \\) is a \\( \sigma \\)-Algebra over \\( X \\), we now have the thing known as a Measurable Space. 

---

Usually I nice way to understand abstract algebra is a nice example:

Let \\( X = \{ a, b, c, d\} \\) then one possible \\( \sigma \\)-Algebra could be: \\( \Sigma = \{\emptyset, \{a, b\}, \{c, d\}, \{a, b, c, d\} \} \\) or the \\( \sigma \\)-Algebra could just equal the Power Set: \\( \Sigma = \mathcal{P}(X) \\) or it could be as small as possible: \\( \Sigma = \{X, \emptyset \} \\).

Then in all these cases, whichever you choose, the measurable space would be: \\( (X, \Sigma ) \\).
