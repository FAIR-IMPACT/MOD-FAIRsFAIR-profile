![Build Pages & Deploy](https://github.com/FAIR-IMPACT/MOD-DCAT-profile/actions/workflows/pages/pages-build-deployment/badge.svg)

# MOD-FAIRsFAIR-Profile based on OGC Building Block template

This repository provides a representation of the FAIRsFAIR Profile of the SemanticArtefact and SemanticArtefactDistribution from the MOD ontology based on the OGC Building Block template.

The FAIRsFAIR Profile of the SemanticArtefact from the MOD ontology is defined by considering the results in the vote organised within a FAIRsFAIR workshop for the endorsement level mandatory-recommended-optional for each property to describe a semantic artefact, as reported in the publication:

    - Clement Jonquet, Biswanath Dutta, Luiz O. Bonino da Silva Santos, Robert Pergl, Yann Le Franc. Common Minimum Metadata for FAIR Semantic Artefacts. 2nd Workshop on Ontologies for FAIR and FAIR Ontologies (Onto4FAIR 2023), C. Trojahn; L. O. Bonino da Silva Santos; G. Guizzardi; C. Jonquet, Jul 2023, Sherbrooke, Canada. ⟨[hal-04106533v2](https://hal.science/hal-04106533/)⟩

The report refers to Consensus as:

    - consensus = (0.333 + percentage of votes for the winning option (mandatory, recommended or optional) − sum of percentages of the non-winning options) / 1.333


To create the FAIRsFAIR MOD profile, we considered as required those properties that have consensus > 50%, for the mod:SemanticArtefact class, as no properties had consensus >50% for mod:SemanticArtefactDistribution.

The OGC Building Block template produces:

- MOD-FAIRsFAIR-Profile documentation for the [SemanticArtefact](https://fair-impact.github.io/MOD-FAIRsFAIR-profile/build/generateddocs/slate-build/bbr/template/mod-fairsfair-semanticartefact/) and [SemanticArtefactDistribution](https://fair-impact.github.io/MOD-FAIRsFAIR-profile/build/generateddocs/slate-build/bbr/template/mod-fairsfair-semanticartefactdistribution/)

- MOD-FAIRsFAIR-Profile [Test reports](https://fair-impact.github.io/MOD-FAIRsFAIR-profile/build/tests/report.html)

More information on the OGC approach can be found:
- [Building Blocks](https://blocks.ogc.org/)
- [Examples of using this with typical applications of OGC standards](https://github.com/ogcincubator/bblocks-examples)


# How to use this template

[More information on design and usage](https://github.com/opengeospatial/bblock-template/blob/master/USAGE.md)

To update to the latest template version:
1. add the template repository as a remote:
    ```git remote add template [URL of the template repo]```
2. run git fetch to update the changes
    ```git fetch --all```
3. merge branch from the new remote to your current one
    ```git merge template/[branch to merge] --allow-unrelated-histories```

