```markdown
**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**  
   The project will generate multiple types of scientific data from approximately 1,000 human participants (500 cases and 500 controls), including:
   - Array-derived genotype data (Illumina platform), estimated output ~1-2 GB per sample, totaling ~1-2 TB.
   - 30x whole-genome sequencing (WGS) data (Illumina), estimated at ~100 GB per sample, totaling ~100 TB.
   - RNA sequencing (RNA-seq) data (~10-20 GB per sample; total ~10-20 TB).
   - Hi-C WGS data (~100 GB per sample; total ~100 TB).
   - Phenotypic and clinical data extracted from electronic health records (EHRs), including structured and unstructured data, estimated at ~2-5 GB.
   - Demographic data, including age, sex, ethnicity, and other relevant variables, extracted from EHRs, estimated at <1 GB.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All primary genomic, transcriptomic, and clinical datasets listed above will be preserved and shared, including: raw and processed genotype data, WGS data (raw FASTQ, aligned BAM/CRAM files, and variant calls), RNA-seq data (raw and processed count files), Hi-C data (raw and processed contact maps), and associated phenotypic/clinical/demographic data. The rationale is to maximize the utility and reproducibility of the research, facilitate secondary analyses, and comply with NIH and NHGRI data sharing policies. Data will be shared broadly, consistent with participants’ consent for broad data sharing.

3. **Metadata, other relevant data, and associated documentation:**  
   The following metadata and documentation will be made available:
   - Data dictionaries and codebooks for all clinical and demographic variables
   - Data processing pipelines and workflow descriptions
   - Sample and participant metadata (including technical and biological covariates)
   - Study protocols, consent forms (redacted as necessary), and IRB approval documents
   - Data collection instruments and QC metrics for each data type
   - README files and standardized metadata files following repository requirements (e.g., BioSample/BioProject metadata for NCBI)

**Element 2: Related Tools, Software and/or Code:**  
Standard, widely used bioinformatics tools will be required to access and analyze the data:
- Genotype data: PLINK, GenomeStudio (Illumina), bcftools
- WGS data: samtools, GATK, IGV
- RNA-seq data: STAR, kallisto, R/Bioconductor packages
- Hi-C data: Juicer, HiC-Pro, HiGlass
- Data available in standard formats (VCF, BAM/CRAM, FASTQ, HDF5, TXT/CSV)
All tools listed are open-source or freely available for academic use. Documentation and, where applicable, custom analysis scripts will be provided via GitHub or a similar public code repository.

**Element 3: Standards:**  
The following data standards will be applied:
- Genotype and sequence data: VCF (Variant Call Format), FASTQ, BAM/CRAM (aligned sequence), following GA4GH and Global Alliance for Genomics and Health recommendations.
- RNA-seq data: FASTQ, BAM, count matrices in tab-delimited or HDF5 formats
- Hi-C data: .hic or .cool formats, following community standards
- Clinical and demographic data: OMOP or CDISC standards where applicable; ICD-10 for diagnoses; LOINC for lab tests; HL7 FHIR for EHR data extraction
- Metadata: BioSample/BioProject (NCBI) and MIAME/MINSEQE guidelines for sequencing experiments
All data will be curated and formatted according to the requirements of the chosen repositories to ensure interoperability and reusability.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**  
   - Genotype, WGS, RNA-seq, and Hi-C data: dbGaP (Database of Genotypes and Phenotypes), and where appropriate, the NCBI Sequence Read Archive (SRA) and Gene Expression Omnibus (GEO).
   - Phenotypic, clinical, and demographic data: dbGaP, linked to corresponding genomic datasets.
   - Metadata and protocols: Associated with primary data in dbGaP, SRA, and/or GEO.

2. **How scientific data will be findable and identifiable:**  
   All datasets will be assigned unique, persistent accession numbers (e.g., dbGaP Study Accession, SRA/GEO accession numbers). Metadata will be indexed and searchable via NIH repository portals and standard search engines. DOIs will be minted where appropriate.

3. **When and how long the scientific data will be made available:**  
   Data will be submitted to repositories and made available no later than the time of first publication of results or at the end of the funding period, whichever comes first. Data will remain available in these repositories indefinitely, in accordance with NIH and repository policies.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   Data sharing will comply with participants’ consent for broad data sharing. Because datasets include potentially identifiable human genetic information and clinical data, data use will be governed by NIH Genomic Data Sharing Policy and any specific limitations stipulated in participant consent or IRB protocol. There are no anticipated restrictions beyond those required by privacy protection and ethical guidelines.

2. **Whether access to scientific data will be controlled:**  
   Yes, access to individual-level genomic and clinical data will be controlled via dbGaP’s Data Access Committee (DAC) process. Summary-level data and aggregate results may be openly available, as permitted by consent.

3. **Protections for privacy, rights, and confidentiality of human research participants:**  
   All data will be de-identified in accordance with HIPAA and NIH guidelines prior to sharing. A Certificate of Confidentiality will be obtained. Data will be stored and shared via NIH repositories with established security and access controls. All institutional and federal requirements for human subjects data protection will be followed, including IRB oversight and Data Use Agreements (DUAs) for secondary users.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Plan will be overseen by the Project Principal Investigator (PI) and a designated Data Manager/Data Steward within the research team. Regular reviews (at least quarterly) will ensure adherence to data sharing timelines, standards, and repository submission requirements. The Institutional Office of Research Compliance and the IRB will provide additional oversight to ensure all data management and sharing activities meet institutional, NIH, and regulatory guidelines.
