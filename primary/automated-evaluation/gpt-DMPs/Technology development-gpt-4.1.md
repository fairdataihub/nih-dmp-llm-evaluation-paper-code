**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate high-throughput sequencing data from 20 human cell lines, including:
   - Nanopore sequence data: Long-read sequencing data (~100 GB per cell line; total ~2 TB), enabling structural variant detection and genome assembly.
   - 30x Whole-Genome Sequencing (WGS) data: High-coverage short-read data (~120 GB per cell line; total ~2.4 TB), for comprehensive variant detection.
   - RNA sequencing (RNA-seq) data: Transcriptomic profiling (~10 GB per cell line; total ~200 GB) to capture gene expression dynamics.
   The total expected data output is approximately 4.6 TB.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All generated raw and processed sequencing data—including FASTQ (raw reads), BAM/CRAM (aligned reads), VCF (variant calls), and gene expression matrices—will be preserved and shared. Sharing these data supports reproducibility, enables secondary analyses by the scientific community, and aligns with NHGRI and NIH policies promoting broad data sharing for human genomic data.

3. **Metadata, other relevant data, and associated documentation:**   
   The following will be shared:
   - Sample and experiment metadata (e.g., cell line identifiers, sequencing platform, library preparation protocols, batch information)
   - Data processing and quality control protocols
   - File manifest and data dictionaries
   - Informed consent language and data use limitations
   - Bioinformatics pipeline descriptions and software versions
   - Study design and protocol documentation

**Element 2: Related Tools, Software and/or Code:**  
Most data formats (FASTQ, BAM/CRAM, VCF, count matrices) are standard and can be accessed using widely available, open-source tools (e.g., samtools, bcftools, IGV, R, Python packages). For Oxford Nanopore data, Guppy basecaller and MinKNOW are recommended for raw read processing; both are freely available for academic research from Oxford Nanopore Technologies. Custom scripts and pipelines used for analysis will be deposited in a public code repository (e.g., GitHub), and links to these resources will be provided alongside the data.

**Element 3: Standards:**  
Standard genomic data formats and metadata standards will be used:
- Data formats: FASTQ for raw reads, BAM/CRAM for aligned reads, VCF for variants, and tab-delimited or HDF5 files for RNA-seq gene expression matrices.
- Metadata standards: The project will follow the Minimum Information About a Sequencing Experiment (MINSEQE) standard and the BioSample/BioProject metadata schema.
- Controlled vocabularies: Cell line and experimental metadata will use standard ontologies (e.g., Cell Line Ontology, NCBI Taxonomy).
These standards ensure interoperability and facilitate data reuse.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   Sequence and associated metadata will be deposited in NIH-approved repositories:
   - dbGaP (Database of Genotypes and Phenotypes): For controlled-access sharing of human genomic data.
   - Gene Expression Omnibus (GEO) or Sequence Read Archive (SRA): For RNA-seq and raw sequencing data, referencing dbGaP accession for controlled access.
   - BioSample/BioProject: For sample and project metadata.

2. **How scientific data will be findable and identifiable:**   
   All datasets will be assigned persistent unique identifiers (accession numbers from dbGaP, SRA, GEO, BioProject). Metadata and data will be indexed and searchable via NCBI’s standard search tools and cross-referenced in publications and project communications.

3. **When and how long the scientific data will be made available:**   
   Data will be made available as soon as possible, but no later than the time of publication of the first main findings or the end of the funding period, whichever comes first. Data will remain available through the designated repositories for a minimum of 10 years, or as specified by repository and NIH policy.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All participants have provided consent for broad data sharing, but as the data are derived from human subjects, sharing will comply with NIH Genomic Data Sharing Policy and applicable law. Potential limitations include requirements to protect participant privacy and honor data use limitations specified in consent documents.

2. **Whether access to scientific data will be controlled:**  
   Yes, access to the genomic data will be controlled. Data will be made available through dbGaP under controlled-access protocols, requiring prospective users to submit Data Access Requests and agree to Data Use Certifications. Processed, aggregate, and non-identifiable metadata may be shared openly as appropriate.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All data will be de-identified prior to sharing, following HIPAA Safe Harbor guidelines and NIH best practices. Data use will be governed by dbGaP’s Data Access Committees. Informed consent documents will clearly describe data sharing and use. Additional protections include certificate of confidentiality and compliance with institutional IRB requirements.

**Element 6: Oversight of Data Management and Sharing:**  
Oversight of data management and sharing will be conducted by the Project Data Manager, in coordination with the Principal Investigator and the institution’s Data Stewardship Committee. Compliance will be reviewed quarterly, with documentation maintained for all data submissions and sharing activities. The Institutional Review Board (IRB) and Office of Research Compliance will perform annual audits to ensure adherence to the DMSP and applicable policies.