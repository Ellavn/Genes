Introduction
============
The projecct is in order to specify the project OMG requirement.
OMG is a web application to analyze difference in genes
expression.


Purpose
-------
To analyze the difference genes expression through a genes expression
file and a scatter diagram.The purpose of this application is for
biologists to better analyze exprimental data.


Overview
--------
The web application has a simple interface with only one button.scientist
could upload a text file with two sample.after we receive the text file
and scientist press the button you can get a scatter plots of genes.if you insert a vaild text file,the application will return to the start interface and prompt you insert another file.


users
-----
*  The scientist who study genes expression
*  Program maintainer


Terminologies
-------------
*  **Control Sample:** A cell sample prepared in its normal condition
*  **Treatment Sample:** A cell sample treated by special chemicals,or in which some genes are altered.
*  **Differentially expressed genes** The genes which have significantly different expression levels between two samples.
*  **Up-regulation** A gene is said to be up-regulated if it has higher expression in treatment than in control.
*  **Down-regulation** A gene is said be down-regulated if it has lower expression in treatment than in control.


Abbreviations
-------------
**logFC** - log fold change of gene expression. log_2 [T/C], where T is the gene expression level from a treatment sample, while C is the gene expression level from a control sample
