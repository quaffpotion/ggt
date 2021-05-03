# Readme

- Search "QQ" for questions

## Todo
- [ ] Linear Reading 2021-05-02
- [ ] Writeup connected fibers lemma

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

### 2020-08-20

- Went over using the CAT(0) property of the tree product and working with the quotient to get that the quotient is a graph of spaces and how this interacts with the cover to see that it is a tree of spaces.
- In general for a CAT(0) cube complex we have that (1) hyperplanes are embedded and (2) hyperplanes are separating (both by Sageev)
- Hyperplanes(subcomplex) = subcomplex intersect hyperplanes of ambient complex

### 2020-04-21
Connected Fiber Lemma
Sketch: Talk about sending fibers of the square to the tree via embedded paths of uniform speed. Said this way it includes the constant path and also means the original case by case definition can be reduced to one case. Also helps to organize the logic by selecting something in the square and connecting it to the base since it is in some preimage after all. Then we need a path in the graph from x to x' (that's f(x) to t0 in T) We need a + b = d( f(x), t0 ) (where a is distance from the eta image to t and b is the distance from t to t0) to be satisfied while moving points along the path. Taking the nearest point in K the graph, gives us that our path won't wander past t.  As for continuity of F, we recognize there is something to prove but won't be giving details) 
