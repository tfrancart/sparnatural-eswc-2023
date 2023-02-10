## Ontology-driven configuration of Sparnatural
{:#configuration}

Sparnatural is configured by an OWL ontology, defining which classes and relationships are shown in the interface. The ontology defines the (multilingual) labels and tooltips, icons, or which value selection widget should be used for each predicate. The dropdown list and autocomplete widgets are also associated with a SPARQL query that populates the list or the autocomplete suggestions.

A key aspect of that configuration ontology is that it does not need to be the same as the ontology of the underlying knowledge graph. Classes or properties can be removed or labelled differently; shortcuts can be proposed: a single link in the search interface can correspond to a property path in the underlying graph; classes presented to users can be subsets of the (in general relatively abstract) classes of the underlying ontology.

The decoupling of the search ontology from the graph structure enables to show the same graph in different ways for different users. The configuration ontologies can also be shared, such as the [generic configuration for the ANF demonstrator](cite:cites sparnatural-anf-config-A).


