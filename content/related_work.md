## Related work
{:#related_work}

Sparnatural builds on the visual paradigm of [ResearchSpace semantic search component](cite:cites researchspace), but improves the user experience and is more expressive, with support for `OPTIONAL` and `NOT EXISTS`.

[RDFExplorer](cite:cites rdfexplorer) is another graph-based SPARQL builder. Sparnatural is less expressive than RDFExplorer (in particular it can generate only tree-shaped queries, not complete basic graph pattern), but we believe more end-user-friendly. The presentation of [RDFExplorer](cite:cites rdfexplorer) cites [Bhowmick et al.](cite:cites bhowmick) to summarize the challenges of _visual graph querying paradigm_: (1) development of graph queries requires a considerable cognitive effort; (2) users need to be able to express their goal in a systematic and correct manner, which is antagonistic with the goal of catering to lay users; (3) it is more intuitive to "draw" graph queries than to write them, which implies the need for intuitive visual interfaces. 
In the same family of tools, [Visual SPARQL Builder](cite:cites visual_sparql_builder) proposes a visual query building pane similar to RDFExplorer, while [A-QuB](cite:cites a-qub) is more form-based.
Sparnatural adresses the challenges of visual graph querying by providing the following set of features : UX is intuitive and "gamifies" the query experience; dynamic results can be provided on-the-fly; example queries can be loaded; some level of non-emptiness garantee are provided.
