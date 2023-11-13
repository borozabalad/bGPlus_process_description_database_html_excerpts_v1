# https://en.wikipedia.org/wiki/Graph_theory#Graph

<div class="mw-content-ltr mw-parser-output" lang="en" dir="ltr">

### <span id="Graph" class="mw-headline">Graph</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/w/index.php?title=Graph_theory&action=edit&section=1 "Edit section: Graph")<span class="mw-editsection-bracket">\]</span></span>

<figure class="mw-default-size" typeof="mw:File/Thumb">
<a href="/wiki/File:Undirected.svg" class="mw-file-description"><img
src="//upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Undirected.svg/220px-Undirected.svg.png"
class="mw-file-element" decoding="async"
srcset="//upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Undirected.svg/330px-Undirected.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Undirected.svg/440px-Undirected.svg.png 2x"
data-file-width="100" data-file-height="100" width="220"
height="220" /></a>
<figcaption>A graph with three vertices and three edges.</figcaption>
</figure>

In one restricted but very common sense of the
term,<sup>[\[1\]](#cite_note-FOOTNOTEBenderWilliamson2010148-1)[\[2\]](#cite_note-2)</sup>
a **graph** is an [ordered pair](/wiki/Ordered_pair "Ordered pair")
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$G = (V,E)$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/644a8d85ee410b6159ca2bdb5dcb9097e2c8f182"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:11.331ex; height:2.843ex;"
aria-hidden="true" alt="G=(V,E)" /></span> comprising:

- <span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
  style="display: none;">$V$</span><img
  src="https://wikimedia.org/api/rest_v1/media/math/render/svg/af0f6064540e84211d0ffe4dac72098adfa52845"
  class="mwe-math-fallback-image-inline mw-invert"
  style="vertical-align: -0.338ex; width:1.787ex; height:2.176ex;"
  aria-hidden="true" alt="V" /></span>, a
  [set](/wiki/Set_(mathematics) "Set (mathematics)") of **vertices**
  (also called **nodes** or **points**);
- <span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
  style="display: none;">$E \subseteq \{\{ x,y\} \mid x,y \in V\;\text{and}\; x \neq y\}$</span><img
  src="https://wikimedia.org/api/rest_v1/media/math/render/svg/15e9954c722145a63f937b26123915b546cb9db7"
  class="mwe-math-fallback-image-inline mw-invert"
  style="vertical-align: -0.838ex; width:33.749ex; height:2.843ex;"
  aria-hidden="true"
  alt="{\\displaystyle E\\subseteq \\{\\{x,y\\}\\mid x,y\\in V\\;{\\textrm {and}}\\;x\\neq y\\}}" /></span>,
  a [set](/wiki/Set_(mathematics) "Set (mathematics)") of **edges**
  (also called **links** or **lines**), which are [unordered
  pairs](/wiki/Unordered_pair "Unordered pair") of vertices (that is, an
  edge is associated with two distinct vertices).

To avoid ambiguity, this type of object may be called precisely an
**undirected simple graph**.

In the edge
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$\{ x,y\}$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/f2611cdc8fecaffa28cb0ea888dbba55f3a31077"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:5.844ex; height:2.843ex;"
aria-hidden="true" alt="\\{x,y\\}" /></span>, the vertices
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$x$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/87f9e315fd7e2ba406057a97300593c4802b53e4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.33ex; height:1.676ex;"
aria-hidden="true" alt="x" /></span> and
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$y$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/b8a6208ec717213d4317e666f1ae872e00620a0d"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.671ex; width:1.155ex; height:2.009ex;"
aria-hidden="true" alt="y" /></span> are called the **endpoints** of the
edge. The edge is said to **join**
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$x$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/87f9e315fd7e2ba406057a97300593c4802b53e4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.33ex; height:1.676ex;"
aria-hidden="true" alt="x" /></span> and
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$y$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/b8a6208ec717213d4317e666f1ae872e00620a0d"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.671ex; width:1.155ex; height:2.009ex;"
aria-hidden="true" alt="y" /></span> and to be **incident** on
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$x$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/87f9e315fd7e2ba406057a97300593c4802b53e4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.33ex; height:1.676ex;"
aria-hidden="true" alt="x" /></span> and on
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$y$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/b8a6208ec717213d4317e666f1ae872e00620a0d"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.671ex; width:1.155ex; height:2.009ex;"
aria-hidden="true" alt="y" /></span>. A vertex may exist in a graph and
not belong to an edge. Under this definition, **[Multiple
edges](/wiki/Multiple_edges "Multiple edges")**, in which two or more
edges connect the same vertices, are not allowed.

In one more general sense of the term allowing multiple
edges,<sup>[\[3\]](#cite_note-FOOTNOTEBenderWilliamson2010149-3)[\[4\]](#cite_note-4)</sup>
a **graph** is an ordered triple
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$G = (V,E,\phi)$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/7d427ef20e7ca460e1a8fc6069aa44aa43447c5e"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:13.751ex; height:2.843ex;"
aria-hidden="true" alt="{\\displaystyle G=(V,E,\\phi )}" /></span>
comprising:

- <span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
  style="display: none;">$V$</span><img
  src="https://wikimedia.org/api/rest_v1/media/math/render/svg/af0f6064540e84211d0ffe4dac72098adfa52845"
  class="mwe-math-fallback-image-inline mw-invert"
  style="vertical-align: -0.338ex; width:1.787ex; height:2.176ex;"
  aria-hidden="true" alt="V" /></span>, a
  [set](/wiki/Set_(mathematics) "Set (mathematics)") of **vertices**
  (also called **nodes** or **points**);
- <span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
  style="display: none;">$E$</span><img
  src="https://wikimedia.org/api/rest_v1/media/math/render/svg/4232c9de2ee3eec0a9c0a19b15ab92daa6223f9b"
  class="mwe-math-fallback-image-inline mw-invert"
  style="vertical-align: -0.338ex; width:1.776ex; height:2.176ex;"
  aria-hidden="true" alt="E" /></span>, a
  [set](/wiki/Set_(mathematics) "Set (mathematics)") of **edges** (also
  called **links** or **lines**);
- <span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
  style="display: none;">$\phi:E\rightarrow\{\{ x,y\} \mid x,y \in V\;\text{and}\; x \neq y\}$</span><img
  src="https://wikimedia.org/api/rest_v1/media/math/render/svg/e4d1de96c66b47f9e65d46b28d8a2d6c42927bcd"
  class="mwe-math-fallback-image-inline mw-invert"
  style="vertical-align: -0.838ex; width:37.587ex; height:2.843ex;"
  aria-hidden="true"
  alt="{\\displaystyle \\phi :E\\to \\{\\{x,y\\}\\mid x,y\\in V\\;{\\textrm {and}}\\;x\\neq y\\}}" /></span>,
  an **incidence function** mapping every edge to an [unordered
  pair](/wiki/Unordered_pair "Unordered pair") of vertices (that is, an
  edge is associated with two distinct vertices).

To avoid ambiguity, this type of object may be called precisely an
**undirected [multigraph](/wiki/Multigraph "Multigraph")**.

A **[loop](/wiki/Loop_(graph_theory) "Loop (graph theory)")** is an edge
that joins a vertex to itself. Graphs as defined in the two definitions
above cannot have loops, because a loop joining a vertex
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$x$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/87f9e315fd7e2ba406057a97300593c4802b53e4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.33ex; height:1.676ex;"
aria-hidden="true" alt="x" /></span> to itself is the edge (for an
undirected simple graph) or is incident on (for an undirected
multigraph)
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$\{ x,x\} = \{ x\}$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/a457ee3880442411f71879595a0e99c666601791"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:12.771ex; height:2.843ex;"
aria-hidden="true" alt="{\\displaystyle \\{x,x\\}=\\{x\\}}" /></span>
which is not in
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$\{\{ x,y\} \mid x,y \in V\;\text{and}\; x \neq y\}$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/a70ae8296685423e58fb58f1b7d5061f64d66fc6"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:28.875ex; height:2.843ex;"
aria-hidden="true"
alt="{\\displaystyle \\{\\{x,y\\}\\mid x,y\\in V\\;{\\textrm {and}}\\;x\\neq y\\}}" /></span>.
So to allow loops the definitions must be expanded. For undirected
simple graphs, the definition of
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$E$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/4232c9de2ee3eec0a9c0a19b15ab92daa6223f9b"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.776ex; height:2.176ex;"
aria-hidden="true" alt="E" /></span> should be modified to
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$E \subseteq \{\{ x,y\} \mid x,y \in V\}$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/8153f5127d2ca8bce373d2520c36b3fdbb6bff25"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:23.127ex; height:2.843ex;"
aria-hidden="true"
alt="{\\displaystyle E\\subseteq \\{\\{x,y\\}\\mid x,y\\in V\\}}" /></span>.
For undirected multigraphs, the definition of
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$\phi$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/72b1f30316670aee6270a28334bdf4f5072cdde4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.671ex; width:1.385ex; height:2.509ex;"
aria-hidden="true" alt="\\phi " /></span> should be modified to
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$\phi:E\rightarrow\{\{ x,y\} \mid x,y \in V\}$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/49004a1fd53258a96c0c8d2609fcf83620a1f282"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:26.965ex; height:2.843ex;"
aria-hidden="true"
alt="{\\displaystyle \\phi :E\\to \\{\\{x,y\\}\\mid x,y\\in V\\}}" /></span>.
To avoid ambiguity, these types of objects may be called **undirected
simple graph permitting loops** and **undirected multigraph permitting
loops** (sometimes also **undirected
<a href="/wiki/Pseudograph" class="mw-redirect"
title="Pseudograph">pseudograph</a>**), respectively.

<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$V$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/af0f6064540e84211d0ffe4dac72098adfa52845"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.787ex; height:2.176ex;"
aria-hidden="true" alt="V" /></span> and
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$E$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/4232c9de2ee3eec0a9c0a19b15ab92daa6223f9b"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.776ex; height:2.176ex;"
aria-hidden="true" alt="E" /></span> are usually taken to be finite, and
many of the well-known results are not true (or are rather different)
for infinite graphs because many of the arguments fail in the
<a href="/wiki/Infinite_graph" class="mw-redirect"
title="Infinite graph">infinite case</a>. Moreover,
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$V$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/af0f6064540e84211d0ffe4dac72098adfa52845"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.787ex; height:2.176ex;"
aria-hidden="true" alt="V" /></span> is often assumed to be non-empty,
but
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$E$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/4232c9de2ee3eec0a9c0a19b15ab92daa6223f9b"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.776ex; height:2.176ex;"
aria-hidden="true" alt="E" /></span> is allowed to be the empty set. The
**order** of a graph is
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$|V|$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/9ddcffc28643ac01a14dd0fb32c3157859e365a7"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:3.081ex; height:2.843ex;"
aria-hidden="true" alt="|V|" /></span>, its number of vertices. The
**size** of a graph is
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$|E|$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/d8c2b9637808cf805d411190b4ae017dbd4ef8d8"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:3.069ex; height:2.843ex;"
aria-hidden="true" alt="|E|" /></span>, its number of edges. The
**degree** or **valency** of a vertex is the number of edges that are
incident to it, where a loop is counted twice. The **degree** of a graph
is the maximum of the degrees of its vertices.

In an undirected simple graph of order *n*, the maximum degree of each
vertex is <span class="nowrap">*n* âˆ’ 1</span> and the maximum size of
the graph is

<span class="sfrac tion" role="math"><span class="num">*n*(*n* âˆ’
1)</span><span class="sr-only">/</span><span class="den">2</span></span>.

The edges of an undirected simple graph permitting loops
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$G$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/f5f3c8921a3b352de45446a6789b104458c9f90b"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.827ex; height:2.176ex;"
aria-hidden="true" alt="G" /></span> induce a symmetric [homogeneous
relation](/wiki/Binary_relation#Homogeneous_relation "Binary relation")
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$\sim$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/afcc42adfcfdc24d5c4c474869e5d8eaa78d1173"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: 0.307ex; margin-bottom: -0.478ex; width:1.808ex; height:1.343ex;"
aria-hidden="true" alt="\\sim " /></span> on the vertices of
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$G$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/f5f3c8921a3b352de45446a6789b104458c9f90b"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.827ex; height:2.176ex;"
aria-hidden="true" alt="G" /></span> that is called the **adjacency
relation** of

</div>
