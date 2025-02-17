# VISTA_reproduce
The codes used to reproduce the results in paper: VISTA Uncovers Missing Gene Expression and Spatial-induced Information for Spatial Transcriptomic Data Analysis. 

To reproduce the results in the main figure, please refer the codes and results listed in each folder.

To reproduce the results in supplementary files, please refer the folder **supp**.

To reproduce the results of baselines, please refer the folder **baselines**.

The hyper-parameters used in VISTA (model archicature: joint GNN-based VAE and MLP-based VAE) for the four datasets used in the benchmarking analysis is shown below:

| Dataset          | Epochs | n_latent | n_neighbors |
|------------------|--------|----------|-------------|
| osmFISH-brain    | 300    | 32       | 20          |
| Xenium-brain     | 200    | 1024     | 20          |
| Xenium-breast    | 200    | 1024     | 20          |
| seqFISH-embryo   | 300    | 32       | 20          |

Other hyper-parameters follow the default setting in [scvi-tools](https://scvi-tools.org/).