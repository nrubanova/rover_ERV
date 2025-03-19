Data and Jupyter notebooks supporting the manuscript **_"An endogenous retroviral element co-opts an upstream regulatory sequence to achieve somatic expression and mobility"_**, authored by
Natalia Rubanova, Darshika Singh, Louis Barolle, Fabienne Chalvet, Sophie Netter, Mickaël Poidevin, Nicolas Servant, Allison J. Bardin and Katarzyna Siudeja.



The notebooks `notebooks/rover_TE_genotyping_ONT.ipynb` and `notebooks/rover_TE_aging.ipynb` are Python scripts developed to perform post-processing and genotyping of TE calls detected in ONT samples using `tldr` [Ewing et al. (2020) Molecular Cell](https://www.cell.com/molecular-cell/fulltext/S1097-2765(20)30731-0?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS1097276520307310%3Fshowall%3Dtrue), as well as to normalize raw singleton counts.

`data/PGFP_refTE_dm6.csv` and `data/PGFP_Illumina.csv` are needed to run `rover_TE_genotyping_ONT.ipynb`.

The file `data/PGFP_refTE_dm6.csv` contains the list of full-length refrence TE insertions in the _D. melanogaster_ _ProsGFP_ genetic background.


The file `data/PGFP_Illumina.csv` contains the list of non-reference TE insertions detected in the Illumina DNA-seq samples from [Siudeja et al (2021) EMBO J](https://www.embopress.org/doi/full/10.15252/embj.2020106388), using `readtagger` [Siudeja et al. (2021) EMBO J](https://www.embopress.org/doi/full/10.15252/embj.2020106388) and `ngs_te_mapper2` [Han et al. (2021) Genetics](https://academic.oup.com/genetics/article/219/2/iyab113/6321957).

