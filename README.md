## A novel AI algorithm of GRU model integrated with transfer learning, is proposed to perform de novo natural products design that employed as novel NLRP3 inhibitors. 
### 1.perform pre-training process
`python train.py`
### 2.perform transfer learning process
`python transfer_learning.py`
### 3.generate molecules with the transfer learning model
`python sample.py data/200_epochs_transfer_augument3_one.ckpt`
### 4.calculate the properties of the pre-training dataset, transfer learning dataset, and generated molecules
`python calculate_property.py`
### 5.compare the properties between the transfer learning dataset and generated molecules
`python pca_plot.py`
`python KDE.py`


