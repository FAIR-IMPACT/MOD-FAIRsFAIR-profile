---
title: MOD FAIRsFAIR SemanticArtefact Profile (Schema)

language_tabs:
  - json: JSON
  - jsonld: JSON-LD
  - turtle: RDF/Turtle

toc_footers:
  - Version 0.1
  - <a href='#'>MOD FAIRsFAIR SemanticArtefact Profile</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: MOD FAIRsFAIR SemanticArtefact Profile (Schema)
---


# MOD FAIRsFAIR SemanticArtefact Profile `ogc.bbr.template.mod-fairsfair-semanticartefact`

This Building Block is the FAIRsFAIR Profile of the SemanticArtefact from the MOD ontology

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="success">
This building block is <strong><a href="https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/blob/master/build/tests/bbr/template/mod-fairsfair-semanticartefact/" target="_blank">valid</a></strong>
</aside>

# Description

## MOD FAIRsFAIR Semantic Artefact Profile

This is the representation of the FAIRsFAIR Profile of the SemanticArtefact from the MOD ontology. This document provides a human-readable description of the profile.

# Examples

## Examples of MOD Semantic Artefact description complying with the FAIRsFAIR profile.



```json
{
    "dct:title": "my semantic artefact",
    "dct:license": "our license",
    "dct:identifier": "mySA",
    "dct:accessRights": "all",
    "dct:creator": "me",
    "dct:created": "then",
    "dct:description": "my semantic artefact is ...."
}
```

<blockquote class="lang-specific json">
  <p class="example-links">
    <a target="_blank" href="https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/tests/bbr/template/mod-fairsfair-semanticartefact/example_1_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2FFAIR-IMPACT.github.io%2FMOD-FAIRsFAIR-profile%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fmod-fairsfair-semanticartefact%2Fexample_1_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>




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

<blockquote class="lang-specific json">
  <p class="example-links">
    <a target="_blank" href="https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/tests/bbr/template/mod-fairsfair-semanticartefact/example_1_2.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2FFAIR-IMPACT.github.io%2FMOD-FAIRsFAIR-profile%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fmod-fairsfair-semanticartefact%2Fexample_1_2.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>




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
  "@context": "https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefact/context.jsonld"
}
```

<blockquote class="lang-specific jsonld">
  <p class="example-links">
    <a target="_blank" href="https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/tests/bbr/template/mod-fairsfair-semanticartefact/example_1_2.jsonld">Open in new window</a>
    <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2FFAIR-IMPACT.github.io%2FMOD-FAIRsFAIR-profile%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fmod-fairsfair-semanticartefact%2Fexample_1_2.jsonld">View on JSON-LD Playground</a>
</blockquote>




```turtle
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

<blockquote class="lang-specific turtle">
  <p class="example-links">
    <a target="_blank" href="https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/tests/bbr/template/mod-fairsfair-semanticartefact/example_1_2.ttl">Open in new window</a>
</blockquote>


These examples show the minimum feature set as well as a full feature set.


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
description: Schema for the MOD FAIRsFAIR SemanticArtefact Profile
$defs:
  mod:SemanticArtefact:
    allOf:
    - type: object
      properties:
        dcat:keyword:
          type: string
        dcat:landingPage:
          type: string
          format: URI
        dct:accessRights:
          type: string
        dct:accrualMethod:
          type: string
        dct:accrualPeriodicity:
          type: string
        dct:contributor:
          type: string
        dct:created:
          type: string
        dct:creator:
          type: string
        dct:description:
          type: string
        dct:identifier:
          type: string
        dct:language:
          type: string
        dct:license:
          type: string
        dct:modified:
          type: string
        dct:publisher:
          type: string
        dct:relation:
          type: string
        dct:subject:
          type: string
        dct:title:
          type: string
        dct:type:
          type: string
        mod:acronym:
          type: string
        mod:competencyQuestion:
          type: string
        mod:hasFormalityLevel:
          type: string
        mod:status:
          type: string
        mod:URI:
          type: string
          format: URI
        mod:usedEngineeringMethodology:
          type: string
        owl:versionIRI:
          type: string
        prov:wasGeneratedBy:
          type: string
        schema:includedInDataCatalog:
          type: string
      required:
      - dct:title
      - dct:license
      - dct:identifier
      - dct:accessRights
      - dct:creator
      - dct:created
      - dct:description
anyOf:
- $ref: '#/$defs/mod:SemanticArtefact'
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

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2FFAIR-IMPACT.github.io%2FMOD-FAIRsFAIR-profile%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fmod-fairsfair-semanticartefact%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefact/schema.yaml" target="_blank">https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefact/schema.yaml</a>
* JSON version: <a href="https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefact/schema.json" target="_blank">https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefact/schema.json</a>


# JSON-LD Context

```json--ldContext
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

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2FFAIR-IMPACT.github.io%2FMOD-FAIRsFAIR-profile%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fmod-fairsfair-semanticartefact%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefact/context.jsonld" target="_blank">https://FAIR-IMPACT.github.io/MOD-FAIRsFAIR-profile/build/annotated/bbr/template/mod-fairsfair-semanticartefact/context.jsonld</a>

# References

* [MOD Ontology](https://github.com/fair-IMPACT/mod)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile" target="_blank">https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile</a>
* Path:
<code><a href="https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/blob/HEAD/_sources/mod-fairsfair-semanticartefact" target="_blank">_sources/mod-fairsfair-semanticartefact</a></code>

