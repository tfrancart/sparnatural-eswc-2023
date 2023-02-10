## Demonstrators
{:#demonstrators}

The [French National Archives (ANF)](https://www.archives-nationales.culture.gouv.fr/) and the [French National Library (BNF)](https://www.bnf.fr) conducted a project to add features to Sparnatural and to build two demonstrators to test its deployment on their respective knowledge graphs. The project was successfully concluded in June 2022 by a [presentation at the ANF](cite:cites sparnatural-presentation).

The [demonstrator of the ANF](cite:cites sparnatural-anf-demo) allows exploring a dataset based on [RIC-O](cite:cites ric-o), of about 50 million triples describing notarial archives. The demonstrator proposes two configurations of Sparnatural to navigate the same data: a generic one, that could be used for any RIC-O-based knowledge graph, and a more precise, showing specific criteria for notarial archives.

The [demonstrator of the BNF](cite:cites sparnatural-bnf-demo) allows querying the data already accessible in the data.bnf.fr portal, of about 600 million triples, and based on an [LRM-like](cite:cites lrm) ontology. The performance of the SPARQL endpoint was sufficient to allow to deploy Sparnatural without further performance tuning.

The project included three workshops to confront end-users with the tool and gather feedback. Users were mostly enthusiastic, but some were lost by this new search paradigm. Some feedback was taken into account, such as the inclusion of the query execution button, or the "reset" button.