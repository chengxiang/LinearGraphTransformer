# (Linear) Graph Transformer 
Pytorch code for reproducing experiments for the following paper:

[Graph Transformers Dream of Electric Flow](https://arxiv.org/abs/2410.16699).  *Xiang Cheng, Lawrence Carin, Suvrit Sra, ICLR 2025*  



<h2>ZINC Experiments</h2>
The files for the the ZINC regression experiments are found under the ZINC folder. To reproduce the experiments, run (in order):

- zinc_exp_init.ipynb
- zinc_exp_LT.ipynb

For comparison, the baseline Laplacian Eigenvector implementation is found in 
- zinc_exp_baseline_LapPE.ipynb

The train/val/test data can be downloaded here: 

[ZINC_dgl_clean_20k](https://duke.box.com/s/cbbszr4e0rd2tbc5cbdd49vre0uuulig) <br />
[ZINC_pytorch_clean_20k](https://duke.box.com/s/v6vql8a4cyahr4knscx4mes4e5ecs9nf)

Alternatively, you can also generate the data yourself using the [code found here](https://github.com/xbresson/CS6208_2023/blob/main/codes/labs_lecture09/01_generate_molecular_datasets.ipynb).

Code for base Graph Transformer implementation is taken from https://github.com/xbresson/CS6208_2023
