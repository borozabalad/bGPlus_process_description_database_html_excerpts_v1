# https://en.wikipedia.org/wiki/Graph_theory#Directed_graph

<div class="mw-content-ltr mw-parser-output" lang="en" dir="ltr">

### <span id="Directed_graph" class="mw-headline">Directed graph</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/w/index.php?title=Graph_theory&action=edit&section=1 "Edit section: Directed graph")<span class="mw-editsection-bracket">\]</span></span>

<div class="hatnote navigation-not-searchable" role="note">

Main article: [Directed graph](/wiki/Directed_graph "Directed graph")

</div>

<figure class="mw-default-size" typeof="mw:File/Thumb">
<a href="/wiki/File:Directed.svg" class="mw-file-description"><img
src="//upload.wikimedia.org/wikipedia/commons/thumb/a/a2/Directed.svg/220px-Directed.svg.png"
class="mw-file-element" decoding="async"
srcset="//upload.wikimedia.org/wikipedia/commons/thumb/a/a2/Directed.svg/330px-Directed.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/a/a2/Directed.svg/440px-Directed.svg.png 2x"
data-file-width="250" data-file-height="225" width="220"
height="198" /></a>
<figcaption>A directed graph with three vertices and four directed edges
(the double arrow represents an edge in each direction).</figcaption>
</figure>

A **directed graph** or **digraph** is a graph in which edges have
orientations.

In one restricted but very common sense of the
term,<sup>[\[1\]](#cite_note-FOOTNOTEBenderWilliamson2010161-1)</sup> a
**directed graph** is an ordered pair
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
  [set](/wiki/Set_(mathematics) "Set (mathematics)") of *vertices* (also
  called *nodes* or *points*);
- <span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
  style="display: none;">$E \subseteq \left\{ {(x,y) \mid (x,y) \in V^{2}\;\text{and}\; x \neq y} \right\}$</span><img
  src="https://wikimedia.org/api/rest_v1/media/math/render/svg/76d5017f509f81427d4f5bb82b1964dd48cbd583"
  class="mwe-math-fallback-image-inline mw-invert"
  style="vertical-align: -1.005ex; width:36.612ex; height:3.343ex;"
  aria-hidden="true"
  alt="{\\displaystyle E\\subseteq \\left\\{(x,y)\\mid (x,y)\\in V^{2}\\;{\\textrm {and}}\\;x\\neq y\\right\\}}" /></span>,
  a [set](/wiki/Set_(mathematics) "Set (mathematics)") of *edges* (also
  called *directed edges*, *directed links*, *directed lines*, *arrows*
  or *arcs*) which are [ordered
  pairs](/wiki/Ordered_pair "Ordered pair") of vertices (that is, an
  edge is associated with two distinct vertices).

To avoid ambiguity, this type of object may be called precisely a
**directed simple graph**. In set theory and graph theory,
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$V^{n}$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/cbfbf91428ae481b792337be15fdae34db6331ad"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:3.135ex; height:2.343ex;"
aria-hidden="true" alt="{\\displaystyle V^{n}}" /></span> denotes the
set of <span class="texhtml mvar"
style="font-style:italic;">n</span>-[tuples](/wiki/Tuple "Tuple") of
elements of
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$V,$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/ace9595e3ce66fdec7e9d30202626accd676b11e"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.671ex; width:2.434ex; height:2.509ex;"
aria-hidden="true" alt="V," /></span> that is, ordered sequences of
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$n$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/a601995d55609f2d9f5e233e36fbe9ea26011b3b"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.395ex; height:1.676ex;"
aria-hidden="true" alt="n" /></span> elements that are not necessarily
distinct.

In the edge
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$(x,y)$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/41cf50e4a314ca8e2c30964baa8d26e5be7a9386"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:5.328ex; height:2.843ex;"
aria-hidden="true" alt="(x,y)" /></span> directed from
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$x$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/87f9e315fd7e2ba406057a97300593c4802b53e4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.33ex; height:1.676ex;"
aria-hidden="true" alt="x" /></span> to
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$y$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/b8a6208ec717213d4317e666f1ae872e00620a0d"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.671ex; width:1.155ex; height:2.009ex;"
aria-hidden="true" alt="y" /></span>, the vertices
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
aria-hidden="true" alt="y" /></span> are called the *endpoints* of the
edge,
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$x$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/87f9e315fd7e2ba406057a97300593c4802b53e4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.33ex; height:1.676ex;"
aria-hidden="true" alt="x" /></span> the *tail* of the edge and
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$y$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/b8a6208ec717213d4317e666f1ae872e00620a0d"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.671ex; width:1.155ex; height:2.009ex;"
aria-hidden="true" alt="y" /></span> the *head* of the edge. The edge is
said to *join*
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
aria-hidden="true" alt="y" /></span> and to be *incident* on
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
not belong to an edge. The edge
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$(y,x)$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/ec736777360ba7cbdabf050bc448d33ec5e266b7"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:5.328ex; height:2.843ex;"
aria-hidden="true" alt="(y,x)" /></span> is called the *inverted edge*
of
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$(x,y)$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/41cf50e4a314ca8e2c30964baa8d26e5be7a9386"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:5.328ex; height:2.843ex;"
aria-hidden="true" alt="(x,y)" /></span>. *[Multiple
edges](/wiki/Multiple_edges "Multiple edges")*, not allowed under the
definition above, are two or more edges with both the same tail and the
same head.

In one more general sense of the term allowing multiple
edges,<sup>[\[1\]](#cite_note-FOOTNOTEBenderWilliamson2010161-1)</sup> a
**directed graph** is an ordered triple
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
  [set](/wiki/Set_(mathematics) "Set (mathematics)") of *vertices* (also
  called *nodes* or *points*);
- <span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
  style="display: none;">$E$</span><img
  src="https://wikimedia.org/api/rest_v1/media/math/render/svg/4232c9de2ee3eec0a9c0a19b15ab92daa6223f9b"
  class="mwe-math-fallback-image-inline mw-invert"
  style="vertical-align: -0.338ex; width:1.776ex; height:2.176ex;"
  aria-hidden="true" alt="E" /></span>, a
  [set](/wiki/Set_(mathematics) "Set (mathematics)") of *edges* (also
  called *directed edges*, *directed links*, *directed lines*, *arrows*
  or *arcs*);
- <span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
  style="display: none;">$\phi:E\rightarrow\left\{ {(x,y) \mid (x,y) \in V^{2}\;\text{and}\; x \neq y} \right\}$</span><img
  src="https://wikimedia.org/api/rest_v1/media/math/render/svg/aa82c43bd4a851ec4fedd13d870336488bb9d413"
  class="mwe-math-fallback-image-inline mw-invert"
  style="vertical-align: -1.005ex; width:40.45ex; height:3.343ex;"
  aria-hidden="true"
  alt="{\\displaystyle \\phi :E\\to \\left\\{(x,y)\\mid (x,y)\\in V^{2}\\;{\\textrm {and}}\\;x\\neq y\\right\\}}" /></span>,
  an *incidence function* mapping every edge to an [ordered
  pair](/wiki/Ordered_pair "Ordered pair") of vertices (that is, an edge
  is associated with two distinct vertices).

To avoid ambiguity, this type of object may be called precisely a
**directed multigraph**.

A *[loop](/wiki/Loop_(graph_theory) "Loop (graph theory)")* is an edge
that joins a vertex to itself. Directed graphs as defined in the two
definitions above cannot have loops, because a loop joining a vertex
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$x$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/87f9e315fd7e2ba406057a97300593c4802b53e4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.33ex; height:1.676ex;"
aria-hidden="true" alt="x" /></span> to itself is the edge (for a
directed simple graph) or is incident on (for a directed multigraph)
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$(x,x)$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/72f9e25892f6d000349b8bb6578a59567efbdd63"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.838ex; width:5.503ex; height:2.843ex;"
aria-hidden="true" alt="{\\displaystyle (x,x)}" /></span> which is not
in
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$\left\{ {(x,y) \mid (x,y) \in V^{2}\;\text{and}\; x \neq y} \right\}$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/25410d40346861db34ad7c20585306c2e0642af1"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -1.005ex; width:31.738ex; height:3.343ex;"
aria-hidden="true"
alt="{\\displaystyle \\left\\{(x,y)\\mid (x,y)\\in V^{2}\\;{\\textrm {and}}\\;x\\neq y\\right\\}}" /></span>.
So to allow loops the definitions must be expanded. For directed simple
graphs, the definition of
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$E$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/4232c9de2ee3eec0a9c0a19b15ab92daa6223f9b"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.338ex; width:1.776ex; height:2.176ex;"
aria-hidden="true" alt="E" /></span> should be modified to
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$E \subseteq \left\{ {(x,y) \mid (x,y) \in V^{2}} \right\}$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/4480299c49fd60e3eaa82f8771bfdff5361f4eff"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -1.005ex; width:25.99ex; height:3.343ex;"
aria-hidden="true"
alt="{\\displaystyle E\\subseteq \\left\\{(x,y)\\mid (x,y)\\in V^{2}\\right\\}}" /></span>.
For directed multigraphs, the definition of
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$\phi$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/72b1f30316670aee6270a28334bdf4f5072cdde4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -0.671ex; width:1.385ex; height:2.509ex;"
aria-hidden="true" alt="\\phi " /></span> should be modified to
<span class="mwe-math-element"><span class="mwe-math-mathml-inline mwe-math-mathml-a11y"
style="display: none;">$\phi:E\rightarrow\left\{ {(x,y) \mid (x,y) \in V^{2}} \right\}$</span><img
src="https://wikimedia.org/api/rest_v1/media/math/render/svg/b4f448ad13540d90792adb6dccdd09210f308aa4"
class="mwe-math-fallback-image-inline mw-invert"
style="vertical-align: -1.005ex; width:29.829ex; height:3.343ex;"
aria-hidden="true"
alt="{\\displaystyle \\phi :E\\to \\left\\{(x,y)\\mid (x,y)\\in V^{2}\\right\\}}" /></span>.
To avoid ambiguity, these types of objects may be called precisely a
**directed simple graph permitting loops** an

</div>
