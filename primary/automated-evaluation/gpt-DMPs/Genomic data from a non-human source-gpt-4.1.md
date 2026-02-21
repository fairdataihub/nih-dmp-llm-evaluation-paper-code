**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate a spatially mapped single-cell atlas of the developing mouse brain, with the potential to include data from human cells in later project years. For each modality (single-cell ATAC-seq, single-cell RNA-seq, and single-cell DNA methylation), the primary data will be cell-by-feature matrices:  
   - ATAC-seq: Matrix of cells × peaks (counts in peaks)  
   - RNA-seq: Matrix of cells × genes (UMI counts)  
   -DNA methylation: Matrix of cells × methylation status at specific sites  
   Each matrix will be accompanied by dense metadata tables annotating each cell. The anticipated volume of data is estimated at 1-2 TB of processed data and up to 10-20 TB of raw sequencing data over the course of the project.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   The following data will be preserved and shared:  
   - Processed cell-by-feature matrices for each modality (ATAC-seq, RNA-seq, DNA methylation)  
   - Associated cell-level metadata tables  
   - Raw sequencing data (FASTQ files)  
   - Data processing scripts and pipelines  
   Sharing these datasets will facilitate reproducibility, enable secondary analyses by the research community, and support collaborative efforts in mapping brain development. Raw data will be preserved to enable reprocessing with future methods.

3. **Metadata, other relevant data, and associated documentation:**   
   The following metadata and documentation will be made accessible:  
   - Cell-level metadata: animal sex, developmental time point, punch of origin (x, y, z coordinates), assigned cluster/subcluster and inferred cell types, QC metrics (total reads, passing reads, reads in peaks, TSS enrichment, cell barcode, preparation/sequencing dates, sequencing platform, doublet likelihood, and other relevant metrics)  
   - Sample-level metadata: animal identifiers, batch information, experimental protocols  
   - Data processing documentation: detailed protocols for tissue processing, library preparation, and sequencing; descriptions of quality control procedures and analysis pipelines  
   - Data dictionaries and README files to facilitate interpretation and reuse

**Element 2: Related Tools, Software and/or Code:**  
Specialized tools and software will be needed to access and analyze the scientific data:  
- Seurat (R package) and Scanpy (Python) for single-cell data analysis  
- ArchR for single-cell ATAC-seq analysis  
- Cell Ranger (10x Genomics) for initial processing  
- Standard bioinformatics tools for handling FASTQ, BAM, and matrix files  
All software is open-source or freely available for academic use. Custom code and processing pipelines developed during the project will be shared via GitHub and documented for reproducibility.

**Element 3: Standards:**  
The project will follow established community standards for single-cell genomics data:  
- Data formats: FASTQ for raw reads; BAM for aligned data; HDF5, AnnData (.h5ad), or Matrix Market (.mtx) formats for matrices  
- Metadata standards: Minimum Information About a Single Cell Experiment (MINISE) and requirements by the Brain Research through Advancing Innovative Neurotechnologies® (BRAIN) Initiative  
- Controlled vocabularies for cell types (e.g., Cell Ontology), anatomical terms, and experimental variables  
- All metadata will be structured to comply with repository requirements (e.g., GEO/SRA/NeMO Archive) to maximize interoperability  
If additional standards emerge during the project, they will be adopted as appropriate.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   Processed data and metadata will be deposited in the NeMO Archive (https://nemoarchive.org/), which specializes in single-cell neurogenomics data. Raw sequencing data will be deposited in the NCBI Gene Expression Omnibus (GEO) and Sequence Read Archive (SRA). If human data is generated, it will be deposited in dbGaP or an equivalent NIH-approved controlled-access repository.

2. **How scientific data will be findable and identifiable:**   
   All datasets will be assigned persistent unique identifiers (DOIs or accession numbers from NeMO, GEO, SRA, or dbGaP). Metadata will follow repository-specific indexing and will be discoverable via standard repository search tools and NIH Data Discovery Indexes.

3. **When and how long the scientific data will be made available:**   
   Data will be made available no later than the time of first publication of results or at the end of the performance period, whichever comes first. Data will remain accessible in the selected repositories for a minimum of 10 years, in accordance with NIH policy and repository guidelines.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   Data from mouse studies will be shared without restrictions, except for general terms of use set by the repositories. If human-derived data are included, sharing will be subject to informed consent agreements, privacy, and confidentiality requirements. Data use limitations will be clearly documented in the metadata.

2. **Whether access to scientific data will be controlled:**  
   Mouse data will be available via open access repositories (NeMO, GEO, SRA). Human data, if generated, will be available through controlled access (e.g., dbGaP) to ensure compliance with consent and confidentiality protections.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   If human data are generated, all data will be de-identified before sharing. Data will be deposited in controlled-access repositories (e.g., dbGaP), with access granted only to approved investigators under data use agreements. Certificates of Confidentiality and IRB-approved protocols will govern data handling and sharing, in full compliance with NIH and institutional requirements.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be overseen by the project’s Data Steward, supervised by the Principal Investigator (PI). Quarterly reviews will be conducted to ensure data is being properly documented, archived, and shared according to the timelines and standards outlined above. The institutional Office of Research Compliance will perform annual audits and provide guidance as needed. Any updates or amendments to the DMSP will be reviewed and approved by institutional officials and communicated to NIH program staff.