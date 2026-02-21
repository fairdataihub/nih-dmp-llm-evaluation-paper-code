**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   This study will generate clinical and laboratory data from 500 participants (250 renal dialysis patients and 250 matched healthy controls) collected from multiple clinics. Data types will include:  
   - Demographics (e.g., age, sex, race/ethnicity, medical history)
   - Laboratory results (e.g., serum creatinine, urea, electrolytes, hemoglobin)
   - Clinical observations (e.g., blood pressure, weight, dialysis modality, session duration)
   - Clinical disposition (e.g., hospitalization, survival status, adverse events)
   The estimated amount of data is approximately 1-2 MB per participant, resulting in a total of ~1 GB of tabular data, plus associated documentation and metadata.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All de-identified, individual-level data for demographics, laboratory results, clinical observations, and clinical disposition will be preserved and shared. The rationale is to maximize scientific value and reproducibility, in accordance with NIH and NIDDK data sharing expectations, and because all participants will provide informed consent for broad data sharing.

3. **Metadata, other relevant data, and associated documentation:**   
   The following will be made accessible:  
   - Data dictionary/codebook
   - Study protocol
   - Case report forms (CRFs)
   - Data collection instruments and standard operating procedures (SOPs)
   - Metadata describing data structure, variable definitions, and coding conventions

**Element 2: Related Tools, Software and/or Code:**  
No specialized or proprietary software is required to access or manipulate the shared data. All data will be provided in non-proprietary, widely used formats (e.g., CSV, TXT, PDF for documentation). Any analysis code or scripts developed during the project (e.g., in R or Python) will be shared as supplementary files with appropriate documentation.

**Element 3: Standards:**  
The following data standards will be applied:  
- Clinical data will be structured according to the Clinical Data Interchange Standards Consortium (CDISC) Study Data Tabulation Model (SDTM) where feasible.
- Laboratory results will use Logical Observation Identifiers Names and Codes (LOINC) for test identification.
- Demographic and clinical variables will conform to NIDDK data element standards and National Library of Medicine (NLM) controlled vocabularies (e.g., SNOMED CT for clinical terms).
- Metadata will follow the Data Documentation Initiative (DDI) standard.
These standards will be applied at the time of data curation and prior to data archiving to ensure interoperability and reusability.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   De-identified data and supporting documentation will be archived in the NIDDK Central Repository (https://repository.niddk.nih.gov/), which supports controlled access for human subjects data.

2. **How scientific data will be findable and identifiable:**   
   Data will be assigned a persistent unique identifier (e.g., DOI or accession number) by the NIDDK Central Repository. Metadata will be indexed in the repository’s catalog and registered with relevant data discovery platforms to enhance findability.

3. **When and how long the scientific data will be made available:**   
   Data will be made available upon publication of the primary results or at the end of the NIH-funded performance period, whichever comes first. Data will remain available through the NIDDK Central Repository for at least 10 years, or as long as the repository remains active and the data are deemed valuable for research.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All research participants will provide informed consent for broad data sharing. Data will be de-identified in accordance with HIPAA standards. However, because the data derive from human subjects and include potentially sensitive clinical information, some use limitations may be imposed to prevent re-identification or misuse, as outlined in the data use agreement.

2. **Whether access to scientific data will be controlled:**  
   Yes, access to the scientific data will be controlled through the NIDDK Central Repository. Investigators seeking access must submit a data request and agree to repository data use conditions.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All data will be de-identified prior to sharing, with direct identifiers removed and indirect identifiers minimized as per NIH and HIPAA guidance. A Certificate of Confidentiality will be obtained. Access will be managed via controlled access procedures, and all users must agree to data use agreements prohibiting attempts to re-identify participants or unauthorized data redistribution.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be monitored by the Principal Investigator (PI) in coordination with the project’s Data Manager and the Institutional Data Steward. Oversight will occur quarterly, with review of data collection, de-identification, documentation, and sharing activities. Annual progress reports will include updates on data management. The Institutional Review Board (IRB) will oversee human subjects protections and approve all data sharing procedures.