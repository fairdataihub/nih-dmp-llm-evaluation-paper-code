**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   The project will generate multimodal datasets from 50 to 80 mouse subjects, comprising:  
   - Electrophysiology data: Raw extracellular voltage recordings and processed spike time data from 64-channel probes targeted to the mouse hippocampus; estimated data volume to be shared is 100–1000 GB.  
   - Behavioral data: Raw video recordings of spatial navigation behavior (freely moving mice in an arena) and processed positional and heading data for each frame; estimated data volume is 10–100 GB.  
   - Imaging data: Confocal microscopy 3-color image stacks of immunostained brain tissue, used to verify probe placement in the hippocampus; estimated data volume is 1–10 GB.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All raw and processed electrophysiology data, behavioral videos and derived trajectory data, and confocal microscopy image stacks will be preserved and shared. Sharing these datasets will enable reproducibility, secondary analyses, and comparison with other hippocampal studies, thereby maximizing the scientific value and impact of the research.

3. **Metadata, other relevant data, and associated documentation:**   
   Metadata to be shared will include:  
   - Subject-level information (age, sex, genotype, experimental group)  
   - Experimental protocols and procedures (surgery, behavioral tasks, electrophysiological recording parameters, imaging protocols)  
   - Data acquisition settings (hardware and software versions, sampling rates, filtering parameters)  
   - Data processing pipelines and code  
   - Data dictionaries and README files explaining data organization and formats  
   - Protocols for behavioral tests and image acquisition

**Element 2: Related Tools, Software and/or Code:**  
Specialized tools are required for data access and analysis:  
- Electrophysiology data: Open Ephys GUI, SpikeInterface, and custom Python/MATLAB scripts (to be shared via GitHub).  
- Behavioral data: OpenCV (Python) for video processing, DeepLabCut for pose estimation, and custom scripts (to be shared).  
- Imaging data: FIJI/ImageJ for confocal image viewing and analysis (open source).  
All custom code used for data processing and analysis will be made available in public repositories (e.g., GitHub) with documentation. All third-party tools are open source and freely available.

**Element 3: Standards:**  
The following data and metadata standards will be applied:  
- Electrophysiology data: Neurodata Without Borders (NWB:N 2.0) format for storing and sharing raw and processed data.  
- Behavioral data: Pose and trajectory data will be stored in CSV or HDF5 formats with metadata following the NWB extension where applicable.  
- Imaging data: Confocal image stacks will be provided in OME-TIFF format compliant with the Open Microscopy Environment (OME) standard.  
- Metadata: Organized according to the Minimum Information About a Neuroscience Investigation (MINI) guidelines and NWB metadata schemas.  
These standards will facilitate interoperability and reuse.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   - Electrophysiology and behavioral data: OpenNeuro (https://openneuro.org)  
   - Imaging data: The Brain Image Library (BIL; https://www.brainimagelibrary.org)  
   - Code and documentation: GitHub and Zenodo for archival and DOI assignment

2. **How scientific data will be findable and identifiable:**   
   Datasets will be assigned persistent unique identifiers (DOIs) by the respective repositories (OpenNeuro, BIL, Zenodo). Metadata will include searchable keywords, and datasets will be indexed in public repository catalogs.

3. **When and how long the scientific data will be made available:**   
   Data will be made publicly available at the time of publication of the primary results or at the end of the award period, whichever comes first, in accordance with NIH policy. Data will remain available for at least 10 years or as long as the repository infrastructure is maintained.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All data are derived from non-human (mouse) subjects and do not contain personally identifiable information. No factors are anticipated to limit access, distribution, or reuse.

2. **Whether access to scientific data will be controlled:**  
   All data will be openly available (uncontrolled access) upon release in the designated repositories.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   Not applicable; no human subjects are involved in this research.

**Element 6: Oversight of Data Management and Sharing:**  
The Principal Investigator (PI) will be responsible for compliance with this Plan, with day-to-day oversight by the project’s Data Steward (lab manager or designated research staff). The PI and Data Steward will review data management activities quarterly, ensure data are appropriately documented, and verify timely deposition in repositories. The institution’s Office of Research Compliance will conduct annual audits to ensure adherence to NIH DMS policy.