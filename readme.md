# EADTN: Efficient Deep Model Ensemble Framework for Drug–Target Interaction Prediction

This repository contains the official implementation of the paper:

> **Efficient Deep Model Ensemble Framework for Drug–Target Interaction Prediction**
> **Jinhang Wei**, Yangbin Zhu, Linlin Zhuo, Yang Liu, Xiangzheng Fu, Fushan Li.
> *The Journal of Physical Chemistry Letters*, 2024, 15, 7681–7693.
> DOI: [10.1021/acs.jpclett.4c01509](https://doi.org/10.1021/acs.jpclett.4c01509)

> **Note on authorship:** This code repository was primarily developed by **Jinhang Wei** (first author).

# Requirements

- numpy==1.20.3
- pandas==1.5.3
- scikit_learn==1.0.2
- torch==1.13.1
- tqdm==4.64.1

# Usage

```bash
python main.py --dataset 'BindingDB/Biosnap' \
               --scenario 'Random/Clustering' \
               --Clustering_basis 'drug/target'  # if scenario is Clustering