## Sparnatural: an intuitive visual SPARQL query builder
{:#sparnatural}

[Sparnatural](cite:cites sparnatural) provides an innovative search paradigm to explore and discover these knowledge graphs. A [presentation video](cite:cites sparnatural-video) demonstrates its features. Technically speaking, Sparnatural is a visual SPARQL query builder, written in Typescript, operating purely on the client. Its only requirement is a SPARQL endpoint to which the queries can be sent. Sparnatural is open-source, under a LGPL license.

Sparnatural visually displays the query pattern with connectors and indentation, as in Figure 1 below:

<figure id="sparnatural-query">
<img src="img/example-query.png" alt="A Sparnatural example query">
<figcaption markdown="block">
A query edited in Sparnatural: _"Archive records that have as provenance a Person who is a member of an organization of type 'Notarial Office', and that are of type 'bill of sale' or 'civil status document'"_
</figcaption>
</figure>

Each line in the query mimics the structure of an RDF triple pattern with a subject type, a predicate, an object type and, optionally, some values. At each step, dropdown lists enable the user to directly see the classes and predicates available.

Values of a criterion can be selected with different widgets (dropdown lists, autocompleted search fields, calendars, etc.) and the set of columns in the result set can be controlled by activating the "eye" icon on the arrows in the query pattern.

Sparnatural also offers the ability to load predefined queries, enabling data publishers to propose sample queries that can be loaded in one click. This can serve as query templates that the users can modify.

While `OPTIONAL` and `FILTER NOT EXISTS` are supported, Sparnatural does not have the objective of covering 100% of SPARQL keywords; currently it does not support `UNION`, `FROM`, or Aggregate functions like `COUNT`.

