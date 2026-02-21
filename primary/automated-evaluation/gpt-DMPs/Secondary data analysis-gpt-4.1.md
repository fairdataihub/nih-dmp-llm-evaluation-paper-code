**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will utilize and generate multimodal data derived from human participants with major depressive disorder. The scientific data will include:  
   - Structural MRI images (T1-weighted and T2-weighted) from approximately 350 subjects (195 from NDA collections 2134 and 2433, and 155 from a previous study not yet shared). Each subject has up to two time points (pre- and post-treatment), resulting in an estimated 700 MRI image files in standard formats (NIfTI or DICOM).  
   - Associated clinical assessment data (e.g., depression severity scores, demographic variables, medication history, and treatment outcomes) for each participant and time point.  
   - Ancillary data such as quality assurance metrics for imaging and records of imaging parameters.  

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All structural MRI images and corresponding clinical assessment data generated or used in the project will be preserved and shared. This includes the previously unshared dataset from 155 participants, which will be deposited to the NIMH Data Archive (NDA). The rationale is to maximize scientific transparency, reproducibility, and reuse by the research community, in accordance with NIH and NIMH policies and in recognition of the value of sharing both neuroimaging and clinical data to advance mental health research.

3. **Metadata, other relevant data, and associated documentation:**   
   The following metadata and documentation will be made accessible:  
   - Study protocols, including MRI acquisition parameters and clinical assessment procedures  
   - Data dictionaries describing variables within the clinical assessments  
   - Participant eligibility criteria  
   - Data processing and de-identification procedures  
   - Documentation outlining time points, treatment regimens, and assessment schedules  
   - Quality control protocols and logs  

**Element 2: Related Tools, Software and/or Code:**  
MRI data will be shared in standard formats (NIfTI, DICOM) compatible with widely available neuroimaging software, including FSL, SPM, and AFNI, all of which are open-source and freely available. Clinical data will be shared in CSV or tab-delimited text formats compatible with standard data analysis tools (R, Python, SPSS, SAS). No proprietary software is required to access the data. Any custom code used for data preprocessing or analysis will be documented and shared via a public repository (e.g., GitHub) with instructions for use.

**Element 3: Standards:**  
The project will adhere to the Brain Imaging Data Structure (BIDS) standard for organizing and describing MRI data and associated metadata, facilitating interoperability and reuse. Clinical data will be mapped to the NDA Common Data Elements (CDEs) where possible, and metadata will be described using NDA-recommended data dictionaries and templates. Data will conform to de-identification and harmonization standards required by the NDA.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   All data and metadata will be deposited in the National Institute of Mental Health Data Archive (NDA; https://nda.nih.gov), the designated NIH repository for neuroimaging and mental health research data.

2. **How scientific data will be findable and identifiable:**   
   Data will be indexed and made findable via the NDA, with each dataset assigned a unique, persistent NDA Collection ID and Digital Object Identifier (DOI) where applicable. Metadata and documentation will be linked to the relevant NDA collection, ensuring discoverability through standard indexing and search tools.

3. **When and how long the scientific data will be made available:**   
   Previously unshared data from 155 participants will be uploaded to the NDA by the end of Quarter 2 of Year 1 of funding. All data will be made available to qualified researchers no later than the time of first publication or the end of the project period, whichever occurs first, and will remain available via the NDA repository for a minimum of 10 years or as long as NDA maintains the data.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   Data sharing will comply with participant informed consent for broad data sharing. All shared data will be de-identified to protect participant privacy. Access and reuse may be limited to non-commercial research purposes, consistent with consent and NDA policies. Any additional restrictions required by participant consent or institutional review board (IRB) will be documented in the NDA permissions.

2. **Whether access to scientific data will be controlled:**  
   Yes, access to the scientific data will be controlled. The NDA operates under a controlled-access model, requiring data use certifications and approval of data access requests to ensure responsible use and participant privacy.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All data will be de-identified prior to sharing, with removal of direct identifiers in accordance with HIPAA and NDA guidelines. Structural MRI data will be defaced to prevent facial recognition. Access to data will be granted only to qualified researchers under a data use agreement that includes provisions for confidentiality and appropriate data handling. The study will have a Certificate of Confidentiality and all procedures will be reviewed and approved by the IRB.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be monitored by the project’s Data Steward (PI or designated Data Manager). The Data Steward will oversee data collection, de-identification, documentation, and timely submission to the NDA, with review at quarterly lab meetings. Institutional oversight will be provided by the Office of Research Compliance, and adherence to the Plan will be reviewed annually in progress reports to NIH.