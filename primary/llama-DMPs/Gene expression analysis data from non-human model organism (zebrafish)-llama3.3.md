### Element 1: Data Type
1. **Types and amount of scientific data expected to be generated in the project:**   
   The proposed project is expected to generate several types of scientific data from approximately 200 zebrafish embryos (100 wild types and 100 phox2bb:mNeonGreen reporter transgenic fish embryos). The primary data types include:
   - *In situ hybridization images (.png, .jpeg files) for genes of interest using digoxigenin-labeled antisense RNA probes.
   - *Transcriptional profiling data from NeonGreen labeled cells through bulk RNA-seq analysis, single cell clustering and expression analysis, and/or single cell RNA-seq (scRNA-seq).
   - Detailed cis-regulatory and open chromatin analysis data from single cell ATAC-seq.
   - Raw data will be collected as fastq files, which will then be transformed into matrices and bed files using standard workflows for bulk RNA-seq, scRNA-seq, and ATAC-seq analyses.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All raw and processed data from in situ hybridization, bulk RNA-seq, scRNA-seq, and ATAC-seq experiments will be preserved and shared. The rationale is to facilitate transparency, reproducibility, and further research by making these datasets available to the scientific community. Sharing these data aligns with the principles of open science and can accelerate discoveries related to gene expression and regulatory mechanisms in zebrafish models.

3. **Metadata, other relevant data, and associated documentation:**   
   To facilitate interpretation of the scientific data, the following will be made accessible:
   - Metadata: Sample information (e.g., embryo type, experimental conditions), sequencing parameters, and analysis pipeline details.
   - Other relevant data: Gene expression levels, differential gene expression analyses, and chromatin accessibility data.
   - Associated documentation: Study protocols, data collection instruments, and detailed methods for each experiment.

### Element 2: Related Tools, Software and/or Code:
Specialized tools, software, and/or code are needed to access or manipulate shared scientific data. These include:
- Bioinformatics pipelines for RNA-seq and ATAC-seq data analysis (e.g., HISAT2, FeatureCounts, DESeq2).
- Single-cell analysis tools (e.g., Seurat, Scanpy).*
- Genomic browsers (e.g., UCSC Genome Browser, IGV) for visualizing chromatin accessibility and gene expression data.
These tools are widely used in the field and can be accessed through their respective websites or repositories (e.g., GitHub, Bioconductor).

### Element 3: Standards:
Common data standards will be applied to the scientific data and associated metadata to enable interoperability of datasets and resources. Specifically:
- FASTQ files for raw sequencing data, adhering to the FASTQ format standard.
- BED and bigWig files for genome-wide data (e.g., ATAC-seq peaks, gene expression levels), following the ENCODE data standards.
- Metadata will be described using standardized ontologies (e.g., EFO, DOID) where applicable.
These standards are chosen because they are widely adopted in the genomics and transcriptomics communities, facilitating data integration and comparison across studies.

### Element 4: Data Preservation, Access, and Associated Timelines
1. **Repository where scientific data and metadata will be archived:**   
   The scientific data and metadata arising from this project will be archived in the Gene Expression Omnibus (GEO) repository and/or the NCBI Sequence Read Archive (SRA), which are appropriate for genomics and transcriptomics data.

2. **How scientific data will be findable and identifiable:**   
Data will be made findable and identifiable through the assignment of unique identifiers (e.g., GEO accession numbers, SRA run accessions) and standard indexing tools like PubMed and Google Scholar.

3. **When and how long the scientific data will be made available:**   
   The scientific data will be made available to other users no later than the time of publication of the main findings or at the end of the performance period, whichever comes first. The data will remain accessible for a minimum of 10 years after the project's completion, adhering to NIH guidelines and repository policies.

### Element 5: Access, Distribution, or Reuse Considerations
1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   Given that this project involves zebrafish embryos and not human subjects, there are no limitations related to informed consent, privacy, or confidentiality protections. However, any reuse of the data should properly cite the original publication and adhere to the terms of use specified by the repositories where the data are archived.

2. **Whether access to scientific data will be controlled:**  
   Access to the scientific data will not be controlled beyond what is standard for public repositories like GEO or SRA. Data will be available for download without restrictions, other than those imposed by the repository's terms of service.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   This project does not involve human subjects; therefore, protections for human research participant privacy, rights, and confidentiality are not applicable.

### Element 6: Oversight of Data Management and Sharing:
Compliance with this Data Management and Sharing Plan will be monitored and managed by the Principal Investigator (PI) in collaboration with the institution's Research Data Management Office. Oversight activities include regular checks on data deposition into designated repositories, ensuring metadata completeness, and verifying that shared data are properly cited in publications. The PI and the data management team will meet bi-annually to review progress and address any issues related to data sharing and management.