**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate longitudinal data from a cohort of approximately 13,000 participants via web-based surveys and in-person interviews, as well as biological data from approximately 200 home health exams. The data will include:  
   - Social data (e.g., demographics, social networks, psychosocial measures)  
   - Behavioral data (e.g., health behaviors, lifestyle, cognitive assessments)  
   - Biological data (e.g., blood pressure, anthropometrics, biospecimen-derived measures)  
   The estimated data volume is approximately 13,000 records for survey/interview data and 200 records for biological data, with each record containing multiple variables. The total data size is expected to be around 10-20 GB.  

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All individual-level, de-identified data collected via web-surveys, in-person interviews, and home health exams will be preserved and shared. This includes core survey responses, cognitive assessments, and measured biological variables. Data will be shared to facilitate reproducibility, enable secondary analyses, and maximize the scientific value of the cohort, in accordance with NIH and NIA data sharing policies and participant consent for broad data sharing.  

3. **Metadata, other relevant data, and associated documentation:**   
   The following metadata and documentation will be made accessible to facilitate interpretation:  
   - Data dictionaries describing variables, coding, and derived measures  
   - Survey and exam instruments (questionnaires, protocols)  
   - Codebooks and data user guides  
   - Study protocol and design documentation  
   - Data collection and processing SOPs  
   - Documentation of data cleaning and quality assurance procedures  

**Element 2: Related Tools, Software and/or Code:**  
No specialized or proprietary software is required to access or manipulate the shared scientific data. Data files will be shared in standard, non-proprietary formats (e.g., CSV, TXT, or Stata and SAS formats with accompanying documentation). Open-source statistical software (e.g., R) and widely available commercial packages (e.g., SPSS, Stata, SAS) can be used to analyze the data. All code used for data cleaning and derivation of variables will be made available as annotated scripts (e.g., R or Stata .do files).

**Element 3: Standards:**  
The project will use widely recognized data and metadata standards to facilitate interoperability and reuse:  
- Variables will be coded following NIH Common Data Elements (CDEs) where applicable (e.g., demographic, cognitive, and health variables).  
- Metadata will be structured using the Data Documentation Initiative (DDI) standard for social science datasets.  
- Biological data will use LOINC and SNOMED CT codes where relevant.  
- File formats will adhere to non-proprietary standards (e.g., CSV, PDF for documentation).  
These standards will be applied during data processing and documentation to ensure consistency and facilitate integration with other datasets.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   Scientific data and metadata will be archived in the National Archive of Computerized Data on Aging (NACDA), a domain-specific NIH-supported repository. Additional deposition may occur in the NIA-supported AgingResearchBiobank for biological data, as appropriate.

2. **How scientific data will be findable and identifiable:**   
   Data will be assigned persistent Digital Object Identifiers (DOIs) by the repository, and indexed in repository catalogs. Metadata will be findable through NACDA’s searchable database and cross-referenced in relevant NIH and NIA data resource registries.

3. **When and how long the scientific data will be made available:**   
   Scientific data will be made available no later than the time of publication of primary results or the end of the project funding period, whichever occurs first. Data will remain available for a minimum of 10 years after release, or as long as the repository remains operational.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All participants will be consented for broad data sharing. However, access to individual-level data will be subject to data use agreements to ensure appropriate use. Data will be de-identified prior to sharing to protect privacy. Sensitive variables (e.g., geocodes, rare conditions) may be further restricted or masked. Any additional limitations will follow NIH guidance and participants’ informed consent.

2. **Whether access to scientific data will be controlled:**  
   Yes, access to the scientific data will be controlled. Researchers will be required to submit a data use application and agree to terms of use, including not attempting to re-identify participants and using data only for approved research purposes.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All shared data will be de-identified in accordance with HIPAA and NIH guidelines. Direct and indirect identifiers will be removed or masked. The project has obtained a Certificate of Confidentiality from NIH. Data access will be governed by repository data use agreements, and all users will be required to complete human subjects protection training. Additional steps, such as data aggregation or suppression of small cells, will be taken as needed to protect participant confidentiality.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Plan will be monitored by the project’s Data Steward, in coordination with the Principal Investigator (PI) and the Institutional Research Compliance Office. The Data Steward will conduct quarterly reviews of data management activities, including documentation, de-identification, and repository submission status. The PI will provide oversight and annual reporting to the institution and funding agency. Any deviations from the Plan will be documented and addressed promptly, with corrective actions as needed to maintain compliance with NIH and institutional policies.