# seqCD

## Capstone Project 2 for Springboard DataScience Bootcamp

Aim of the project is to develop a model that will predict the shape of a CD spectrum based on the primary amino acid sequence. See final report for details and background.   

Data are coming from PCDBB (https://pcddb.cryst.bbk.ac.uk/).    
Citation: The PCDDB (protein circular dichroism data bank): A bioinformatics resource for protein characterisations and methods development.
Ramalli SG, Miles AJ, Janes RW, Wallace BA., J Mol Biol (2022) 

DataCleaning notebook details connecting to the database and importing the data into a more easy-to-manipulate format.<br>
EDA can be ignored by most unless you'd like to go on a stream-of-conscious journey through this dataset with me.<br>
Feature Engineering uses AAIndex and some other criteria to convert amino acid sequences and spectra into something more algorithmically tractable.<br>
Modeling optimizes hyperparameters for the three best classifiers identified in EDA (I say what they are here, seriously, you don't want to go through the EDA), then compares them and tries to make some conclusions.<br>
Final Report is where I would recommend starting.
