# movable: an RDF Schema for making RDF schemas be movable

This schema is helpful for writing "movable" RDF schemas. Schemas (also called ontologies or vocabularies) which are movable retain their semantics even when moved to a different URL.  As such, while the original version of this document is hosted at https://sandhawke.github.io/movable, it is possible (and recommended) to use this schema in a way which does not involve trusting either github or the author (username sandhawke). 

In fact, due to limitions of github hosting, the namespace URL for this schema is different for different formats.  This would normally break interoperability, but with movable schemas, it's fine:

|Format|Media Type|Namespace URL|
|:----:|:---:|:------------|
|Turtle|text/turtle|<https://sandhawke.github.io/movable/schema.ttl#>
|JSON-LD|application/ld+json|<https://sandhawke.github.io/movable/schema.jsonld#>
|JSON-LD|text/html with script tag|<https://sandhawke.github.io/movable/schema/>

More details TBD.
