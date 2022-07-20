# Phosphate Solubilization

## Summary of Findings

Due to the presence of gcd (glucose dehydrogenase) and gad (gluconate dehydrogenase) coding sequences, 11R-A, PTD1, R10, SherDot1, and WP5 were predicted to solubilize mineral phosphates like tricalcium phosphate (TCP). During the phosphate solubilization assay, only R10 and WP5 were seen to solubilize phosphate (TCP).

## Introduction

We are using Geneious Prime to predict if certain strains of endophytic bacteria can solubilize phosphate. This will give me further experience with Geneious Prime and KEGG. The strains used were 11R-A, 11R-B1, PTD1, R10, SherDot1, WP5, and WW5.

## Literature Review

Phosphate solubilization by bacteria is mediated by the secretion of gluconate

## Methods

I viewed the annotated strains in Geneious Prime and searched for glucose dehydrogenase and gluconate dehydrogenase coding sequences. I then predicted whether the strains were able to solubilize phosphate or not based on the presence those genes

## Results

1.1.99.3 is the reduces gluconate to 2-keto-D-gluconate while 1.1.99.4 reduces 2-keto-D-gluconate to 2,5 diketogluconate (not relevant?) gcd does glucose --\> glucono-1,5-lactone (\<-\> gluconate), from KEGG

+----------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Strain   | Genes                                                                                                            | Loci                        | Notes                                                                                                                                                                  |
+==========+==================================================================================================================+=============================+========================================================================================================================================================================+
| 11R-A    | gcd (PQQ-dependent glucose dehydrogenase, EC 1.1.5.2), gad (2-gluconate dehydrogenase 1.1.99.3) PhnA, PhnX, PhnP | Contig 24, 21, 10, 38       | Can solubilize phosphate                                                                                                                                               |
|          |                                                                                                                  |                             |                                                                                                                                                                        |
|          |                                                                                                                  |                             | can metabolize phosphonoacetate, phosphonoacetaldehyde                                                                                                                 |
+----------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 11R-B1   | none                                                                                                             |                             | Unlikely to solubilize phosphate                                                                                                                                       |
+----------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| PTD1     | gcd, gad, phnX,                                                                                                  | scaffold00016, 00029, 00041 | Likely to solubilize phosphate, metabolize phosphonoacetaldehyde                                                                                                       |
+----------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| R10      | gcd, gad                                                                                                         | 6, 32                       | Likely to solubilize phosphate                                                                                                                                         |
+----------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| SherDot1 | gad, gcd (EC 1.1.5.9), 2-ketogluconate kinase (2.7.1.13)                                                         | Contig 42                   | gcd is membrane bound here, still does same reaction. also contains kinase to phosphorylate ketogluconate product, makes phosphate soluble (step may not be necessary) |
|          |                                                                                                                  |                             |                                                                                                                                                                        |
|          |                                                                                                                  |                             | Likely to solubilize phosphate                                                                                                                                         |
+----------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| WP5      | gcd, gad (both)                                                                                                  | Contig 3, (2), 5            | EC 1.1.99.3 found on same contig as gcd (3), EC 1.1.99.4 isn't                                                                                                         |
|          |                                                                                                                  |                             |                                                                                                                                                                        |
|          |                                                                                                                  |                             | Likely to solubilize phosphate                                                                                                                                         |
+----------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| WW5      | none                                                                                                             | Contig 6                    | gluconate 2-dehydrogenase subunit 3 family protein CDS                                                                                                                 |
|          |                                                                                                                  |                             |                                                                                                                                                                        |
|          |                                                                                                                  |                             | Unlikely to solubilize phosphate                                                                                                                                       |
+----------+------------------------------------------------------------------------------------------------------------------+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

## Outcomes

11R-A, PTD1, R10, SherDot1, and WP5 were predicted to be able to solubilize phosphate because gcd and gad coding sequences were present in their genomes. 11RB and WW5 do not have these coding sequences, so they were predicted to be unable to solubilize phosphate. After this prediction, I tested it by placing each strain in an agar plate with insoluble TCP (tricalcium phosphate) mixed in. In this assay, only R10 and WP5 were able to solubilize the phosphate, which was demonstrated by a clear ring forming around the bacteria. 11R-A, PTD1, and SherDot1 were unable to solubilize the phosphate in these conditions despite having the gcd and gad genes. This may be because the genes weren't being expressed in those conditions.

## Notes

Gluconate and 2-ketogluconate can both combine with mineral phosphate to make soluble phosphate. Gluconate dehydrogenase may not be necessary for solubilization.
