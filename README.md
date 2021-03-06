# Bioinformatics_course_project

This is the project realized for the Bioinformatics course of Universit√† degli studi di Milano.

The main goal of the project consist in the prediction of active and inactive regions (promoters and enhancers) of the cell line GM12878 of the human genome (hg38).
Two different types of data have been used to try to achive this proposition: the epigenomic data obtained form the [ENCODE](https://www.encodeproject.org/) dataset, and the genomic sequence data obtained the [UCSC genome browser](https://genome.ucsc.edu/). 

The bio_data_elaboration_representation file aims is the graphical visualization of different characteristic of both the enhancers and the promoters, and contains the data elaboration steps necessary to obtain the data to visualize.

In the other two files, the bio_enhancers and bio_promoters, the actual learning is performed, evaluated and presented.
The models used for the learning are a Random forest classifier, a FeedForward Neural Network, a Convolutional Neural Network and a MultiModal Neural Network, of which the first two use the epigenomic data, the third the sequence ones, and the fourth both.
Each one of the two files concernes only the learning of one of the type of region considered (the one indicated by the name of the file).
The two files shares most of their characteristic, only the structure of the neural networks varies, in order to use networks tha suits better the data of the two types of regions considered. 
