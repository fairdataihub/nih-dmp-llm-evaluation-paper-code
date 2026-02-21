```markdown
**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate both clinical and research laboratory data from approximately 1,000 enrolled human participants. Clinical data will be extracted from site electronic health records (EHRs) and include demographic information, insurance status, medical history, medication lists, laboratory test results (from both site and central laboratory), physical examination findings, and other study-specific clinical variables. Data will be collected longitudinally, with high frequency (daily) for the first 2 weeks and then monthly for up to 12 months post-consent. Research laboratory data will include cytokine analyses and other immunoassay results obtained from biospecimens. In addition, genomic data will be generated from whole exome sequencing (WES), shallow whole genome sequencing (WGS), and DNA methylation (EPIC arrays) on blood samples collected at the initial study visit, with an estimated total data volume of approximately 10 TB.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All individual-level, de-identified clinical data (including data from case report forms), research laboratory data, and genomic data will be preserved and shared. This includes longitudinal clinical data, immunoassay results, and genomic data (WES, WGS, and methylation arrays). The rationale is to maximize the utility and reproducibility of the data, facilitate secondary research, and comply with NIH and NICHD data sharing policies. All participants will provide informed consent for broad data sharing.

3. **Metadata, other relevant data, and associated documentation:**   
   The following documentation will be made accessible to facilitate interpretation:  
   - Data dictionaries and codebooks for all clinical, laboratory, and genomic datasets  
   - Study protocols and standard operating procedures (SOPs)  
   - Data collection instruments (e.g., case report forms)  
   - REDCap data dictionary/export files  
   - Laboratory assay protocols  
   - Genomic data processing and quality control documentation  
   - Consent forms and data sharing agreements (templates)  

**Element 2: Related Tools, Software and/or Code:**  
Most clinical and laboratory data will be provided in standard, non-proprietary formats (e.g., CSV, TSV). Genomic data will be shared in standard formats such as FASTQ, BAM/CRAM, and VCF. Tools for accessing these data are freely available and include REDCap (for data management), as well as standard bioinformatics software (e.g., samtools, bcftools, IGV). Detailed documentation and references to appropriate open-source tools will be provided in the data release documentation. No proprietary software is required for access.

**Element 3: Standards:**  
Clinical data will be mapped to standardized terminologies and coding systems, including LOINC (Logical Observation Identifiers Names and Codes) for laboratory data, SNOMED CT/ICD-10 for diagnoses, and RxNorm for medications. Genomic data will adhere to formats and standards established by the Global Alliance for Genomics and Health (GA4GH) and the NIH Genomic Data Sharing Policy, including use of standardized file formats (e.g., FASTQ, BAM/CRAM, VCF). Metadata will conform to the Data Tag Suite (DATS) standard as used by NICHD DASH. Associated documentation will follow FAIR data principles to enhance findability, accessibility, interoperability, and reusability.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   All clinical, laboratory, and associated documentation will be deposited in the NICHD Data and Specimen Hub (DASH) repository. Genomic data will also be deposited in appropriate NIH repositories, such as dbGaP (Database of Genotypes and Phenotypes), as required.

2. **How scientific data will be findable and identifiable:**   
   Data will be assigned persistent unique identifiers (e.g., DOIs, accession numbers) by the NICHD DASH and dbGaP repositories. Descriptive metadata and study-level information will be indexed and searchable through repository portals and relevant data catalogs.

3. **When and how long the scientific data will be made available:**   
   Data will be made available as soon as possible, but no later than the time of publication of the main study findings or at the end of the funding period, whichever comes first. Data will remain available through NICHD DASH and NIH repositories for a minimum of 10 years, in accordance with NIH policy and repository guidelines.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   Data sharing will be conducted in accordance with participant informed consent, which includes permission for broad data sharing. Data will be de-identified prior to sharing to protect participant privacy. Access to individual-level genomic and some clinical data will be subject to data use agreements to ensure compliance with privacy regulations and ethical standards. No additional restrictions are anticipated beyond those required for human subjects data.

2. **Whether access to scientific data will be controlled:**  
   Yes. Access to individual-level data, particularly genomic data and sensitive clinical data, will be controlled and subject to approval by the data repository’s Data Access Committee (DAC). Users must submit data use requests and agree to repository data use terms.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All data will be de-identified in accordance with HIPAA Safe Harbor or expert determination standards prior to sharing. Access to controlled data will require approval and compliance with repository and institutional policies. Additional protections include the use of secure data transfer and storage, Certificates of Confidentiality, and adherence to all applicable federal, state, and institutional human subject protections.

**Element 6: Oversight of Data Management and Sharing:**  
Oversight of data management and sharing will be the responsibility of the study’s Data Manager in collaboration with the Principal Investigator (PI) and institutional Data Steward. Compliance will be monitored throughout the project lifecycle, including annual internal audits, regular data quality checks, and review of data sharing and access activities. The PI will ensure compliance with this plan, and the Institutional Review Board (IRB) will provide oversight of human subject protections and data sharing practices. All data management activities will be documented and reviewed at least quarterly.
