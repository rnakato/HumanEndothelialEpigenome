
## About this project

As a part of the International Human Epigenome Consortium (IHEC) project, 
we collected ChIP-seq data of histone modifications as well as RNA-seq and DNA methylation data from various vascular cell types from multiple donors. To catalogue and characterize the transcriptomic and epigenomic landscape in the vascular system, we implemented comprehensive analysis for genome-wide data of active histone modifications and gene expression for nine types of human endothelial cells show below.

- Human aortic endothelial cells (HAoECs)
- Human coronary artery endothelial cells (HCoAECs)
- Human endocardial cells (HENDCs)
- Human pulmonary artery endothelial cells (HPAECs)
- Human umbilical vein endothelial cells (HUVECs)
- Human umbilical artery endothelial cells (HUAECs)
- Human common carotid artery endothelial cells (HCCaECs)
- Human renal artery endothelial cells (HRAECs)
- Human great saphenous vein endothelial cells (HGSVECs)

## Data
- Raw read file (Fastq)
   - ChIP-seq: [GEO GSE131953](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131953)
   - RNA-seq: [GEO GSE131681](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131681)

- Mapped read file (BAM)
   - [ChIP-seq](https://drive.google.com/open?id=1uz_tX9eue_PLR5AjElYwf46Zv9xxxpsB&authuser=u-rnakato%40g.ecc.u-tokyo.ac.jp&usp=drive_fs)
       - build hg19 and hg38, mapped by [BWA](http://bio-bwa.sourceforge.net/)
   - [RNA-seq](https://drive.google.com/open?id=1XmdM3HQS0-Bto6a-tEdnueoTVXPOeayd&authuser=u-rnakato%40g.ecc.u-tokyo.ac.jp&usp=drive_fs)
       - uild hg19 and hg38, mapped by [STAR](https://github.com/alexdobin/STAR)

- Quality check (QC) results
   - [ChIP-seq](https://drive.google.com/open?id=16ialQRmdq-gN6z0_0uyLHNIusK4q0zD-&authuser=u-rnakato%40g.ecc.u-tokyo.ac.jp&usp=drive_fs)
   - [RNA-seq](https://drive.google.com/open?id=19ILbnLD1g-GAvXlZBdXGlxyWTe1pNbF4&authuser=u-rnakato%40g.ecc.u-tokyo.ac.jp&usp=drive_fs)

- Peak files
   - [The reference promoter sites](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE131953&format=file&file=GSE131953%5FEC%5Fref%5Fpromoter%2Ebed%2Egz)
   - [The reference enhancer sites](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE131953&format=file&file=GSE131953%5FEC%5Fref%5Fenhancer%2Ebed%2Egz)
   - The peak list of each sample is also available at [GEO GSE131953](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131953)

- Gene expression data
      - IMR90 cells from the [Sequence Read Archive (SRA)](www.ncbi.nlm.nih.gov/sra) under accession number SRR2952390.

- ChIA-PET file
    - We acquired fastq files from the GEO under accession number GSE41553, applied Mango [65] with default parameter settings

## Program

## Contact

