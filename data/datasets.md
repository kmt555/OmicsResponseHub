
<!--ts-->
* [Collection of bulk RNA data with drugs](#collection-of-bulk-rna-data-with-drugs)
   * [Drug treatment + bulk RNA profiling prior to treatment start](#drug-treatment--bulk-rna-profiling-prior-to-treatment-start)
      * [Example 1.](#example-1)
      * [Example 2.](#example-2)
   * [Drug treatment + bulk RNA profiling prior and after the treatment](#drug-treatment--bulk-rna-profiling-prior-and-after-the-treatment)
      * [Example 1.](#example-1-1)
      * [Example 2.](#example-2-1)

<!-- Created by https://github.com/ekalinin/github-markdown-toc -->
<!-- Added by: tyck, at: Thu Jun  6 13:37:36 EDT 2024 -->

<!--te-->

# Cell perturbations

## Drugs: 131 drugs across 639 human cell lines

  * [Garnett et al Nature 2012 "Systematic identification of genomic markers of drug sensitivity in cancer cells"](https://pubmed.ncbi.nlm.nih.gov/22460902/).

Other studies that re-use these data:

  * [Livnat Jerby-Arnon et al Cell 2018](https://pubmed.ncbi.nlm.nih.gov/30388455/) "A Cancer Cell Program Promotes T Cell Exclusion and Resistance to Checkpoint Blockade."


## (CRISPR)-Cas9: Perturb-CITE-seq 
[Frangieh, Melms, Thakore, Geiger-Schuller et al 2021](https://pubmed.ncbi.nlm.nih.gov/33649592/)

~750 (CRISPR)-Cas9 perturbations + single-cell transcriptome (~218K cells) + 20 proteins.

Genes perturbed are those known/likely to be associated with resistance to immune checkpoint inhibitors.

Experimental set up: samples are collected from melanoma patients and patient-derived melanoma cells are generated. sgRNA library is consturcted to KO select genes of interest. 
In a simple viability screen: the (CRISPR)-Cas9 perturbed patient-derived melanoma cells are then co-cultured with autologous tumor-infiltrating lymphocyte (TIL) and cell viability is measured using as a proxy sgRNA enrichment in surviving cells.

Perturb-CITE-seq on the other hand, matches pooled CRISPR screen with scRNA readout. This gives us impact of genetic perturbation on expression profile and survival of individual cells.


## Drug treatment + bulk RNA profiling prior and after the treatment

### Example 1.

### Example 2.

## scRNAseq data

  * [Sade-Feldman et al Cell 2018 "Defining T Cell States Associated with Response to Checkpoint Immunotherapy in Melanoma"](https://pubmed.ncbi.nlm.nih.gov/30388456/)


# Large consortia with multi-omics data + drug treatments

## NCI-60 database
[Official Publication](https://pubmed.ncbi.nlm.nih.gov/16990858/)

## Genomics of Drug Sensitivity in Cancer (GDSC) project
[Official Publication](https://pubmed.ncbi.nlm.nih.gov/27397505/)

## Cancer Cell Line Encyclopedia (CCLE) project
[CCLE modeling of drug response](https://pubmed.ncbi.nlm.nih.gov/22460905/)
This dataset contains pharmacological profiles for 24 anticancer drugs across 479 of the cell lines.

