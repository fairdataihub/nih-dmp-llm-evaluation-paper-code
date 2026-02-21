**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The proposed research will generate multi-modal scientific data from approximately 500 human participants across multiple testing sessions. Primary data types include:  
   - Raw video files (estimated 1–2 GB per subject per session; total ~3–5 TB) capturing behavioral sessions.  
   - Activity data (e.g., accelerometry, actigraphy) from wearable sensors (estimated 10–50 MB per subject per session).  
   - Cardiac physiological files (e.g., ECG, heart rate variability; estimated 100–200 MB per subject per session).  
   - Processed behavioral data (e.g., coded behavioral metrics, event timings), and autonomic nervous system (ANS) reactivity metrics derived from physiological recordings.  
   In total, the project will generate approximately 4–6 TB of raw and processed data.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   The following data will be preserved and shared:  
   - De-identified processed behavioral and ANS reactivity data tables for all subjects and time points, as these represent the primary scientific outcomes.  
   - Summary activity data and cardiac physiological metrics (e.g., heart rate, variability indices) at all test points.  
   - Associated metadata, including timing, test conditions, and demographic variables (de-identified).  
   - Raw data (video, physiological signals) will be archived for reproducibility but shared only upon qualified request due to privacy, data size, and re-identification risk.  
   Rationale: Sharing processed data and metadata maximizes scientific value and reproducibility, while managing participant confidentiality and logistical constraints.

3. **Metadata, other relevant data, and associated documentation:**   
   - Data dictionaries for all shared variables  
   - Study protocols and experimental procedures  
   - Data collection instruments and sensor/device specifications  
   - Variable codebooks and behavioral coding schemes  
   - Data processing pipelines/workflows  
   - Consent forms (template versions, excluding PHI)  
   - README files describing dataset structure and access instructions  

**Element 2: Related Tools, Software and/or Code:**  
  - Processed data (tables, CSV, or similar) can be accessed using standard statistical and spreadsheet software (e.g., R, Python, Excel).  
  - Raw physiological data may require open-source tools such as Kubios HRV or Biorec, and video data can be read with standard video players (e.g., VLC).  
  - Custom data processing scripts (e.g., Python, R, MATLAB) developed for this project will be made available in a public GitHub repository, with documentation and open-source licensing.  
  - Links and instructions for all required software/tools will be provided in the documentation.

**Element 3: Standards:**  
  - Behavioral and physiological data will adhere to the Brain Imaging Data Structure (BIDS) standard where applicable (e.g., BIDS-EEG and BIDS-behavior for event-locked data).  
  - Metadata will follow the NIH Common Data Elements (CDE) and NIA-recommended data elements for aging studies, including standardized demographic variables.  
  - Variable names, units, and value coding will be documented in data dictionaries using recognized ontologies (e.g., SNOMED CT for medical terms).  
  - Data and documentation will be provided in non-proprietary formats (e.g., CSV, JSON, MP4, EDF).  
  - No universal consensus standards exist for some behavioral video data; for these, internal documentation and codebooks will be used to maximize interpretability and interoperability.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   - Processed and de-identified data, metadata, and documentation will be deposited in the [NIH-supported National Institute on Aging (NIA) Aging Research Biobank](https://agingresearchbiobank.nia.nih.gov/) and/or [NIH Figshare instance](https://nih.figshare.com/).  
   - Raw video and physiological files will be archived in the institutional secure data repository with controlled access and registered in the NIA Biobank or dbGaP as appropriate.

2. **How scientific data will be findable and identifiable:**   
   - Each dataset will be assigned a persistent digital object identifier (DOI) through the repository.  
   - Metadata records will be indexed in the NIA Aging Research Biobank catalog and linked to publications via DOI and standard citation formats.  
   - Data will be discoverable through repository search tools and referenced in data availability statements in publications.

3. **When and how long the scientific data will be made available:**   
   - Data will be made available no later than the time of publication of the main study results or at the end of the funding period, whichever comes first.  
   - Data will remain available for a minimum of 10 years from the date of deposit, in line with NIH and NIA data sharing policies.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   - Data access and use will be governed by participant consent, which allows for broad sharing of de-identified data for research purposes.  
   - Access to raw video and physiological data is restricted due to the potential risk of re-identification and large data size; these files will be shared under data use agreements upon qualified request and IRB approval.  
   - All shared data will be de-identified and stripped of direct personal identifiers in accordance with HIPAA and institutional policies.

2. **Whether access to scientific data will be controlled:**  
   - Processed and de-identified data will be shared openly.  
   - Access to raw video and physiological files will be controlled and subject to data access requests and approval processes managed by the repository and the institutional data access committee.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   - All data will be de-identified prior to sharing, following HIPAA Safe Harbor and expert determination procedures as appropriate.  
   - A Certificate of Confidentiality will be obtained to protect participant data from compelled disclosure.  
   - Access to potentially re-identifiable data (e.g., video files) will be restricted and governed by data use agreements specifying privacy and security requirements.  
   - All data management will comply with institutional IRB and NIH data sharing and privacy policies.

**Element 6: Oversight of Data Management and Sharing:**  
   - Oversight of data management and sharing will be provided by the project’s Data Steward (PI-appointed), in coordination with the institutional Data Management and Sharing Committee and the IRB.  
   - Compliance with this plan will be reviewed quarterly during project meetings and annually in progress reports to NIH.  
   - The Data Steward, with support from the project manager and institutional compliance office, will monitor data preservation, documentation, timely sharing, and adherence to privacy requirements.  
   - Any breaches or deviations will be reported promptly to the IRB and NIH Program Officer.