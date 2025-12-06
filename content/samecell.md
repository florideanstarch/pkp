---
title: Single Cell!
authors: Deepak, Satya
---

Walking back from office and rushing for our mandatory evening tea, we entered a huge street in an upscale Hyderabad neighbourhood. This time the topic was that why has no one ever attempted to sequence the transcriptome and perform proteomics on the same cell. [CITE-seq](https://en.wikipedia.org/wiki/CITE-Seq) came up as a method but as we recalled, it targets only a few surface protein molecules and not the entire proteome.

The real answer, or what we thought was the real answer, was that it is simply not possible!? The chemistry of RNA extraction is not conducive to the extraction of proteins and vice-versa. But given that this problem is so fundamental, we suspected that someone would have attempted to solve this problem.

Lo and behold, someone took a shot at this! Even though the method is not super popular, a group of Chinese researchers had published a protocol in 2023 named [scSTAP](https://pubmed.ncbi.nlm.nih.gov/37976159/) (single-cell simultaneous transcriptome and proteome).

This is the authors' introduction to the method:

> The commonly used cell lysis reagent was 0.1% RapiGest in single-cell proteome analysis and 0.2% Triton X-100 in single-cell transcriptome analysis. It is well known that most of the surfactants including Triton X-100 are MS incompatible due to their interference with MS detection.

They appear to have engineered a work around for RNA lysis buffers that interfere with MS (mass spectrometry), a major hinderance to developing proteomics and transcriptomics on the same single cell. This involved the development of an "enzyme-assisted cell lysis" method. They tried it in oocytes. 

Because their method relies on extremely small lysate volumes, they have had to engineer a workaround for this as well:

> At present, the single-cell proteome analysis technique plays a speed-determining role in the development of single-cell multi-omics analysis because the amount of proteins contained in a single cell is extremely small and proteins cannot be amplified, leading to greater challenges than single-cell transcriptome analysis. For the analysis of transcriptome and proteome in a single-cell individual, the primary problem to be solved is how to separate and transfer the very small amount of RNAs and proteins existing in the single cell for respective transcriptome sequencing and proteome analysis.

Broadly, the authors discuss the following prerequisites for fully solving single-cell multi-omics, which they appear to have fulfilled: 

-  The system must be able to split single-cell lysates in the nanoliter range (single-cell proteomics studies typically use nL volumes to avoid adsorption loss of ultra-trace proteins). The paper calls this PSS or precise sample splitting
-  When the cell is lysed, cellular components should be uniformly distributed in the lysate. Uneven splitting of the components will cause inconsistency in the component content between the transcriptome and proteome samples.
-  Even after solving the challenges above, the "performance of the simultaneous two-omics analysis should not have a remarkable decrease in the identification depth compared with the single-omics analysis". The simultaneous omics analysis should not suffer a marked decrease in identification depth compared with single‑omics analyses. Proteomics and transcriptomics should detect comparable numbers of distinct molecules.

The PSS is achieved through a techique they have previously developed, called [SODA](https://pubs.acs.org/doi/10.1021/ac4006414) (sequential operation droplet array).

We will read and analyse this paper further to identify where the method still falls short and why it has not become popular.

Note: The paper was recently corrected because the authors failed to provide their code; the authors apologized nearly two years after publication.

An interesting tangent worth mentioning is from the modeling world. [This](http://nature.com/articles/s41540-024-00484-9) method had claimed to reproduce CITE-seq level of surface proteome using transcriptomics and some transformer magic. More on this later.