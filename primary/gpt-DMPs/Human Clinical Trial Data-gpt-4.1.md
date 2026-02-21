```markdown
**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate both clinical and imaging data from a Phase 3, randomized, placebo-controlled, double-blind clinical trial of 360 mother-infant pairs (180 per arm) across three sites, studying early onset preeclampsia. The expected data include:
   - Clinical and laboratory data: Demographics, medical history, enrollment characteristics, serial physical exams, blood pressure readings, laboratory tests (urinalysis, angiogenic factors, uric acid, glycemia), pregnancy duration (days), and neonatal outcomes (birth weight, Apgar scores, anthropometry, NICU admissions, prognosis).
   - Infant follow-up data: Anthropometric measurements and neurodevelopmental assessments (Bayley Scales) at 3, 6, and 12 months.
   - Clinical imaging data: 
        - 2D Doppler images (.jpeg) and extracted metrics (pulsatility index, notching; .csv)
        - 3D fetal thigh images (.vol) and derived thigh volume metrics (.csv)
        - 2D fetal cardiac clips (DICOM) and extracted cardiac measurements (.csv)
   - Estimated data volume: Tabular data (REDCap/CSV) for 360 participants over multiple visits (~2 GB), clinical images (~1,000 JPEGs, ~10 GB), volumetric images (~360 VOL files, ~5 GB), cardiac DICOM clips (~360 files, ~10 GB).

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All deidentified, participant-level clinical, laboratory, and outcome data, as well as all deidentified imaging data (JPEG, VOL, DICOM), and their derived quantitative measurements (CSV) will be preserved and shared. The rationale is to maximize the value and reproducibility of the trial for future research on preeclampsia, maternal-fetal medicine, and neonatal development, as well as to comply with NIH and NICHD policies on broad data sharing.

3. **Metadata, other relevant data, and associated documentation:**   
   The following metadata and documentation will be made accessible:
   - Data dictionaries and variable codebooks
   - REDCap case report forms and data collection instruments
   - Study protocol and statistical analysis plan
   - Imaging acquisition protocols and processing SOPs
   - Data deidentification procedures
   - Consent form language regarding data sharing
   - Description of data structure and file formats
   - Visit schedule and measurement timing documentation

**Element 2: Related Tools, Software and/or Code:**  
Most shared data are in standard, open formats (CSV, JPEG, DICOM, VOL). Accessing VOL files may require specialized 3D medical imaging software (e.g., Amira, 3D Slicer, or similar open-source tools). DICOM files can be viewed with open-source DICOM viewers (e.g., OsiriX, RadiAnt, 3D Slicer). All software listed is freely available or has open-source versions. No proprietary code is required for basic data access.

**Element 3: Standards:**  
Clinical data will be structured according to the Clinical Data Interchange Standards Consortium (CDISC) Study Data Tabulation Model (SDTM) standards for clinical trials. Imaging metadata will follow DICOM standards for medical images. All data will be deidentified per HIPAA Safe Harbor guidelines. Variable names and coding will be consistent with CDISC Controlled Terminology. Study-level metadata will utilize NIH Common Data Elements (CDEs) where applicable, and data dictionaries will conform to FAIR principles (Findable, Accessible, Interoperable, Reusable).

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   Deidentified participant-level data and associated metadata will be deposited in the NICHD Data and Specimen Hub (DASH; https://dash.nichd.nih.gov/), an NIH-supported, domain-specific repository for maternal and child health research. Imaging data (DICOM, VOL, JPEG) will also be deposited in DASH or, if file size or modality requires, in a NIH-supported imaging repository such as the National Imaging Archive (NIA).

2. **How scientific data will be findable and identifiable:**   
   All datasets will be assigned persistent unique digital object identifiers (DOIs) by the repository. Metadata will be indexed and searchable via the DASH and NIA platforms. Study-level metadata will be registered in ClinicalTrials.gov and linked to the DASH record.

3. **When and how long the scientific data will be made available:**   
   Data will be made available no later than the time of first publication of primary results or at the end of the performance period, whichever comes first, in accordance with NIH policy. Data will remain accessible through the repository for a minimum of 10 years after study completion.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   There are no anticipated restrictions beyond those pertaining to the protection of participant privacy and confidentiality. All participants will provide informed consent for broad data sharing, including future unspecified research use. Data will be deidentified and will not include direct identifiers. Any residual risk of reidentification will be minimized by data aggregation for rare variables and suppression of small cell sizes where necessary.

2. **Whether access to scientific data will be controlled:**  
   Yes. Access to individual-level data will be controlled and managed through the NICHD DASH platform. Investigators must submit a data use request with an approved research plan and agree to data use terms, including not attempting reidentification.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All data will be deidentified according to HIPAA Safe Harbor standards before sharing. A Certificate of Confidentiality will be obtained from NIH to further protect participant information. Only study ID numbers will be used; all direct and indirect identifiers will be removed. Data use agreements will prohibit attempts at reidentification or redistribution of data outside of approved uses. Oversight will include periodic review of data access requests and adherence to consent terms.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be overseen by the study’s Data Management Committee, which includes the Principal Investigator, Project Data Manager, and Institutional Privacy Officer. The committee will meet quarterly to review data integrity, deidentification, repository submission status, and access logs. Annual reports of data sharing activities will be submitted to NICHD as part of progress reports. The Institutional Review Board (IRB) will review the data sharing protocol and monitor compliance with participant consent and privacy protections.
