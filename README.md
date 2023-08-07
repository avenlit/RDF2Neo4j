# RDF2Neo4j
it is a baby project haven't been built up correctly yet trying to import rdf to Neo4j DB


总结一下：protege生成的ttl文件需要将inferred axioms也一并生成了，最后可以使用rdf2rdf转换一下，import进Neo4j中，并且值得注意的是，删去label prefix需要handleVocabUris ignore，保留实例需要rdf2rdf转换，而保留type关系需要handleRDFtypes：keep
