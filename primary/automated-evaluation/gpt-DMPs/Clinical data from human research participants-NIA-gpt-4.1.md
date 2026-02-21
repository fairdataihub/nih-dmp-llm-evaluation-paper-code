```markdown
**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   Clinical data will be obtained from electronic health records (EHR) for approximately 15,000 patients in a primary care clinic. The data types include demographic information, medical history, laboratory results, medication records, physical exam findings, and cognitive exam results. Additionally, cognitive assessment data will be collected for a subset of approximately 40 individuals using validated assessment instruments. The total estimated dataset size is expected to be 2-3 GB of structured, tabular data. The project will also generate derived cognitive risk scores for each patient.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   De-identified clinical data (demographics, medical history, laboratory data, medications, physical and cognitive exam results) and the derived cognitive risk scores will be preserved and shared. Data will be shared to promote reproducibility, enable secondary analyses, and support further research in aging and cognitive health. Direct identifiers and protected health information (PHI) will not be preserved or shared.

3. **Metadata, other relevant data, and associated documentation:**   
   Metadata to be provided will include data dictionaries, variable definitions, coding information, and descriptions of the data structure. Associated documentation such as study protocols, data collection instruments (including cognitive assessment tools), and data processing scripts will also be made accessible to facilitate interpretation and reuse of the scientific data.

**Element 2: Related Tools, Software and/or Code:**  
Standard statistical software such as R and Python (with commonly used data analysis packages) will be sufficient to access and manipulate the shared scientific data. Any custom code used for generating cognitive risk scores or preprocessing data will be provided as open-source scripts in a public code repository (e.g., GitHub). No specialized or proprietary software is required.

**Element 3: Standards:**  
The project will use standard health data terminologies, including LOINC for laboratory results, RxNorm for medications, and SNOMED CT or ICD-10 for diagnoses and medical history. Demographic and clinical variables will be mapped to the Observational Medical Outcomes Partnership (OMOP) Common Data Model where possible to facilitate interoperability. Metadata will adhere to the Data Documentation Initiative (DDI) standard. In cases where no consensus standards exist for a variable, detailed descriptions will be provided in the data dictionary.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   Scientific data and metadata will be archived in the National Institute on Aging (NIA) approved data repository, such as the National Institute on Aging Genetics of Alzheimer's Disease Data Storage Site (NIAGADS) or the NIH-supported generalist repository, Figshare.

2. **How scientific data will be findable and identifiable:**   
   All datasets will be assigned a persistent unique identifier (DOI) and will be indexed in the chosen repository’s public catalog to ensure findability. Data will be accompanied by comprehensive metadata to support discoverability.

3. **When and how long the scientific data will be made available:**   
   Scientific data will be made available no later than the time of publication of major findings or at the end of the performance period, whichever occurs first. Data will remain available for a minimum of 10 years following initial deposit, or as required by the repository’s policies.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   As the data are derived from human participants, all research participants will be consented for broad data sharing. However, data will be de-identified to protect participant privacy and comply with HIPAA regulations. Data use will be subject to a Data Use Agreement (DUA) to ensure ethical use and compliance with participant consent.

2. **Whether access to scientific data will be controlled:**  
   Yes, access to the scientific data will be controlled. Users must submit a data access request and agree to the DUA prior to gaining access through the data repository.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All data will be de-identified prior to sharing, with direct identifiers and PHI removed in accordance with HIPAA Safe Harbor standards. A Certificate of Confidentiality will be obtained from NIH to further protect participant information. Access will be limited to qualified investigators who agree to comply with all privacy and data use requirements.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Plan will be monitored and managed by the project’s Data Steward in collaboration with the Institutional Data Governance Committee. Oversight will occur quarterly, with compliance checks at each major project milestone and prior to data release. The Principal Investigator will have ultimate responsibility for DMSP adherence, supported by the Institutional Review Board (IRB) and the Office of Research Compliance.
