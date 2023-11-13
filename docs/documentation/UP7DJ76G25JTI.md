# https://en.wikipedia.org/wiki/Graph_database#Labeled-property_graph


### <span id="Labeled-property_graph" class="mw-headline">Labeled-property graph</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/w/index.php?title=Graph_database&action=edit&section=1 "Edit section: Labeled-property graph")<span class="mw-editsection-bracket">\]</span></span>

A labeled-property graph model is represented by a set of nodes,
relationships, properties, and labels. Both nodes of data and their
relationships are named and can store properties represented by
<a href="/wiki/Attribute%E2%80%93value_pair" class="mw-redirect"
title="Attributeâ€“value pair">keyâ€“value pairs</a>. Nodes can be
labelled to be grouped. The edges representing the relationships have
two qualities: they always have a start node and an end node, and are
directed;<sup>[\[1\]](#cite_note-1)</sup> making the graph a [directed
graph](/wiki/Directed_graph "Directed graph"). Relationships can also
have properties. This is useful in providing additional metadata and
semantics to relationships of the nodes.<sup>[\[2\]](#cite_note-2)</sup>
Direct storage of relationships allows a
[constant-time](/wiki/Time_complexity#Constant_time "Time complexity")
[traversal](/wiki/Graph_traversal "Graph traversal").<sup>[\[3\]](#cite_note-:32-3)</sup>


1.  <span id="cite_note-1"><span class="mw-cite-backlink">**[^](#cite_ref-1)**</span>
    <span class="reference-text"></span></span>
    Frisendal, Thomas (2017-09-22). <a
    href="http://www.dataversity.net/property-graphs-swiss-army-knife-data-modeling/"
    class="external text" rel="nofollow">"Property Graphs"</a>.
    *graphdatamodeling.com*<span class="reference-accessdate">.
    Retrieved
    <span class="nowrap">2018-10-23</span></span>.<span class="Z3988"
    title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=graphdatamodeling.com&amp;rft.atitle=Property+Graphs&amp;rft.date=2017-09-22&amp;rft.aulast=Frisendal&amp;rft.aufirst=Thomas&amp;rft_id=http%3A%2F%2Fwww.dataversity.net%2Fproperty-graphs-swiss-army-knife-data-modeling%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AGraph+database"></span>
2.  <span id="cite_note-2"><span class="mw-cite-backlink">**[^](#cite_ref-2)**</span>
    <span class="reference-text">Das, S; Srinivasan, J; Perry, Matthew;
    Chong, Eugene; Banerjee, Jay (2014-03-24).
    <a href="https://www.researchgate.net/publication/264702160"
    class="external text" rel="nofollow">"A Tale of Two Graphs: Property
    Graphs as RDF in Oracle"</a>.<span class="Z3988"
    title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=A+Tale+of+Two+Graphs%3A+Property+Graphs+as+RDF+in+Oracle&amp;rft.date=2014-03-24&amp;rft.aulast=Das&amp;rft.aufirst=S&amp;rft.au=Srinivasan%2C+J&amp;rft.au=Perry%2C+Matthew&amp;rft.au=Chong%2C+Eugene&amp;rft.au=Banerjee%2C+Jay&amp;rft_id=https%3A%2F%2Fwww.researchgate.net%2Fpublication%2F264702160&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AGraph+database"></span>
    <span class="cs1-hidden-error citation-comment">`{{`[`cite journal`](/wiki/Template:Cite_journal "Template:Cite journal")`}}`:
    </span><span class="cs1-hidden-error citation-comment">Cite journal
    requires `|journal=`
    ([help](/wiki/Help:CS1_errors#missing_periodical "Help:CS1 errors"))</span></span></span>
3.  <span id="cite_note-:32-3"><span class="mw-cite-backlink">**[^](#cite_ref-:32_3-0)**</span>
    <span class="reference-text">Have, Christian Theil; Jensen, Lars
    Juhl (2013-10-17).
    <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3842757"
    class="external text" rel="nofollow">"Are graph databases ready for
    bioinformatics?"</a>. *Bioinformatics*. **29** (24): 3107â€“3108.
    <a href="/wiki/Doi_(identifier)" class="mw-redirect"
    title="Doi (identifier)">doi</a>:<a href="https://doi.org/10.1093%2Fbioinformatics%2Fbtt549"
    class="external text" rel="nofollow">10.1093/bioinformatics/btt549</a>.
    <a href="/wiki/ISSN_(identifier)" class="mw-redirect"
    title="ISSN (identifier)">ISSN</a> <a href="https://www.worldcat.org/issn/1460-2059" class="external text"
    rel="nofollow">1460-2059</a>.
    <a href="/wiki/PMC_(identifier)" class="mw-redirect"
    title="PMC (identifier)">PMC</a> <span class="cs1-lock-free"
    title="Freely accessible"><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3842757"
    class="external text" rel="nofollow">3842757</a></span>.
    <a href="/wiki/PMID_(identifier)" class="mw-redirect"
    title="PMID (identifier)">PMID</a> <a href="https://pubmed.ncbi.nlm.nih.gov/24135261" class="external text"
    rel="nofollow">24135261</a>.<span class="Z3988"
    title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=Bioinformatics&amp;rft.atitle=Are+graph+databases+ready+for+bioinformatics%3F&amp;rft.volume=29&amp;rft.issue=24&amp;rft.pages=3107-3108&amp;rft.date=2013-10-17&amp;rft_id=https%3A%2F%2Fwww.ncbi.nlm.nih.gov%2Fpmc%2Farticles%2FPMC3842757%23id-name%3DPMC&amp;rft.issn=1460-2059&amp;rft_id=info%3Apmid%2F24135261&amp;rft_id=info%3Adoi%2F10.1093%2Fbioinformatics%2Fbtt549&amp;rft.aulast=Have&amp;rft.aufirst=Christian+Theil&amp;rft.au=Jensen%2C+Lars+Juhl&amp;rft_id=https%3A%2F%2Fwww.ncbi.nlm.nih.gov%2Fpmc%2Farticles%2FPMC3842757&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AGraph+database"></span></span></span>

