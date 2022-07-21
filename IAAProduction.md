---
bibliography: references.bib
---

# IAA (auxin) Production

## Summary of Findings

The 11R-B1 and PTD1 strains are predicted to produce IAA through the TAM pathway due to the presence of aromatic-L-amino-acid decarboxylase, monoamine oxidase, and aldehyde dehydrogenase coding sequences. No other strains were predicted to produce IAA using any other pathway.

## Introduction

I am looking for coding sequences that are part of pathways for producing auxin. Auxin is a plant growth hormone. A strain that is able to produce auxin will be beneficial because it will help the plant grow. The strains being used are 11R-A, 11R-B1, PTD1, R10, SherDot1, WP5, and WW5. I will be using Geneious Prime to look for the CDSs and KEGG to find which pathways are viable, along with Olanrewaju's paper summarizing the pathways for making IAA (auxin).

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

## Methods

I reviewed the pathways for IAA production using Olanrewaju's paper and the KEGG website. I used Geneious Prime to search for coding sequences that matched with the enzymes necessary to carry out one of those pathways. I then predicted whether each strain could produce IAA based on the presence of those coding sequences.

## Results

All strains have 4.2.1.20, 4.1.1.48, 5.3.1.24, 2.4.2.18. Tryptophan synthesis via indole (<https://www.kegg.jp/pathway/map00400>). IAA synthesis may be possible from just indole, Trp-independent pathway with IAA acetyltransferase (aka tryptophan acetyltransferase, coded by ysnE).

IAM path highly unlikely, none have iaaM/1.13.12.3 tryptophan 2-monooxygenase, only PTD1 appears to have TAM path. IPyA seems unlikely, no tryptophan aminotransferase, other amino acid oxidases might work (not 1.4.3.2). No 1.14.14.156, other monooxygenases present though.

+----------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Strain   | Genes                                        | Loci                                      | Notes                                                                                                                                                                       |
+==========+==============================================+===========================================+=============================================================================================================================================================================+
| 11R-A    | IAA acetyltransferase (2.3.1.-)              | Contig 10                                 | no tryptophan N-monooxygenase (1.14.14.156), doesnt appear to have any other CDSs related to IAA formation, need to find out what IAA acetyltransferase does                |
|          |                                              |                                           |                                                                                                                                                                             |
|          | 1.2.1.3                                      |                                           |                                                                                                                                                                             |
+----------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 11R-B1   | 4.1.1.28 aromatic-L-amino-acid decarboxylase | Contig 2                                  | 4.1.1.105 is specific to tryptophan, but 4.1.1.28 might work too?                                                                                                           |
|          |                                              |                                           |                                                                                                                                                                             |
|          | 1.4.3.4                                      | Contig 3, 4, 7                            | Could also follow the TAM pathway, same as PTD1                                                                                                                             |
|          |                                              |                                           |                                                                                                                                                                             |
|          | 1.2.1.3                                      |                                           |                                                                                                                                                                             |
+----------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| PTD1     | IAA acetyltransferase                        | scaffold00002, 10                         | no idea what this does, implies some sort of interaction with IAA                                                                                                           |
|          |                                              |                                           |                                                                                                                                                                             |
|          | 3.5.1.4 acetamidase                          | scaffold00008                             | PTD1 could maybe follow the TAM pathway for IAA synthesis. these are all the generic version of the enzymes and theyre all on different contigs, which is a little worrying |
|          |                                              |                                           |                                                                                                                                                                             |
|          | 4.1.1.28                                     | scaffold00001, 13                         |                                                                                                                                                                             |
|          |                                              |                                           |                                                                                                                                                                             |
|          | 1.4.3.4 monoamine oxidase                    | scaffold00005                             |                                                                                                                                                                             |
|          |                                              |                                           |                                                                                                                                                                             |
|          | 1.2.1.3 aldehyde dehydrogenase               | scaffold00001, 2, 3, 4, 6, 11, 12, 14, 46 |                                                                                                                                                                             |
+----------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| R10      | 1.2.1.3                                      |                                           | doesn't appear to have anything outside of the aldehyde dehydrogenase, unlikely to produce IAA                                                                              |
+----------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| SherDot1 | 1.2.1.3                                      | Contig 9                                  | no 4.1.1.28 or anything like it, unlikely to produce IAA                                                                                                                    |
|          |                                              |                                           |                                                                                                                                                                             |
|          | 1.4.3.4                                      |                                           |                                                                                                                                                                             |
+----------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| WP5      | 1.2.1.3                                      |                                           | doesn't appear to have anything outside of the aldehyde dehydrogenase, unlikely to produce IAA                                                                              |
+----------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| WW5      | 1.2.1.3                                      |                                           | doesn't appear to have anything outside of the aldehyde dehydrogenase, unlikely to produce IAA                                                                              |
+----------+----------------------------------------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

## Outcomes

Due to the presence of CDSs for enzymes that would produce IAA through the TAM pathway, 11R-B1 and PTD1 are predicted to produce IAA. Since none of the other strains have the CDSs necessary to produce IAA through any of the pathways, they are predicted to not produce IAA. Strains 11R-A and PTD1 both have IAA acetyltransferase. 11R-A has this despite not being predicted to produce IAA, so maybe it just interacts with it after another organism makes it. PTD1 has this but 11R-B1 doesn't, despite them both being predicted to be able to make IAA. This may mean that the ability to produce IAA does not mean that IAA acetyltransferase will be present. IAA acetyltransferase (or IAA transacetylase/tryptophan acetyltransferase) may be part of a tryptophan-independent pathway [@idris2007], an uncharacterized tryptophan-dependent pathway involving indole-3-lactic acid and tryptophol, or the TAM/IPA pathways [@shao2021]. Further research is required to determine if 11R-A and PTD1 could produce auxin using IAA acetyltransferase.
