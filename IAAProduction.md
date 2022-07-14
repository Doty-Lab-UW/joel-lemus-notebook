---
bibliography: references.bib
---

# IAA (auxin) Production

## Summary of Findings

## Introduction

## Literature Review [@olanrewaju2017]

-   IAA is an auxin, stimulates plant growth/development.

-   Bacteria can regulate plant growth by changing the levels of auxin in plant roots/shoots

-   5 ("at least 3") synthesis pathways for IAA: indole pyruvic acid pathway, indole acetamide pathway, indole acetaldoxime/indoleacetonitrile pathway, indole acetaldehyde pathway, tryptamine pathway

-   Bacteria can have up to 3 different pathways for this

-   IPyA path enzymes: tryptophan aminotransferase --\> indole-3-pyruvic acid decarboxylase --\> indole-3-acetaldehyde oxidase (IAH path) \*or\* non-enzymatic decarboxylation of IPyA

-   IAM path: tryptophan 2-monooxygenase --\> indole acetamide hydrolase

-   IAOx/IAN path: unknown --\> acetaldoxime dehydratase --\> nitrilase or (nitrile hydratase --\> indole acetamide hydrolase, part of IAM path)

-   IAH pathway: tryptophan side chain oxidase --\> indole-3-acetaldehyde oxidase

-   tryptamine path: tryptophan decarboxylase --\> amine oxidase --\> indole-3-acetaldehyde oxidase (IAH path)

##### What to look for

Carrier proteins for auxin (PINs, ABCB, AUX1/LAX)

## Methods

## Results

All strains have 4.2.1.20, 4.1.1.48, 5.3.1.24, 2.4.2.18. Tryptophan synthesis via indole (<https://www.kegg.jp/pathway/map00400>). IAA synthesis may be possible from just indole, Trp independent synthesis (<https://www.genome.jp/entry/R08609+RC00209>) addition of deaminated Ser via 4.2.1.20 like enzyme??? May not be possible because you need a schiff base (review PLP stuff). rule out all other paths before looking further.

IAM path highly unlikely, none have iaaM/1.13.12.3 tryptophan 2-monooxygenase, only PTD1 appears to have TAM path. IPyA seems unlikely, no tryptophan aminotransferase, other amino acid oxidases might work (not 1.4.3.2)

+-----------------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| tStrain         | Genes                                        | Loci                                      | Notes                                                                                                                                                                       |
+=================+==============================================+===========================================+=============================================================================================================================================================================+
| 11R-A           | IAA acetyltransferase (2.3.1.-)              | Contig 10                                 | no tryptophan N-monooxygenase,                                                                                                                                              |
+-----------------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 11R-B1          | 4.1.1.28 aromatic-L-amino-acid decarboxylase | Contig 2                                  | 4.1.1.105 is specific to tryptophan, but 4.1.1.28 might work too?                                                                                                           |
+-----------------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| PTD1            | IAA acetyltransferase                        | scaffold00002, 10                         | no idea what this does, implies some sort of interaction with IAA                                                                                                           |
|                 |                                              |                                           |                                                                                                                                                                             |
|                 | 3.5.1.4 acetamidase                          | scaffold00008                             | PTD1 could maybe follow the TAM pathway for IAA synthesis. these are all the generic version of the enzymes and theyre all on different contigs, which is a little worrying |
|                 |                                              |                                           |                                                                                                                                                                             |
|                 | 4.1.1.28                                     | scaffold00001, 13                         |                                                                                                                                                                             |
|                 |                                              |                                           |                                                                                                                                                                             |
|                 | 1.4.3.4 monoamine oxidase                    | scaffold00005                             |                                                                                                                                                                             |
|                 |                                              |                                           |                                                                                                                                                                             |
|                 | 1.2.1.3 aldehyde dehydrogenase               | scaffold00001, 2, 3, 4, 6, 11, 12, 14, 46 |                                                                                                                                                                             |
+-----------------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| R10             |                                              |                                           |                                                                                                                                                                             |
+-----------------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| SherDot1        |                                              |                                           |                                                                                                                                                                             |
+-----------------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| WP5             |                                              |                                           |                                                                                                                                                                             |
+-----------------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| WW5             |                                              |                                           |                                                                                                                                                                             |
+-----------------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

## Outcomes
