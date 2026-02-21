**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate scientific data from approximately 200 zebrafish embryos (100 wild type and 100 phox2bb:mNeonGreen reporter transgenics). The following data types will be collected:
   - High-resolution image files (.png, .jpeg) from whole mount in situ hybridization experiments (estimated 500–1,000 images, totaling ~10–20 GB).
   - Raw bulk RNA-seq and/or single cell RNA-seq (scRNA-seq) fastq files from NeonGreen-labeled cells (estimated 200–500 GB).
   - Raw single cell ATAC-seq fastq files (~200–500 GB).
   - Processed data including gene expression matrices (.csv, .tsv), single cell clustering files, and open chromatin region bed files (~10–50 GB).
   - Associated metadata and analysis scripts.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   The following data will be preserved and shared:
   - All raw sequencing data (bulk RNA-seq, scRNA-seq, ATAC-seq fastq files) to enable reproducibility and facilitate downstream analyses by other researchers.
   - Processed data files (gene expression matrices, clustering assignments, open chromatin region files) to expedite data reuse and integration.
   - In situ hybridization image files, which provide essential spatial and phenotypic context.
   - Metadata and protocols to ensure data interpretability.
   Sharing these data types aligns with NIH policies, supports transparency, and enables secondary analysis within the community.

3. **Metadata, other relevant data, and associated documentation:**   
   The following metadata and documentation will be made accessible:
   - Sample information (genotype, developmental stage, experimental conditions, batch, probe sequences).
   - Detailed protocols for in situ hybridization, cell sorting, RNA-seq, and ATAC-seq library preparation.
   - Data processing and analysis workflows (including software versions and parameters).
   - Data dictionaries describing variables and file formats.
   - README files for datasets.

**Element 2: Related Tools, Software and/or Code:**  
Specialized tools and software are required to access and analyze the data:
   - Image viewers (e.g., Fiji/ImageJ, freely available at https://imagej.net/).
   - Standard bioinformatics tools for RNA-seq and ATAC-seq data (e.g., Cell Ranger, Seurat, Scanpy, Bowtie2, STAR, MACS2).
   - Processed data will be provided in standard formats (.csv, .tsv, .bed) interoperable with R and Python.
   - Custom analysis code and scripts will be shared via GitHub or as supplementary files and will include documentation for reproducibility.

**Element 3: Standards:**  
The following data standards will be applied:
   - Raw sequencing data will comply with the standards of repositories such as NCBI’s Gene Expression Omnibus (GEO) and Sequence Read Archive (SRA), including MIAME (Minimum Information About a Microarray Experiment) and MINSEQE (Minimum Information about a High-Throughput Nucleotide Sequencing Experiment) guidelines.
   - Metadata will adhere to the BioSample and BioProject standards.
   - Processed files will follow standard open file formats: .csv/.tsv for matrices, .bed for genomic coordinates, and .png/.jpeg for images.
   - Data and metadata will be structured to maximize interoperability and reuse.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   - Raw and processed sequencing data, associated metadata: NCBI GEO and SRA (https://www.ncbi.nlm.nih.gov/geo/ and https://www.ncbi.nlm.nih.gov/sra/)
   - In situ hybridization images and additional protocols: figshare (https://figshare.com/) or Zenodo (https://zenodo.org/), with links in GEO records.
   - Analysis scripts and workflows: GitHub (https://github.com/).

2. **How scientific data will be findable and identifiable:**   
   Data will be findable via persistent unique identifiers:
   - Accession numbers assigned by GEO/SRA.
   - Digital Object Identifiers (DOIs) from figshare/Zenodo for images and protocols.
   - Permanent URLs for code repositories (GitHub).
   - Data will be indexed and searchable in public repository databases.

3. **When and how long the scientific data will be made available:**   
   - All data will be made available no later than the time of associated publication or the end of the funding period, whichever comes first.
   - Data will be made publicly available for a minimum of 10 years, consistent with repository retention policies.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   There are no anticipated restrictions on access, distribution, or reuse of the data. All data are derived from zebrafish embryos, not human subjects, and do not involve confidential or proprietary information. Data will be shared under terms permitting broad reuse (e.g., CC-BY 4.0 license).

2. **Whether access to scientific data will be controlled:**  
   Access to all scientific data will be open and unrestricted; no controlled access is required.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   Not applicable. No human data will be generated in this project.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be overseen by the Principal Investigator (PI), with support from the laboratory data manager and the institution’s Office of Research Compliance. The PI will conduct quarterly reviews of data management activities, ensure timely data deposition, and address any data sharing issues. Documentation of compliance will be maintained and made available to NIH upon request.