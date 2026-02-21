```markdown
**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate demographic and clinical data from 200 amyloid-positive, cognitively normal older adults with symptomatic insomnia. Scientific data types include:
   - Demographic variables (e.g., age, sex, education, race/ethnicity)
   - Clinical assessments (cognitive status assessments using standardized instruments)
   - Biomarker data:
     - Cerebrospinal fluid (CSF): amyloid-beta (Aβ), tau, phosphorylated tau, NPTX2, sTREM2, and neurofilament light (NfL)
     - Plasma: Aβ, tau, phosphorylated tau
   The estimated data volume is approximately 2-5 MB per participant, resulting in a total dataset size of approximately 1-2 GB (including raw data, cleaned datasets, and associated documentation).

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All de-identified individual-level demographic, clinical, and biomarker data described above will be preserved and shared. The rationale is to maximize scientific utility and reproducibility, to support secondary analyses, facilitate meta-analyses, and enable cross-cohort comparisons in aging and Alzheimer’s disease research. Data sharing is consistent with NIH and NIA policies and the broad data sharing consent obtained from participants.

3. **Metadata, other relevant data, and associated documentation:**   
   The following will be made accessible:
   - Data dictionaries (variable names, definitions, allowable values)
   - Study protocols (enrollment, sample collection, assay methods)
   - Data collection forms and instruments (e.g., cognitive assessment scales)
   - Codebooks and data processing pipelines
   - Documentation of data cleaning and quality control procedures

**Element 2: Related Tools, Software and/or Code:**  
No specialized tools or proprietary software are required to access or analyze the shared datasets. All data will be provided in standard, non-proprietary formats (e.g., CSV, XLSX). Any code used for data processing or analysis (e.g., R scripts, Python code) will be shared via a public code repository (e.g., GitHub) and referenced in the data documentation.

**Element 3: Standards:**  
The project will employ established community data standards to maximize interoperability:
- Common Data Elements (CDEs) from the NIH/NIA Alzheimer’s Disease and Related Dementias (ADRD) CDEs will be used for demographic, clinical, and biomarker variables.
- Clinical and assay data will conform to standards such as LOINC codes for laboratory tests and Neuroimaging Data Model (NIDM) standards when applicable.
- Metadata will follow the Data Documentation Initiative (DDI) standard and will be mapped to the FAIR principles.
- If consensus standards are unavailable for specific biomarker assays (e.g., NPTX2), detailed assay protocols and measurement units will be provided to ensure reproducibility.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   Data and metadata will be archived in the National Institute on Aging Genetics of Alzheimer’s Disease Data Storage Site (NIAGADS; https://www.niagads.org/), a NIH-designated repository for aging and Alzheimer’s disease research data.

2. **How scientific data will be findable and identifiable:**   
   Each dataset deposited in NIAGADS will be assigned a persistent unique identifier (e.g., DOI or accession number) and indexed in the repository’s catalog. Metadata will be registered to ensure discoverability through NIAGADS and associated NIH data discovery platforms.

3. **When and how long the scientific data will be made available:**   
   Data will be made available no later than the time of first publication of primary results or at the end of the funding period, whichever comes first. Data will remain available in the repository for a minimum of 10 years, per NIH and NIA guidelines, or as long as the repository remains active.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All participants will provide informed consent for broad data sharing. Data will be de-identified to minimize risk to participant privacy. Reuse will be permitted for research purposes consistent with the original consent, with no known additional restrictions. Data use limitations and any additional requirements will be disclosed in the data use agreement per NIAGADS policy.

2. **Whether access to scientific data will be controlled:**  
   Yes, access to individual-level data will be controlled. Researchers will be required to submit a data access request and agree to NIAGADS data use terms, which include requirements for IRB approval or exemption and adherence to privacy/confidentiality protections.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   Data will be de-identified in accordance with the HIPAA Privacy Rule Safe Harbor method prior to sharing. Direct identifiers will be removed. The study will obtain a Certificate of Confidentiality from NIH to further protect participant information. Data sharing agreements will require recipients to uphold participant confidentiality and prohibit re-identification attempts.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be overseen by the project’s Data Steward (Principal Investigator) and the institutional Data Management Officer. The Data Steward will ensure data de-identification, documentation, and timely deposition in the repository. Oversight will occur quarterly via internal audits and annual reporting to the NIH Program Officer. Any deviations from the Plan will be addressed promptly and documented in progress reports.
