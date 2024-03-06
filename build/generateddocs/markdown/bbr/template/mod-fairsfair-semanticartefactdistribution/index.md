
# MOD FAIRsFAIR SemanticArtefactDistribution Profile (Schema)

`ogc.bbr.template.mod-fairsfair-semanticartefactdistribution` *v0.1*

This Building Block is the FAIRsFAIR Profile of the SemanticArtefactDistribution from the MOD ontology

[*Status*](http://www.opengis.net/def/status): Under development

## Description

## MOD FAIRsFAIR Semantic Artefact Distribution Profile

This is the representation of the FAIRsFAIR Profile of the SemanticArtefactDistribution from the MOD ontology. This document provides a human-readable description of the profile.

## Examples

### Examples of MOD Semantic Artefact Distribution description complying with the FAIRsFAIR profile.
This example shows a full feature set.
#### json
```json
{
    "dcat:keyword": "keyword",
    "dcat:landingPage": "https://example.org/",
    "dct:accessRights": "all",
    "dct:accrualMethod": "accrual method",
    "dct:accrualPeriodicity": "1 year",
    "dct:contributor": "me",
    "dct:created": "2024",
    "dct:creator": "me",
    "dct:description": "my semantic artefact is ....",
    "dct:identifier": "mySA",
    "dct:language": "English",
    "dct:license": "our license",
    "dct:modified": "2024",
    "dct:publisher": "2024",
    "dct:relation": "schema:keywords",
    "dct:subject": "semantic artefacts",
    "dct:title": "my semantic artefact",
    "dct:type": "semantic artefact",
    "mod:acronym": "mySA",
    "mod:competencyQuestion": "A set of questions made to build an ontology at the design time.",
    "mod:hasFormalityLevel": "1",
    "mod:status": "prime",
    "mod:URI": "https://example.org/",
    "mod:usedEngineeringMethodology": "snap",
    "owl:versionIRI": "https://w3id.org/modp/2.0",
    "prov:wasGeneratedBy": "me",
    "schema:includedInDataCatalog": "none"
}
```

#### jsonld
```jsonld
{
  "dcat:keyword": "keyword",
  "dcat:landingPage": "https://example.org/",
  "dct:accessRights": "all",
  "dct:accrualMethod": "accrual method",
  "dct:accrualPeriodicity": "1 year",
  "dct:contributor": "me",
  "dct:created": "2024",
  "dct:creator": "me",
  "dct:description": "my semantic artefact is ....",
  "dct:identifier": "mySA",
  "dct:language": "English",
  "dct:license": "our license",
  "dct:modified": "2024",
  "dct:publisher": "2024",
  "dct:relation": "schema:keywords",
  "dct:subject": "semantic artefacts",
  "dct:title": "my semantic artefact",
  "dct:type": "semantic artefact",
  "mod:acronym": "mySA",
  "mod:competencyQuestion": "A set of questions made to build an ontology at the design time.",
  "mod:hasFormalityLevel": "1",
  "mod:status": "prime",
  "mod:URI": "https://example.org/",
  "mod:usedEngineeringMethodology": "snap",
  "owl:versionIRI": "https://w3id.org/modp/2.0",
  "prov:wasGeneratedBy": "me",
  "schema:includedInDataCatalog": "none",
  "@context": "https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefactdistribution/context.jsonld"
}
```

#### ttl
```ttl
@prefix dcat1: <http://www.w3.org/ns/dca#> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix mod: <https://w3id.org/mod#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix prov: <http://www.w3.org/ns/prov#> .
@prefix schema: <https://schema.org/> .

[] dct:accessRights "all" ;
    dct:accrualMethod "accrual method" ;
    dct:accrualPeriodicity "1 year" ;
    dct:contributor "me" ;
    dct:created "2024" ;
    dct:creator "me" ;
    dct:description "my semantic artefact is ...." ;
    dct:identifier "mySA" ;
    dct:language "English" ;
    dct:license "our license" ;
    dct:modified "2024" ;
    dct:publisher "2024" ;
    dct:relation "schema:keywords" ;
    dct:subject "semantic artefacts" ;
    dct:title "my semantic artefact" ;
    dct:type "semantic artefact" ;
    owl:versionIRI "https://w3id.org/modp/2.0" ;
    dcat1:keyword "keyword" ;
    dcat1:landingPage "https://example.org/" ;
    prov:wasGeneratedBy "me" ;
    schema:includedInDataCatalog "none" ;
    mod:URI "https://example.org/" ;
    mod:acronym "mySA" ;
    mod:competencyQuestion "A set of questions made to build an ontology at the design time." ;
    mod:hasFormalityLevel "1" ;
    mod:status "prime" ;
    mod:usedEngineeringMethodology "snap" .


```

## Schema

```yaml
$schema: https://json-schema.org/draft/2020-12/schema
description: Schema for the MOD FAIRsFAIR SemanticArtefactDistribution Profile
$defs:
  mod:SemanticArtefactDistribution:
    allOf:
    - type: object
      properties:
        dcat:accessURL:
          type: string
          format: URI
        dcat:byteSize:
          type: string
        dcat:downloadURL:
          type: string
          format: URI
        dct:accessRights:
          type: string
        dct:description:
          type: string
        dct:modified:
          type: string
        dct:title:
          type: string
        mod:authorProperty:
          type: string
        mod:definitionProperty:
          type: string
        mod:hasRepresentationLanguage:
          type: string
        mod:hasSyntax:
          type: string
        mod:hierarchyProperty:
          type: string
        mod:metrics:
          type: string
        mod:obsoleteParent:
          type: string
        mod:obsoleteProperty:
          type: string
        mod:prefLabelProperty:
          type: string
        mod:sampleQueries:
          type: string
        mod:synonymProperty:
          type: string
anyOf:
- $ref: '#/$defs/mod:SemanticArtefactDistribution'
x-jsonld-prefixes:
  dcat: http://www.w3.org/ns/dca#
  dct: http://purl.org/dc/terms/
  mod: https://w3id.org/mod#
  owl: http://www.w3.org/2002/07/owl#
  prov: http://www.w3.org/ns/prov#
  rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
  rdfs: http://www.w3.org/2000/01/rdf-schema#
  schema: https://schema.org/
  xsd: http://www.w3.org/2001/XMLSchema#

```

Links to the schema:

* YAML version: [schema.yaml](https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefactdistribution/schema.json)
* JSON version: [schema.json](https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefactdistribution/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "dcat": "http://www.w3.org/ns/dca#",
    "dct": "http://purl.org/dc/terms/",
    "mod": "https://w3id.org/mod#",
    "owl": "http://www.w3.org/2002/07/owl#",
    "prov": "http://www.w3.org/ns/prov#",
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "schema": "https://schema.org/",
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefactdistribution/context.jsonld)

## Sources

* [MOD Ontology](https://github.com/fair-IMPACT/mod)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile](https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile)
* Path: `_sources/mod-fairsfair-semanticartefactdistribution`

