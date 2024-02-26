---
title: MOD-FAIRsFAIR-Profile (Schema)

language_tabs:
  - json: JSON
  - jsonld: JSON-LD
  - turtle: RDF/Turtle

toc_footers:
  - Version 0.1
  - <a href='#'>MOD-FAIRsFAIR-Profile</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: MOD-FAIRsFAIR-Profile (Schema)
---


# MOD-FAIRsFAIR-Profile `ogc.bbr.template.mod-fairsfair-bblock`

This Building Block serves as a template to create new ones

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="success">
This building block is <strong><a href="https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/blob/master/build/tests/bbr/template/mod-fairsfair-bblock/" target="_blank">valid</a></strong>
</aside>

# Description

## MOD-FAIRsFAIR-Profile

This is the representation of the FAIRsFAIR Profile for MOD. This document provides a human-readable description of the Profile.

# Examples

## Examples of MOD descriptions complying with the FAIRsFAIR profile.



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
    <a target="_blank" href="https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/tests/bbr/template/mod-fairsfair-bblock/example_1_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fraw.githubusercontent.com%2FFAIR-IMPACT%2FMOD-FAIRsFAIR-profile%2Fmaster%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fmod-fairsfair-bblock%2Fexample_1_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>




```jsonld
{
  "dct:title": "my semantic artefact",
  "dct:license": "our license",
  "dct:identifier": "mySA",
  "dct:accessRights": "all",
  "dct:creator": "me",
  "dct:created": "then",
  "dct:description": "my semantic artefact is ....",
  "@context": "https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/context.jsonld"
}
```

<blockquote class="lang-specific jsonld">
  <p class="example-links">
    <a target="_blank" href="https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/tests/bbr/template/mod-fairsfair-bblock/example_1_1.jsonld">Open in new window</a>
    <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fraw.githubusercontent.com%2FFAIR-IMPACT%2FMOD-FAIRsFAIR-profile%2Fmaster%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fmod-fairsfair-bblock%2Fexample_1_1.jsonld">View on JSON-LD Playground</a>
</blockquote>




```turtle
@prefix ns1: <dct:> .

[] ns1:accessRights "all" ;
    ns1:created "then" ;
    ns1:creator "me" ;
    ns1:description "my semantic artefact is ...." ;
    ns1:identifier "mySA" ;
    ns1:license "our license" ;
    ns1:title "my semantic artefact" .


```

<blockquote class="lang-specific turtle">
  <p class="example-links">
    <a target="_blank" href="https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/tests/bbr/template/mod-fairsfair-bblock/example_1_1.ttl">Open in new window</a>
</blockquote>


This is the content of the example.


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
description: Schema for MOD-FAIRsFAIR-Profile building block
defs:
  mod:SemanticArtefact:
    type: object
    properties:
      dct:title:
        type: string
      dct:license:
        type: string
      dct:identifier:
        type: string
      dct:accessRights:
        type: string
      dct:creator:
        type: string
      dct:created:
        type: string
      dct:description:
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
- ref: '#/$defs/mod:SemanticArtefact'
x-jsonld-prefixes:
  mod: https://w3id.org/mod#
  rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
  rdfs: http://www.w3.org/2000/01/rdf-schema#
  xsd: http://www.w3.org/2001/XMLSchema#

```

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fraw.githubusercontent.com%2FFAIR-IMPACT%2FMOD-FAIRsFAIR-profile%2Fmaster%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fmod-fairsfair-bblock%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/schema.yaml" target="_blank">https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/schema.yaml</a>
* JSON version: <a href="https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/schema.json" target="_blank">https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/schema.json</a>


# JSON-LD Context

```json--ldContext
{
  "@context": {
    "mod": "https://w3id.org/mod#",
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "@version": 1.1
  }
}
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fraw.githubusercontent.com%2FFAIR-IMPACT%2FMOD-FAIRsFAIR-profile%2Fmaster%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fmod-fairsfair-bblock%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/context.jsonld" target="_blank">https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile" target="_blank">https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile</a>
* Path:
<code><a href="https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/blob/HEAD/_sources/mod-fairsfair-bblock" target="_blank">_sources/mod-fairsfair-bblock</a></code>

