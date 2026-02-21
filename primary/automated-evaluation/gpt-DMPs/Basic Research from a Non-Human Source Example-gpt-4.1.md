**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   This project will generate three primary datasets from up to 50 mouse models of nonalcoholic steatohepatitis (NASH)-driven hepatocellular carcinoma (HCC):  
   - Clinical and Phenotypic Data: Tabular data including animal sex, body weight, specific organ weights, age and developmental stage, tissue profiled, and disease outcomes. Estimated size: <1MB (CSV or TSV format).  
   - RNA Sequencing Datasets: Raw and processed RNA-seq data, including normalized transcript and gene-level expression counts, as well as quality control metrics (total reads, clipped reads, sequencing platform, etc.). Estimated size: 50-100GB (FASTQ/BAM for raw, TXT/CSV for processed data).  
   - Microscopy Images: Light and confocal microscopy images of formaldehyde-fixed paraffin-embedded tissue slices. Estimated size: 100-200GB (TIFF or similar format).  
   In total, the anticipated volume of data is approximately 150-300GB.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All three datasets—clinical/phenotypic data, RNA-seq data (raw and processed), and microscopy images—will be preserved and shared. Sharing these datasets will allow for validation and reproducibility of findings, facilitate secondary analyses by other researchers (e.g., meta-analyses, re-analysis, or integration with other NASH/HCC datasets), and accelerate scientific discovery in liver disease and cancer research.

3. **Metadata, other relevant data, and associated documentation:**   
   - Detailed data dictionaries describing each variable and its coding in the clinical/phenotypic dataset  
   - Experimental protocols (animal handling, tissue preparation, sequencing library preparation, imaging protocols)  
   - RNA-seq quality control and processing pipelines (including software versions and parameters)  
   - Microscopy acquisition settings and image annotation guidelines  
   - README files describing file structure and naming conventions  
   - Any relevant Institutional Animal Care and Use Committee (IACUC) approval documentation redacted as appropriate

**Element 2: Related Tools, Software and/or Code:**  
Raw and processed RNA-seq data will require standard bioinformatics tools for access and analysis, such as FastQC (for quality control), STAR or HISAT2 (for alignment), and DESeq2 or EdgeR (for differential expression analysis). These are open-source and widely available. Microscopy images can be viewed using open-source tools such as FIJI/ImageJ or QuPath. All tools will be referenced in the associated documentation. Custom scripts or pipelines developed for data processing will be shared via GitHub or as supplementary files in the data repository.

**Element 3: Standards:**  
- Clinical and Phenotypic Data: Variables will be coded using standard biomedical ontologies where available (e.g., Mouse Phenotype Ontology, NCBI Taxonomy for species, and Disease Ontology terms for outcome).  
- RNA-seq Data: Data and metadata will adhere to the Minimum Information About a Sequencing Experiment (MINSEQE) guidelines and will use standard formats such as FASTQ (raw), BAM/CRAM (aligned), and TSV/CSV (expression counts).  
- Microscopy Images: Image files will be stored in OME-TIFF or standard TIFF format with accompanying OME-XML metadata following the Open Microscopy Environment (OME) standards.  
- Metadata will be structured according to the ISA-Tab format to enable interoperability.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   - RNA-seq data (raw and processed): NCBI Gene Expression Omnibus (GEO) and/or Sequence Read Archive (SRA)  
   - Clinical and phenotypic data: GEO supplementary files or the NIDDK Central Repository  
   - Microscopy images: The Image Data Resource (IDR) or NIDDK Central Repository (as appropriate)  

2. **How scientific data will be findable and identifiable:**   
   Each dataset will be assigned a persistent unique identifier (e.g., GEO accession numbers, SRA study IDs, or DOIs in IDR). Metadata will be indexed and searchable via repository portals and through standard indexing services such as PubMed and BioSamples.

3. **When and how long the scientific data will be made available:**   
   All data will be made publicly available no later than the time of publication of the main findings or at the end of the project performance period, whichever comes first. Data will remain available in the repositories for a minimum of 10 years, consistent with NIH policy and repository retention standards.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All data are derived from non-human animal studies, and thus, there are no privacy or consent limitations. Data will be de-identified as per institutional policy. There are no anticipated restrictions on access, distribution, or reuse beyond appropriate citation and acknowledgment requirements.

2. **Whether access to scientific data will be controlled:**  
   No, data will be made openly available without access controls. Raw and processed datasets will be deposited in public repositories with unrestricted access.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   Not applicable. All data are derived from mouse models; no human data will be generated or shared.

**Element 6: Oversight of Data Management and Sharing:**  
Oversight of data management and sharing will be coordinated by the Principal Investigator (PI) and the designated Data Steward for the project. Compliance with the DMSP will be reviewed quarterly at project team meetings, and an annual compliance report will be submitted to the institutional research office. The Data Steward will ensure timely data deposition, adherence to metadata and documentation standards, and will serve as the primary contact for data sharing inquiries. The PI will have ultimate oversight responsibility.