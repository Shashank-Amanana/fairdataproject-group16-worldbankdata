# FAIR Data Engineering Project-Group 16

The goal of the project is to apply the FAIR principles (Findable, Accessible, Interoperable, Reusable) to a sample of the
World Bank's **[Projects & Operations](https://datacatalog.worldbank.org/search/dataset/0037800/world-bank-projects-operations)**
dataset (2,000 projects, up to 14 per country, downloaded on 2026-09-09, CC BY 4.0, © The World Bank).

Deliverables include the original and the FAIRified dataset, the ontology, the metadata and the SPARQL queries (all linked under [Deliverables](#deliverables)).

| Resource | Persistent identifier |
|---|---|
| Ontology | https://w3id.org/FAIR-course-UT/2026/group16/ont |
| FAIRified data (RDF) | https://w3id.org/FAIR-course-UT/2026/group16/data |
| Original data (CSV) | https://w3id.org/FAIR-course-UT/2026/group16/data/original |
| FAIRified data (cleaned CSV) | https://w3id.org/FAIR-course-UT/2026/group16/data/clean |
| Metadata (dataset and distributions) | https://w3id.org/FAIR-course-UT/2026/group16/metadata |

## Deliverables

| Deliverable | Files |
|---|---|
| Report (PDF) | Submitted through Canvas |
| Semantic data model: visual diagram | [semantic-data-model.png](ontology/semantic-data-model.png) (classes, relations, cardinalities) · [overview](ontology/semantic-data-model-overview.png) |
| Semantic data model: RDF/OWL | [group16-ontology.ttl](ontology/group16-ontology.ttl) · [group16-ontology.rdf](ontology/group16-ontology.rdf) |
| Semantic metadata model (diagram) | [semantic-metadata-model.png](metadata/semantic-metadata-model.png) · [SHACL schemas diagram](metadata/schemas/shacl-schemas.png) |
| Semantic metadata model (SHACL): dataset | [dataset-shape.ttl](metadata/schemas/dataset-shape.ttl) |
| Semantic metadata model (SHACL): distributions (original and RDF) | [distribution-shape.ttl](metadata/schemas/distribution-shape.ttl) |
| Original dataset | [worldbank-projects-original.csv](data/original/worldbank-projects-original.csv) |
| Cleaned dataset in the original format | [worldbank-projects-clean.csv](data/clean/worldbank-projects-clean.csv) · [OpenRefine operations](data/openrefine/openrefine-operations.json) · [OpenRefine project](data/openrefine/group16-worldbank-projects.openrefine.tar.gz) |
| FAIRified dataset in RDF | [worldbank-projects.ttl](data/rdf/worldbank-projects.ttl) · [worldbank-projects.rdf](data/rdf/worldbank-projects.rdf) |
| Metadata record: FAIR Data Point | [fdp.ttl](metadata/records/fdp.ttl) |
| Metadata record: catalog | [catalog.ttl](metadata/records/catalog.ttl) |
| Metadata record: dataset | [dataset.ttl](metadata/records/dataset.ttl) · [public copy](metadata/dataset-public.ttl) |
| Metadata record: distribution, original CSV | [distribution-original-csv.ttl](metadata/records/distribution-original-csv.ttl) |
| Metadata record: distribution, FAIRified RDF | [distribution-rdf.ttl](metadata/records/distribution-rdf.ttl) |
| Metadata record: distribution, cleaned CSV | [distribution-clean-csv.ttl](metadata/records/distribution-clean-csv.ttl) |
| SPARQL queries (competency questions) | [queries/](queries/) |
