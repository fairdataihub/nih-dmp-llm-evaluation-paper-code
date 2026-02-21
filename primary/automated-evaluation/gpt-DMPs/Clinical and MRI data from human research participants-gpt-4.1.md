**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate multimodal data from 220 youth (110 affected and 110 healthy controls). Data collected will include:
   - Demographic data (e.g., age, sex, race/ethnicity, education)
   - Clinical assessment data (psychiatric interviews, rating scales, diagnostic information)
   - Neuroimaging data:
     - Structural MRI scans (T1-weighted, T2-weighted images)
     - Functional magnetic resonance imaging (fMRI) data
     - Proton magnetic resonance spectroscopy (^1H fMRS) data
   The estimated data volume is approximately 1-2 GB per participant, with total expected data generation of 220-440 GB.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All de-identified demographic, clinical, and imaging data (structural MRI, fMRI, and ^1H fMRS) will be preserved and shared. Sharing these data will facilitate secondary analyses, promote transparency and reproducibility, and enable data aggregation across studies in alignment with NIMH and NIH data sharing policies. Only data necessary to generate the NIMH Data Archive (NDA) global unique identifier (GUID) will be retained for participant identification within the repository.

3. **Metadata, other relevant data, and associated documentation:**   
   The following metadata and documentation will be provided:
   - Data dictionaries describing all clinical and demographic variables
   - Imaging acquisition parameters and protocols (including scanner models, pulse sequences, and preprocessing steps)
   - Data collection instruments and case report forms
   - Study protocol and informed consent templates
   - Documentation of quality control procedures and data preprocessing pipelines

**Element 2: Related Tools, Software and/or Code:**  
Standard neuroimaging data formats (e.g., NIfTI for MRI, BIDS for data organization) will be used. Analysis and visualization may require commonly available software such as SPM, FSL, AFNI, or LCModel for ^1H fMRS data; these are freely available to the research community. Custom scripts used for preprocessing or analysis will be documented and shared as supplementary materials or via a public repository such as GitHub.

**Element 3: Standards:**  
Data and metadata will be organized and formatted following the Brain Imaging Data Structure (BIDS) standard, which promotes interoperability and reuse. Imaging files will be provided in NIfTI format, and clinical/demographic data will be in CSV or JSON format with accompanying data dictionaries. The NDA data dictionary and variable naming conventions will be used to harmonize with existing NIMH Data Archive submissions. No proprietary or non-standard formats will be used.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   All data and corresponding metadata will be archived in the NIMH Data Archive (NDA; https://nda.nih.gov/), an NIH-designated repository for mental health research data.

2. **How scientific data will be findable and identifiable:**   
   Data will be assigned NDA study and collection identifiers, and each participant will be assigned a global unique identifier (GUID) to enable data linkage across studies while maintaining privacy. Data will be indexed and searchable in the NDA with persistent unique identifiers and metadata descriptors.

3. **When and how long the scientific data will be made available:**   
   Scientific data will be submitted to the NDA and made available no later than the time of publication of major findings or at the end of the grant performance period, whichever occurs first. Data will remain available in the NDA for at least 10 years after the end of the project, in accordance with NIH and NDA policies.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All participants will be consented for broad data sharing; however, data use will be limited to research consistent with the consent provided (broad research use). Data will be shared in de-identified form, with removal of all direct identifiers. Access limitations may apply to protect privacy and comply with IRB requirements, but no additional restrictions are anticipated.

2. **Whether access to scientific data will be controlled:**  
   Yes, access will be controlled. The NDA operates under a controlled-access model, requiring data use certification and agreement to terms of use, including protection of participant confidentiality.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All data will be de-identified prior to sharing. GUIDs will be used to link participant data across datasets without exposing identifiable information. Direct identifiers will be removed, and indirect identifiers will be minimized. All data sharing will comply with institutional IRB requirements and HIPAA. The project will utilize a Certificate of Confidentiality and follow NDA data submission and sharing guidelines to ensure robust privacy and confidentiality protections.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be overseen by the Principal Investigator (PI) and the study Data Manager. The PI will be responsible for ensuring timely submission of data and documentation to the NDA, with quarterly internal reviews of data sharing progress. The Data Manager will coordinate data de-identification, metadata preparation, and submission logistics. The institution’s Office of Research Compliance will provide periodic oversight to ensure adherence to NIH and institutional policies.