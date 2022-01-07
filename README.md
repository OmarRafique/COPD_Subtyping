# COPD_Subtyping
Using topological data analysis to make useful network graphs of COPD expression data (GSE76705).


The code is in Eclipse.ipynb. Run it line by line to obtain the results shown in .png files. 
The data can be downloaded from https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE76705

The shape of  data point cloud contains useful information which is difficult to leverage because of the hig dimensionality of the gene expression data. Common unsupervised methods suchas dimensionality reduction and clustering are blin to the shape of data. Topological DAta Analysis quantifies the shape of data y providing two main methods 1) Pesistent Homology 2) Mapper. 

In the jupyter notebook we have used the Mapper algorithm to analyse COPD gene expression data The input to the mapper is the patient point cloud of the COPD dataset and the output is a graph which preserves the shape f the dataset. Each node of the output graph contains a group of patients and therefore it makes sense to colour ach node by  the average value of 1) FEV1 2) FEV1/FVC 3) Age 4) Pack-years. All these graphs are uploaded. 
Distinct patterns of COPD patients in the four graphs can be visually  seen. 

This repository is under development and suggestions are welcomed. 
