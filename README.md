# HINGNN-DTI
A drug-target interactions prediction model called HINGNN-DTI based on heterogeneous information network and graph neural network
# Data
In this study, dict information of drugs and target proteins in the dataset was used to obtain the physical and chemical property characteristics of drugs and ESM-1b characteristics of targets, and node characteristic information was aggregated through the graph attention network. At the same time, the drug-target association network, drug-drug association network, drug-disease association network, target-target association network and target-disease association network were constructed into a heterogeneous information network, and the HIN2Vec characteristics of drugs and targets were extracted respectively.
# Requirements
python = 3.7.13   torch = 1.13.1  numpy = 1.17.5
