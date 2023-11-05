# ParasitesDatasetIndexes

This repository stores the metadata information about the data sets (ProtozoanCysts and MNIST) used for the experiments for the Master Thesis project `Decision Boundary Maps for Supporting User-Driven Pseudo-labeling`.

## The structure of the repository

This repository contains 2 folders (ProtozoanCysts and MNIST). The ProtozoanCysts folder contains 2 sub-folders (train and test), in each of this folder there are 2 files `indexes.txt` (that contains the indexes of the data samples) and `deepFA_labels.npy` (that contains the labels obtained using the DeepFA pseudo-labeling algorithm on 1% of the data from the train sub-set, in case of the test folder in this file we store the ground truth labels).

The MNIST folder has 6 sub-folders (train_0.2, train_0.4, train_0.6, train_0.8, train_1.0, test). Each of these folders contains the same files `indexes.txt` and `deepFA_labels.npy` (that contains the same information as described previously).

## Datasets accessibility

The MNIST dataset is a public dataset and it can be accessed through keras or any other open sources.
The ProtozoanCysts dataset is a private data set it can be accessed on demand in consultation with Barbara Benato ( b.c.benato@uu.nl , barbarabenato@gmail.com)

## Questions

If you have any questions about this repository, please contact Cristian Grosu: (cristi2019255@gmail.com)
