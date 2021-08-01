# Bioinformatics_course_project

This is the project realized for the Bioinformatics course of Università degli studi di Milano.

The main goal of the project consist in the prediction of active and inactive regions (promoters and enhancers) of the cell line GM12878 of the human genome (hg38).

The bio_data_elaboration_representation file aims is the graphical visualization of different characteristic of both the enhancers and the promoters, and contains the preprocessing steps necessary to obtain the data to visualize.

The other two files, the bio_enhancers and bio_promoters, contain both the preprocessing steps and the actual learning through Random forest classifier and different types of neural networks.
The learning results are also visualized and evaluated through a statistical test (Wilcoxon's test).
Each one of the two files concernes only the learning of one of the type of region considered (the one indicated by the name of the file).
The two files shares most of their characteristic, only the structure of the neural networks varies, in order to use networks tha suits better the data of the two types of regions considered. 
