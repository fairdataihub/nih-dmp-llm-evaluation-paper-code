```markdown
**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   This project will generate the following scientific data:
   - Quantitative and qualitative survey data from approximately 3,000 U.S. adults, collected via a survey instrument comprising 40-50 items (including fixed-scale and open-ended text responses). The anticipated size of the raw and processed survey datasets is approximately 1-2 GB.
   - Recoded and derived variables from the survey data, including variables based on open-ended text item coding.
   - Digitally recorded, semi-structured interviews with patients (n=40), healthcare providers (n=40), and industry professionals (n=20), with raw audio files and their corresponding deidentified, verbatim transcripts (approximately 100 total interviews; estimated data volume ~10-15 GB for audio and transcripts).
   - Coded qualitative data from interview transcripts, including codebooks and coding summary files.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   The following scientific data will be preserved and shared:
   - Deidentified, raw and recoded survey datasets, including open-ended text responses after review for privacy risks and appropriate redaction.
   - Final codebooks and coding summary files for qualitative analyses.
   - Deidentified, verbatim interview transcripts (raw audio will not be shared to further protect privacy).
   Data will be preserved and shared to maximize scientific value, promote reproducibility, and comply with NIH and NHGRI data sharing policies, while protecting participant privacy and any proprietary content.

3. **Metadata, other relevant data, and associated documentation:**   
   The following metadata and documentation will be made accessible:
   - Data dictionaries for all survey variables, including descriptions, coding schemas, and provenance (e.g., source measures, such as PhenX IDs where applicable).
   - Full survey instrument, including all items and response options.
   - Interview guides/protocols.
   - Qualitative codebooks and a summary of coding procedures.
   - Study protocols and consent forms.
   - Documentation of redaction and deidentification procedures.

**Element 2: Related Tools, Software and/or Code:**  
Most shared data will be provided in non-proprietary formats (e.g., CSV for quantitative data, TXT or PDF for transcripts and documentation). Coding summary files and codebooks will be in CSV or XLSX formats. If qualitative data analysis code is shared, it will be compatible with widely available open-source tools such as R (e.g., RQDA, tidytext) or NVivo. Any custom code used for data processing or coding will be shared via a public GitHub repository. No specialized or proprietary software will be required to access the primary data files.

**Element 3: Standards:**  
The following data standards will be applied:
- Survey variables will use standard nomenclature and variable definitions as defined in the PhenX Toolkit where applicable.
- Data and metadata will be formatted according to NIH-recommended standards for tabular data (e.g., CSV with accompanying data dictionaries).
- Qualitative data will be structured in accordance with COREQ (Consolidated Criteria for Reporting Qualitative Research) guidelines.
- Metadata standards recommended by the selected repository (e.g., dbGaP, NIH Generalist Repository) will be followed to ensure interoperability.
For proprietary survey items, only variable codes and general constructs will be documented, in accordance with permissions.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   Scientific data and metadata will be archived in the NIH-supported Generalist Repository (e.g., NIH Figshare, Dryad, or Zenodo) and/or NHGRI-designated repositories as appropriate. The final repository selection will be confirmed in consultation with the NHGRI program officer at time of data deposition.

2. **How scientific data will be findable and identifiable:**   
   All datasets and documentation will be assigned persistent unique digital object identifiers (DOIs) through the repository. Datasets will be indexed in the repository catalog with descriptive metadata to enable discoverability using standard search engines and NIH data discovery tools.

3. **When and how long the scientific data will be made available:**   
   Scientific data will be made available no later than the time of publication of the primary results or at the end of the project period, whichever comes first, in accordance with NIH policy. Data will remain available for at least 10 years from the date of publication/deposition, or as long as the selected repository maintains data.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All research participants will provide informed consent for broad data sharing. However, certain limitations will apply:
   - Open-ended survey responses and interview transcripts will be reviewed for privacy disclosure risks, and any information that could reasonably identify participants will be redacted prior to sharing.
   - Proprietary survey items will be described but not shared verbatim if not permitted by license agreements; derived variables may be shared.
   - Data use will be governed by repository terms and any applicable Data Use Agreements (DUA) to ensure ethical secondary use.

2. **Whether access to scientific data will be controlled:**  
   Survey and interview transcript data will be shared under a controlled access model. Access will be granted to qualified researchers upon request and approval, in accordance with repository procedures and DUA requirements. Codebooks, data dictionaries, and aggregated summaries will be openly accessible.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   The following measures will protect participant privacy and confidentiality:
   - All data will be deidentified prior to sharing, with removal of names, contact details, and any indirect identifiers.
   - Open-ended survey responses and interview transcripts will be reviewed and redacted for privacy risks.
   - A Certificate of Confidentiality will be obtained for the study.
   - All data sharing will comply with IRB-approved protocols and participant consent, including limitations on use of proprietary content.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be overseen by the project’s Data Steward (e.g., Project Data Manager), with quarterly review by the Principal Investigator and the Institutional Data Management Office. The Data Steward will ensure timely deposition of data, monitor data requests, and verify compliance with deidentification and sharing procedures. Oversight activities and compliance status will be documented in project reports and reviewed annually by the Institutional Review Board (IRB) and NHGRI program officials.
