# QUDT — Ontoshire URL-publishing test

**Not an official QUDT distribution.** A test of Ontoshire publishing an
ontology straight from a URL, in the shape QUDT would actually use.

The repository deliberately contains **no RDF**. `ontoshire.ttl` points at
`https://qudt.org/3.5.2/qudt-all` — the built, versioned artefact QUDT serves,
byte-identical to the copy inside its GitHub release ZIP. QUDT's own repository
tree holds Maven templates whose ontology IRI reads `$$QUDT_VERSION$$` until
release-time substitution, so the tree is not publishable as-is.

QUDT is CC BY 4.0; attribution to QUDT.org.
