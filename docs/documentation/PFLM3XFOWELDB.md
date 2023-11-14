# https://en.wikipedia.org/wiki/Graph\_(discrete_mathematics)#Graph

### <span id="Graph" class="mw-headline"><span id="Undirected_graph" class="anchor"></span> Graph</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/w/index.php?title=Graph_(discrete_mathematics)&action=edit&section=1 "Edit section: Graph")<span class="mw-editsection-bracket">\]</span></span>

<figure class="mw-default-size" typeof="mw:File/Thumb">
    <a href="/wiki/File:Undirected.svg" class="mw-file-description">
        <img src="//upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Undirected.svg/220px-Undirected.svg.png"
            class="mw-file-element" decoding="async"
            srcset="//upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Undirected.svg/330px-Undirected.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Undirected.svg/440px-Undirected.svg.png 2x"
            data-file-width="100" data-file-height="100" width="220"
            height="220" />
    </a>
    <figcaption>A graph with three vertices and three edges</figcaption>
</figure>

A **graph** (sometimes called an *undirected graph* to distinguish it
from a [directed graph](#Directed_graph), or a *simple graph* to
distinguish it from a
[multigraph](/wiki/Multigraph "Multigraph"))<sup>[\[1\]](#cite_note-FOOTNOTEBenderWilliamson2010148-1)[\[2\]](#cite_note-2)</sup>
is a [pair](/wiki/Ordered_pair "Ordered pair") <span class="texhtml">*G*
= (*V*, *E*)</span>, where <span class="texhtml mvar"
style="font-style:italic;">V</span> is a set whose elements are called
*vertices* (singular: vertex), and <span class="texhtml mvar"
style="font-style:italic;">E</span> is a set of paired vertices, whose
elements are called *edges* (sometimes *links* or *lines*).

The vertices <span class="texhtml mvar"
style="font-style:italic;">x</span> and <span class="texhtml mvar"
style="font-style:italic;">y</span> of an edge
<span class="texhtml">{*x*, *y*} </span> are called the *endpoints* of
the edge. The edge is said to *join* <span class="texhtml mvar"
style="font-style:italic;">x</span> and <span class="texhtml mvar"
style="font-style:italic;">y</span> and to be *incident* on
<span class="texhtml mvar" style="font-style:italic;">x</span> and
<span class="texhtml mvar" style="font-style:italic;">y</span>. A vertex
may belong to no edge, in which case it is not joined to any other
vertex.

A [multigraph](/wiki/Multigraph "Multigraph") is a generalization that
allows multiple edges to have the same pair of endpoints. In some texts,
multigraphs are simply called
graphs.<sup>[\[3\]](#cite_note-FOOTNOTEBenderWilliamson2010149-3)[\[4\]](#cite_note-4)</sup>

Sometimes, graphs are allowed to contain
*[loops](/wiki/Loop_(graph_theory) "Loop (graph theory)")*, which are
edges that join a vertex to itself. To allow loops, the pairs of
vertices in <span class="texhtml mvar"
style="font-style:italic;">E</span> must be allowed to have the same
node twice. Such generalized graphs are called *graphs with loops* or
simply *graphs* when it is clear from the context that loops are
allowed.

Generally, the set of vertices <span class="texhtml mvar"
style="font-style:italic;">V</span> is supposed to be finite; this
implies that the set of edges is also finite.
<a href="/wiki/Infinite_graph" class="mw-redirect"
title="Infinite graph">Infinite graphs</a> are sometimes considered, but
are more often viewed as a special kind of [binary
relation](/wiki/Binary_relation "Binary relation"), as most results on
finite graphs do not extend to the infinite case, or need a rather
different proof.

An <a href="/wiki/Empty_graph" class="mw-redirect"
title="Empty graph">empty graph</a> is a graph that has an [empty
set](/wiki/Empty_set "Empty set") of vertices (and thus an empty set of
edges). The *order* of a graph is its number of vertices
<span class="texhtml">\|<span class="nowrap"
style="padding-left:0.1em; padding-right:0.1em;">*V*</span>\|</span>.
The *size* of a graph is its number of edges
<span class="texhtml">\|<span class="nowrap"
style="padding-left:0.1em; padding-right:0.1em;">*E*</span>\|</span>.
However, in some contexts, such as for expressing the [computational
complexity](/wiki/Computational_complexity "Computational complexity")
of algorithms, the size is <span class="texhtml">\|<span class="nowrap"
style="padding-left:0.1em; padding-right:0.1em;">*V*</span>\| +
\|<span class="nowrap"
style="padding-left:0.1em; padding-right:0.1em;">*E*</span>\|</span>
(otherwise, a non-empty graph could have size 0). The *degree* or
*valency* of a vertex is the number of edges that are incident to it;
for graphs <sup>[\[5\]](#cite_note-:0-5)</sup>with loops, a loop is
counted twice.

In a graph of order <span class="texhtml">*n*</span>, the maximum degree
of each vertex is <span class="texhtml">*n* âˆ’ 1</span> (or
<span class="texhtml">*n* + 1</span> if loops are allowed, because a
loop contributes 2 to the degree), and the maximum number of edges is
<span class="texhtml">*n*(*n* âˆ’ 1)/2</span> (or
<span class="texhtml">*n*(*n* + 1)/2</span> if loops are allowed).

The edges of a graph define a [symmetric
relation](/wiki/Symmetric_relation "Symmetric relation") on the
vertices, called the *adjacency relation*. Specifically, two vertices
<span class="texhtml mvar" style="font-style:italic;">x</span> and
<span class="texhtml mvar" style="font-style:italic;">y</span> are
*adjacent* if <span class="texhtml">{*x*, *y*} </span> is an edge. A
graph may be fully specified by its [adjacency
matrix](/wiki/Adjacency_matrix "Adjacency matrix")
<span class="texhtml mvar" style="font-style:italic;">A</span>, which is
an <span class="texhtml">*n* Ã— *n*</span> square matrix, with
<span class="texhtml mvar"
style="font-style:italic;">A<sub>ij</sub></span> specifying the number
of connections from vertex <span class="texhtml mvar"
style="font-style:italic;">i</span> to vertex <span class="texhtml mvar"
style="font-style:italic;">j</span>. For a simple graph,
<span class="texhtml">*A<sub>ij</sub>*</span> is either 0, indicating
disconnection, or 1, indicating connection; moreover
<span class="texhtml">*A<sub>ii</sub>* = 0</span> because an edge in a
simple graph cannot start and end at the same vertex. Graphs with
self-loops will be characterized by some or all
<span class="texhtml mvar"
style="font-style:italic;">A<sub>ii</sub></span> being equal to a
positive integer, and multigraphs (with multiple edges between vertices)
will be characterized by some or all <span class="texhtml mvar"
style="font-style:italic;">A<sub>ij</sub></span> being equal to a
positive integer. Undirected graphs will have a
[symmetric](/wiki/Symmetric_matrix "Symmetric matrix") adjacency matrix
(meaning <span class="texhtml">*A<sub>ij</sub>* =
*A<sub>ji</sub>*</span>).

1.  <span id="cite_note-FOOTNOTEBenderWilliamson2010148-1"><span class="mw-cite-backlink">**[^](#cite_ref-FOOTNOTEBenderWilliamson2010148_1-0)**</span>
    <span class="reference-text">[Bender & Williamson
    2010](#CITEREFBenderWilliamson2010), p. 148.</span></span>
2.  <span id="cite_note-2"><span class="mw-cite-backlink">**[^](#cite_ref-2)**</span>
    <span class="reference-text">See, for instance, Iyanaga and Kawada,
    *69 J*, p. 234 or Biggs, p. 4.</span></span>
3.  <span id="cite_note-FOOTNOTEBenderWilliamson2010149-3"><span class="mw-cite-backlink">**[^](#cite_ref-FOOTNOTEBenderWilliamson2010149_3-0)**</span>
    <span class="reference-text">[Bender & Williamson
    2010](#CITEREFBenderWilliamson2010), p. 149.</span></span>
4.  <span id="cite_note-4"><span class="mw-cite-backlink">**[^](#cite_ref-4)**</span>
    <span class="reference-text">Graham et al., p. 5.</span></span>
5.  <span id="cite_note-:0-5"><span class="mw-cite-backlink">**[^](#cite_ref-:0_5-0)**</span>
    <span class="error mw-ext-cite-error" lang="en" dir="ltr">Cite
    error: The named reference `:0` was invoked but never defined (see
    the [help
    page](/wiki/Help:Cite_errors/Cite_error_references_no_text "Help:Cite errors/Cite error references no text")).</span></span>

