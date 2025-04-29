---
title: ReproLake
---

The ReproLake is a publicly available triplestore that contains information on publicly available neuroimaging datasets. The data within the ReproLake conforms to the NIDM standard and can be queried by the Neurobagel user interface or via a SPARQL API. Researchers using PyNIDM can also generate a local triplestore (i.e. a ReproPond) from their data which can be queried through PyNIDM and can also be added to Neurobagel as a local private node.

## Development status

The ReproLake is a public production data store that is currently hosted via a Stardog cloud based endpoint.

## Innovation

The ReproLake uses the NIDM and BIDS standards to provide a formal data store for neuroimaging data.  Using the same standards and tools, researchers are also able to generate their own local data stores that they can query and interrogate.

## How to use

[Neurobagel](/resources/tools/neurobagel/) queries will access the ReproLake.

The ReproLake can also be accessed directly using SPARQL queries.

## Links

- Tutorial: [Sharing and Searching Metadata Using a ReproPond and the ReproLake](/resources/tutorials/pond-lake/)
