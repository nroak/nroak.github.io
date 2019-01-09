---
layout: single
classes: wide
permalink: /admire/
author_profile: true

title: "ADmiRE"
excerpt: "Annotative Database of miRNA Elements"
layouts_gallery:
  - url: /assets/images/admire_annotations.png
    image_path: /assets/images/admire_annotations.png
    alt: "admire_annotations"

toc: false
---

## Annotative Database of miRNA Elements
### ADmiRE Highlights

- Annotation wrapper for adding comprehensive miRNA annotations to a user supplied list of variants (tab-separated format)
- Adds information for miRNA domains, gnomAD mean allele frequency percentiles, evolutionary conservation, etc.

### GitHub

- [Download from GitHub](https://github.com/nroak/ADmiRE)

### Published in Human Mutation

- *Framework for microRNA variant annotation and prioritization using human population and disease datasets* [Human Mutation](https://onlinelibrary.wiley.com/doi/full/10.1002/humu.23668)


{% include gallery id="layouts_gallery" caption="Description of miRNA variant annotations included in ADmiRE" %}

### Description of annotations added to each base within miRNA region

| Index | ADmiRE Annotations         | Description                                 |
| ----- | -------------------------- | ------------------------------------------- |
| 1 | MIRNA | Precursor Name (miRBase) |
| 2 | PRE_ID | Precursor ID (miRBase) |
| 3 | Family_Name | miRNA Family Name (miRBase) |
| 4 | Family_ID | miRNA Family ID (miRBase) |
| 5 | Mature_Name | Mature Name (miRBase) (if applicable) |
| 6 | Mature_ID | Mature ID (miRBase) (if applicable) |
| 7 | High_Confidence | High Confidence (miRBase) |
| 8 | Conserved_ADmiRE | Conserved ADmiRE (This study) |
| 9 | Robust_FANTOM5 | Robust miRNA (FANTOM5 project) |
| 10 | HMDD_Targets.PMID | Curated experiementally validated targets (PubMed ID) (HMDD) |
| 11 | HMDD_Disease.PMID | Known associated disease (HMDD)  |
| 12 | miRTarBase_Validated.Targets | Curated experimentally validated targets (miRTarBase) |
| 13 | miRTarBase_TargetGene.Validation.type | Method of target validation (miRTarBase) |
| 14 | miRTarBase_Reference.PMID | Publication of target validation (miRTarBase) |
| 15 | gnomad_af_precursor_quantile | AF percentile from this study with mean AF across precursor miRNAs |
| 16 | gnomad_af_mature_quantile | AF percentile from this study with mean AF across mature miRNAs |
| 17 | gnomad_af_family_quantile | AF percentile from this study with mean AF across all mature miRNAs in a family |
| 18 | MIRNA_Feature | miRNA Domain (miRBase- Figure 1)  |
| 19 | Precursor_Pos | Base position in precursor domain |
| 20 | Pred_Motif | Predicted Motif in Precursor (CNNC, basalUG, UGU, UGUG, loop) |
| 21 | Mature_Pos | Base position in mature domain |
| 22 | PhyloP_100way | PhyloP 100way- Vertebrate scores |
| 23 | PhastCons_100way | Phastcons 100way- Vertebrate scores |
| 24 | gnomAD_Count | gnomAD AC for all alleles at the position |
| 25 | gnomAD_MAF | gnomAD AF for all alleles at the position |
