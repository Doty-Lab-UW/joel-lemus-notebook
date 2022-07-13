# Phosphate Solubilization

## Summary of Findings

## Introduction

We are using Geneious Prime to predict if certain strains of endophytic bacteria can solubilize phosphate. This will give me further experience with Geneious Prime and KEGG. The strains used were 11R-A, 11R-B1, PTD1, R10, SherDot1, WP5, and WW5.

## Literature Review

Phosphate solubilization by bacteria is mediated by the secretion of gluconate

## Methods

I viewed the annotated strains in Geneious Prime and searched for glucose dehydrogenase and gluconate dehydrogenase coding sequences. I then predicted whether the strains were able to solubilize phosphate or not based on the presence those genes

## Results

1.1.99.3 is the reduces gluconate to 2-keto-D-gluconate while 1.1.99.4 reduces 2-keto-D-gluconate to 2,5 diketogluconate (not relevant?) gcd does glucose --\> glucono-1,5-lactone (\<-\> gluconate), from KEGG

+----------------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Strain         | Genes                                                                                                            | Loci                        | Notes                                                                                                                                                                  |
+================+==================================================================================================================+=============================+========================================================================================================================================================================+
| 11R-A          | gcd (PQQ-dependent glucose dehydrogenase, EC 1.1.5.2), gad (2-gluconate dehydrogenase 1.1.99.3) PhnA, PhnX, PhnP | Contig 24, 21, 10, 38       | Can solubilize phosphate                                                                                                                                               |
|                |                                                                                                                  |                             |                                                                                                                                                                        |
|                |                                                                                                                  |                             | can metabolize phosphonoacetate, phosphonoacetaldehyde                                                                                                                 |
+----------------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 11R-B1         | none                                                                                                             |                             | Unlikely to solubilize phosphate                                                                                                                                       |
+----------------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| PTD1           | gcd, gad, phnX,                                                                                                  | scaffold00016, 00029, 00041 | Likely to solubilize phosphate, metabolize phosphonoacetaldehyde                                                                                                       |
+----------------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| R10            | gcd, gad                                                                                                         | 6, 32                       | Likely to solubilize phosphate                                                                                                                                         |
+----------------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| SherDot1       | gad, gcd (EC 1.1.5.9), 2-ketogluconate kinase (2.7.1.13)                                                         | Contig 42                   | gcd is membrane bound here, still does same reaction. also contains kinase to phosphorylate ketogluconate product, makes phosphate soluble (step may not be necessary) |
|                |                                                                                                                  |                             |                                                                                                                                                                        |
|                |                                                                                                                  |                             | Likely to solubilize phosphate                                                                                                                                         |
+----------------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| WP5            | gcd, gad (both)                                                                                                  | Contig 3, (2), 5            | EC 1.1.99.3 found on same contig as gcd (3), EC 1.1.99.4 isn't                                                                                                         |
|                |                                                                                                                  |                             |                                                                                                                                                                        |
|                |                                                                                                                  |                             | Likely to solubilize phosphate                                                                                                                                         |
+----------------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| WW5            | none                                                                                                             | Contig 6                    | gluconate 2-dehydrogenase subunit 3 family protein CDS                                                                                                                 |
|                |                                                                                                                  |                             |                                                                                                                                                                        |
|                |                                                                                                                  |                             | Unlikely to solubilize phosphate                                                                                                                                       |
+----------------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

## Outcomes

## Notes

Gluconate and 2-ketogluconate can both combine with mineral phosphate to make soluble phosphate. Gluconate dehydrogenase may not be necessary for solubilization.
