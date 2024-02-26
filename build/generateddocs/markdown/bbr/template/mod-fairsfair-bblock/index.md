
# MOD-FAIRsFAIR-Profile (Schema)

`ogc.bbr.template.mod-fairsfair-bblock` *v0.1*

This Building Block serves as a template to create new ones

[*Status*](http://www.opengis.net/def/status): Under development

## Description

## MOD-FAIRsFAIR-Profile

This is the representation of the FAIRsFAIR Profile for MOD. This document provides a human-readable description of the Profile.

## Examples

### Examples of MOD descriptions complying with the FAIRsFAIR profile.
This is the content of the example.
#### json
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

#### jsonld
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

#### ttl
```ttl
@prefix ns1: <dct:> .

[] ns1:accessRights "all" ;
    ns1:created "then" ;
    ns1:creator "me" ;
    ns1:description "my semantic artefact is ...." ;
    ns1:identifier "mySA" ;
    ns1:license "our license" ;
    ns1:title "my semantic artefact" .


```

## Schema

```yaml
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

Links to the schema:

* YAML version: [schema.yaml](https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/schema.json)
* JSON version: [schema.json](https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/schema.yaml)


# JSON-LD Context

```jsonld
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

You can find the full JSON-LD context here:
[context.jsonld](https://raw.githubusercontent.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile/master/build/annotated/bbr/template/mod-fairsfair-bblock/context.jsonld)

## Sources

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile](https://github.com/FAIR-IMPACT/MOD-FAIRsFAIR-profile)
* Path: `_sources/mod-fairsfair-bblock`

