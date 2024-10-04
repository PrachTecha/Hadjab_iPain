# Hadjab iPain paper code
This repository holds the core code for the main analysis and plotting for "[The single-cell transcriptomic atlas iPain identifies senescence of nociceptors as a therapeutical target for chronic pain treatment](https://doi.org/10.1038/s41467-024-52052-8)" paper.

## Citation
```
Techameena, P., Feng, X., Zhang, K., Hadjab, S. (2024).
The single-cell transcriptomic atlas iPain identifies senescence of nociceptors as a therapeutical target for chronic pain treatment.
Nature Communications, 15(8585). https://doi.org/10.1038/s41467-024-52052-8 
```

## Contents
- [DRG](DRG) - Containing Jupyter Notebooks for creating the [iPainDRG](https://cellxgene.cziscience.com/e/b6f472f1-a58d-43a7-a898-2d6822a0b2b2.cxg/) atlas in mice and its analysis.
- [TG](TG) - Containing Jupyter Notebooks for creating the [iPainTG](https://cellxgene.cziscience.com/e/5d6d404a-86f9-419e-9928-56276904819c.cxg/) atlas in mice, and the analysis for the bulk RNA-seq from rat TG ([Tao et al., 2021](https://pubmed.ncbi.nlm.nih.gov/34323444/)).
- [h_DRG](h_DRG) - Containing Jupyter Notebooks for the analysis and deconvolution of Human DRG bulk RNA-seq data from [Ray et al., 2023](https://academic.oup.com/brain/article/146/2/749/6648727). Additionally, bulk RNA-seq analysis of diabetic neuropathy data in human from [Hall et al., 2022](https://www.nature.com/articles/s41598-022-08100-8) could be found in this directory.
- [IMG_BH_Blood](IMG_BH_Blood) - Containing Jupyter Notebooks for plotting and statistical analysis of data related to image quantifications, behavior tests, and blood counts.

## Dependencies
To reproduce the results, please use `conda` or `mamba` to install all the dependencies from [environment.yml](environment.yml) file using:

```sh
mamba env create -f environment.yml
mamba activate injury_atlas
```