Zero-Cost Coercions for Program and Proof Reuse
===============================================

Cedille code accompanying the paper draft
([available on arXiv](https://arxiv.org/pdf/1802.00787.pdf)) 
authored by Larry Diehl and Aaron Stump.

We have also developed a [generic version](https://github.com/larrytheliquid/generic-reuse) 
of this development,
where identity functions are defined via propositional equality, 
rather than definitional equality.

Code from the paper
-------------------

* Datatype Definitions
  * [Nat](code/Nat.ced)
  * [List](code/List.ced)
  * [Vec](code/Vec.ced)
  * [VecL](code/VecL.ced)
* Coercion Functions
  * [Identity Coercions](code/IdCoe.ced)
  * [Nested Identity Coercions](code/NestIdCoe.ced)
* Vector Examples
  * [Definitions](code/VecDefs.ced)
  * [Reuse](code/VecReuse.ced)
* List Examples
  * [Definitions (including nested)](code/ListDefs.ced)
  * [Reuse](code/ListReuse.ced)
  * [Nested Reuse](code/NestListReuse.ced)

Cedille Language
----------------

Download and unpack the [Cedille prerelease](http://cs.uiowa.edu/~astump/cedille-prerelease.zip),
then follow INSTALL.txt in `cedille-prerelease` for installation instructions.
