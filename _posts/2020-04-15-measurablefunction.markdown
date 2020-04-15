---
layout: post
title: Measurable Function
---

A measurable function is just the general classification of a function between two measurable spaces that preserves the structure of the two spaces. 

Here's a nice simple definition:

Let \\( (X, \Sigma) \\) and \\( (Y, T) \\) be two measurable spaces.

A function \\( f : X \rightarrow Y \\) is said to be measurable if for every \\( E \in T \\) the pre-image of \\( E \\) under \\( f \\) is in \\( \Sigma \\):

\\[ f^{-1} = \\{ x \in X \mid f(x) \in E \\} \in \Sigma ,\ \forall E \in T \\]

---

The definition is defined like this because there is a structural definition that says: 

"The pre-image of any measurable set is measurable"

What is a pre-image? Well if we take the function we defined earlier, \\( f \\), its image is all the outputs from this function and the preimage is therefore the inputs. In this particular function's case, the image is the measurable set \\( (Y, T) \\) and the pre-image is the measurable set \\( (X, \Sigma) \\).

But to show this in the definition we have to define an element \\( E \\) inside of the image's \\( \sigma \\)-Algebra T which when applied to the inverse of \\( f \\) shows up in the pre-image's \\( \sigma \\)-Algebra \\( \Sigma \\). If this holds, then the function preserves the measurable space and is hence called a measurable function and we can then write it as:
\\[ f : (X, \Sigma) \rightarrow (Y, T) \\]
to show the dependency on the \\( \sigma \\)-Algebras of the measurable sets.
