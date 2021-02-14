# Readme

- Search "QQ" for questions

E is a hierarchy of splittings ... so by bieri ... the group has larger and larger algebraic dimension ... end on 3 .... alg dim <= geo dim
... we're just showing that the algebraic dimension of E/G is 3 (though it is true that E has the intuitively correct geometric dimension, we only use 3 cells)

## Todo
- [ ] look over Guirardel proof of proposition 8.10 for details on foliations on complexes
- [ ] discussion of non examples for bieri like the HMM shift and the gluing of F infinities into an F2. 
- [ ] discussion of examples of our theorem are hard to write down since you have to verify the intersection of so many stabilitzers is FP 
- [x] Lemma: axes of a given hyeperbolic elment are hausdorff equivalent (we don't need combinatorial anything, it holds in general)
- [ ] When we get the two trees, keep in mind we start iwth the bs trees X x Y and get a subset from guirardel, and then we get a VH complex, TLDR we don't actually use the fact that a general VH-complex universal cover sits in tree x tree.
- [ ] Work out how deep the no tree assumption goes
- [x] Read through Forester paper, take down relevant algebraic graph of group definitions
- [ ] Outline why core is simply connected
  - [x] Send email and break out as a lemma
  - [x] Write details of core being simply connected lemma
- [ ] Write up email that avoids folding
- [ ] Define VHD complex
- [ ] Details on f121 and f122
  - [x] define bass-serre maps as quotient of unviersal cover of GOS
- [ ] Details on Standard 2-complex fibration
  - Not that it's an isometry on edges, but rather if it happens to be transverse on an edge then it's an isometry
  - Ours will be transverse on edges
- [ ] Prove Transverse Lemma
  - [x] Argue upstairs for (3) implies (2)
  - [x] Add skeleton for propositions from email subject "an easier way" to finish thm:ellipticimpliesequality.
  - [x] Details on parallel axes in a CAT(0) space
  - [ ] Lemma: axes of a given hyeperbolic elment are hausdorff equivalent
- [x] Linear Reading #3
  - [x] initial run through
  - [x] depth first following of tree to first unsatisfied node
- [x] How did cocompactness work to begin the bootstrap
  - [x] Write this proof citing continuous, diagonal, product properties
- [x] Prove Switching Lemma
  - [x] Read through Switching lemma outline
  - [x] Read through coloring lemma
  - [x] Prove reduction to vertical subpath lemma
  - [x] Prove multicolored lemma (using new technique without snipping)
  - [x] Read through planar switching lemma
  - [x] Write reduction to vertical subpath lemma
  - [x] Write multicolored lemma (using new technique without snipping)
- [x] Compute example showing local condition is not enough to guarantee parallel classes of edges
- [x] Pull in iterated splitting lemma from chalkboard
- [x] Outline "Bieri Dimension Argument"
- [x] Post 2020-08-19 linear run

## Meeting Notes

### 2020-08-19

- General GOS nonsense gives "Scott-Wall" maps to underlying trees, VH details gives that the product is actually an embedding
- It is true that the Scott-Wall maps are just the embedding from Wise followed by projections
- We need the action of G on C to be PD. Locally finite cell complex plus free gives us PD
- Note: Freeness of the acton means that it covers it's quotient
- We also need to satisfy the "intrinsic GOS" decomposition. We need the "slide map" of the edge space to be injective on fundamental group.
- If a composition is injective then so is the final map, use this to see that if all edge groups inject then edge groups inject into the vertex groups. QQ: why do we need this again? AA: This ensures a valid graph of groups decomposition.
- For VHD define it so that links are tripartite simplicial graphs. Remark: Wise assumed NPC and attains bipartite simplicial. Lemma should imply that the parallel properties hold
- Group for which the statement is false: ZxZ, Deformation spaces correspond to slopes correspond to homotopty types of s.c.c. on a torus
- minimal crossings = squares in Guirardel core.

### 2020-08-21

- Went over using the CAT(0) property of the tree product and working with the quotient to get that the quotient is a graph of spaces and how this interacts with the cover to see that it is a tree of spaces.
- In general for a CAT(0) cube complex we have that (1) hyperplanes are embedded and (2) hyperplanes are separating (both by Sageev)
- Hyperplanes(subcomplex) = subcomplex intersect hyperplanes of ambient complex
