# Cell-Type-Specific-Immune-Dysregulation-in-Severely-Ill-COVID-19-Patients
Here we provided Rmarkdown files related to the Star Protocol manuscript: Sample processing and single cell RNA-sequencing of peripheral blood immune cells from COVID-19 patients 

1.	Sample code for removing Ambient RNA for individual sample before qc using SoupX: “SoupX.Rmd” and “SoupX.pdf”. Please not the input file for SoupX is the “outs” folder from Cellranger alignment, it will scan and read files needed from this folder.
2.	Sample code for qc of individual sample to remove potential low quality cells, dead cells and potential mulitplets:” QC CM1_2.pdf” and “qc_CM1_2.Rmd”.
3.	Sample code for batch correction using Harmony package: “Harmony batch correction.Rmd” and : “Harmony batch correction.pdf”.
4.	Rds files used in the batch correction are deposited in GEO with accession number GSE154567, and also available upon request. These rds files are under the same process steps indicated above 1&2. 
