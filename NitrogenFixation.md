---
bibliography: references.bib
---

# Predicting Nitrogen Fixation in Bacteria

## Summary of Findings

Strains 11R-A, R10, SherDot1, and WP5 were predicted to be nitrogen fixers due to the presence of the NifH, NifDK, NifEN, and NifB genes. 11R-B1, PTD1, and WW5 were predicted to not be nitrogen fixers due to the lack of these genes.

## Introduction

We are using Geneious Prime to predict if certain strains of endophytic bacteria can fix nitrogen. This will be useful as a primer of Geneious Prime and the other bioinformatic tools at my disposal and show me how to analyze the data presented by these tools. The strains used were 11R-A, 11R-B1, PTD1, R10, SherDot1, WP5, and WW5.

## Literature Review

Nitrogen fixation occurs through three known systems in bacteria - a Fe-Mo nitrogenase system, a V-Fe nitrogenase system, and an Fe only nitrogenase system. The main difference between these systems is the metal co-factor used. The minimum dedicated gene set for Fe-Mo nitrogenase is NifH, NifDK, NifB, and NifEN. Genes that code for proteins to assist with electron supply and transfer are also necessary. Fe-V nitrogenases require VnfH, VnfDKG, VnfEN, and NifB. It appears that NifH can also be used instead of VnfH. Fe-only nitrogenases require AnfH, AnfDKG, NifB, NifU, NifV, and NifS. V-Fe and Fe-only nitrogenases require genes used to synthesize Fe-Mo nitrogenases and are only found in bacteria that also use Fe-Mo nitrogenase [@harwood2020]. I'm expecting to find these genes in bacteria that can fix nitrogen.

## Methods

I viewed the annotated strains in Geneious Prime and searched for nitrogenase, nif, vnf, and anf annotated genes. I then predicted whether the strains were n-fixing bacteria or not based on the presence of genes required for nitrogen fixation.

## Results

| Strain   | Genes                                                                                                                                        | Loci                     | Notes                                                                                                                                                                                                                                                                                                     |
|-----------|--------------|-----------|------------------------------------|
| 11R-A    | NifH, NifDK, NifB, NifEN, NifA, NifX, NifQ, NifW, NifO, NifS, NifU, NifT, NifU-like, NifV, NifZ, ferredoxin, fixABCX                         | Contigs 1, 3, 5          | Probably fixes nitrogen, Appears to only use Fe-Mo nitrogenase                                                                                                                                                                                                                                            |
| 11R-B1   | No nitrogenase/nif genes                                                                                                                     |                          | Most likely doesn't fix nitrogen                                                                                                                                                                                                                                                                          |
| PTD1     | NifU like protein CDS                                                                                                                        | scaffold00001            | Doesn't appear to have any other Nif genes, most likely doesn't fix nitrogen, located near Universal stress protein (binds to nucleotide), same with the one on 11R-A                                                                                                                                     |
| R10      | NifHDK, NifEN, NifB, NifX, NifA, NifQ, NifW, nifI, NifT, NifZ, nifM, NifV, NifU flavodoxin, pyruvate-flavodoxin oxidoreductase               | 26                       | Likely fixes nitrogen, no NifO, Fe-Mo nitrogenase only                                                                                                                                                                                                                                                    |
| SherDot1 | NifHDK, NifEN, NifB NifA, ferredoxin, NifXQOW, NifS, NifU, Nif, NifM, NifT, NifY, NifZ, NifV, VnfEN, VnfDKG, VnfX, VnfA, VnfY, NafY, fixABCX | Contigs 1, 38, 66, 80, 9 | Likely fixes nitrogen, Fe-Mo and V-Fe nitrogenases, no VnfH, but there is a NifH located where a VnfH could be located in the vanadium nitrogenase gene cluster (Contig 80), NafY is a stabilizing subunit of the apo-NifDK protein in A. vinelandii, so it may be doing the same thing here [@burén2020] |
| WP5      | NifH, NifDK, NifEN, NifB, NifX, NifQ, NifW, NifS, NifU, NifI, NifM, NifT, NifZ, NifV, flavodoxin, pyruvate-flavodoxin oxidoreductase         | Contig 16                | Likely nitrogen fixer, Fe-Mo nitrogenase only                                                                                                                                                                                                                                                             |
| WW5      | NifU-like domain protein                                                                                                                     | Contig 30                | Unlikely to fix nitrogen                                                                                                                                                                                                                                                                                  |

## Outcomes

Strains 11R-A, R10, SherDot1, and WP5 are predicted to be nitrogen fixers, while 11R-B, PTD1, and WW5 likely do not. I determined this based on the presence of the nitrogenase genes NifH, NifDK, NifB, and NifEN, as well as other genes that code for proteins that participate in redox chemistry. 11R-A, R10, and WP5 only have Fe-Mo nitrogenase genes, while SherDot1 has both the Fe-Mo core genes and V-Fe nitrogenase genes. PTD1 and WW5 have a NifU-like protein CDS, which looks like it may be used to bind to nucleotides due to it being near genes that code for products that bind to nucleotides. It is most likely not used in any nitrogenase activity, due to the coding sequence being located far away from any nitrogenase genes, and because 11R-A has both this sequence and NifU. Not all of the nitrogen fixing bacteria use the same gene set. Some of the bacteria had NifO, which allows for simultaneous activity of nitrogenase and nitrate reductase, allowing nitrogen fixation in the presence of nitrate [@burén2020]. 11R-A and SherDot1 have this gene, while R10 and WP5 don't. This may mean that the bacteria that SherDot1 and 11R-A are associated with live in an environment with lots of nitrate. A potential next step is figuring out what the rest of the genes outside of the minimum set do.
