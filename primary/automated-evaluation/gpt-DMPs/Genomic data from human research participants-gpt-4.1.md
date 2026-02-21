**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate genomic and phenotypic data from approximately 500 human research participants. The primary scientific data types include: (1) raw whole genome sequencing (WGS) data (~100 GB per subject; estimated total ~50 TB), (2) processed genomic data such as variant call files (VCFs), and (3) harmonized phenotypic and clinical assessment data collected using National Institute of Mental Health Data Archive (NDA) data dictionaries. Additional data will include demographic information, behavioral assessments, and medical/psychiatric history as relevant to the study aims.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All raw WGS data, processed genomic data (e.g., VCFs), and corresponding phenotypic and clinical data will be preserved and shared. This includes all data necessary to reproduce primary findings and enable secondary analyses by other investigators. Data sharing is in accordance with NIH and NIMH policies to maximize the utility and impact of collected data, facilitate reproducibility, and support broad scientific discovery.

3. **Metadata, other relevant data, and associated documentation:**   
   Metadata will include subject-level and sample-level information, sequencing platform and protocol details, data processing and quality control logs, and documentation of all phenotypic assessments (including data dictionaries, codebooks, and study protocols). Data will be submitted with all required NDA and dbGaP metadata fields to ensure interpretability and reusability.

**Element 2: Related Tools, Software and/or Code:**  
The scientific data can be accessed and manipulated using standard open-source bioinformatics tools such as SAMtools, GATK, and PLINK for genomic data, and Tabular data analysis software (e.g., R, Python, or Microsoft Excel) for phenotypic/clinical data. No proprietary software is required. Data deposited in dbGaP and NDA will be in standardized file formats (e.g., FASTQ, BAM, VCF, CSV), and documentation will specify recommended tools for use.

**Element 3: Standards:**  
The project will use community-accepted data and metadata standards to ensure interoperability. Genomic data will follow the file format and metadata requirements specified by the NIH Genomic Data Sharing Policy, dbGaP, and the NIMH Data Archive (e.g., FASTQ/BAM for sequence data, VCF for variants). Phenotypic and clinical data will be harmonized and submitted according to the NDA data dictionary and common data elements. All datasets will include required metadata for subject and sample identification, consent codes, and data provenance.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   Raw and processed genomic data will be submitted to dbGaP (the NIH Database of Genotypes and Phenotypes). All data types, including genomic, phenotypic, and clinical data, along with supporting documentation, will be deposited in the NIMH Data Archive (NDA).

2. **How scientific data will be findable and identifiable:**   
   Data submitted to dbGaP and NDA will be indexed and assigned persistent unique identifiers (e.g., accession numbers, DOIs) to ensure long-term discoverability. Metadata records in these repositories will be searchable via repository-specific and general data discovery tools (e.g., NIH RePORTER, DataMed).

3. **When and how long the scientific data will be made available:**   
   Scientific data will be made available to qualified investigators as early as possible, but no later than the time of publication of the main findings or at the end of the NIH funding period, whichever occurs first. Data will remain available through dbGaP and NDA for a minimum of 10 years or as required by repository policies and NIH guidelines.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All research participants will be prospectively consented for broad data sharing in accordance with NIH Genomic Data Sharing Policy. Data will be de-identified prior to sharing. Controlled access procedures will be used to address privacy concerns and ensure data use is consistent with participant consent, IRB requirements, and ethical guidelines.

2. **Whether access to scientific data will be controlled:**  
   Yes, access to all individual-level genomic and phenotypic data will be controlled and made available through dbGaP and NDA only after approval of a Data Use Certification/Application by the appropriate data access committee.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All data will be de-identified prior to submission, following HIPAA and NIH guidelines. Identifiers will be removed, and only coded subject IDs will be used. Data will be stored and shared under controlled access agreements. Certificates of Confidentiality will be obtained as required. Access to sensitive data will require user agreements specifying appropriate data use, storage, and reporting practices to protect participant privacy and confidentiality.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be overseen by the project’s Data Manager in coordination with the Principal Investigator. The Data Manager will ensure timely data submission and adherence to data standards and repository requirements. Oversight will occur at least quarterly and will include regular audits of data storage, documentation, and submission procedures. The Institutional Data Steward and the IRB will provide additional oversight to ensure compliance with all regulatory and ethical requirements. Any non-compliance will be promptly addressed and reported to the funding agency as required.