**Element 1: Data Type**

1. **Types and amount of scientific data expected to be generated in the project:**   
   This project will generate secondary analysis datasets derived from two publicly available sources: the Baltimore Longitudinal Study of Aging (BLSA) and the OASIS-3 dataset. Data types will include processed clinical and cognitive assessments, MR imaging data (structural and functional), PET imaging data, APOE genotype status, and derived quantitative neuroimaging indices (e.g., BOLD local anisotropic correlation measures, Diffusion Tensor Imaging (DTI) indices such as fractional anisotropy, axial diffusivity, radial diffusivity, mean diffusivity). Additionally, new Fluorescence Optical Imaging (FOI) atlases in NIFTI format will be generated to delineate white matter (WM) and gray matter (GM) connectivity. The anticipated total data volume is approximately 500 GB, comprised mostly of neuroimaging atlas files and derived quantitative data matrices.

2. **Scientific data that will be preserved and shared, and the rationale for doing so:**  
   All derived analytic datasets, including voxelwise BOLD correlation maps, DTI template images, WM/GM connectivity atlases (NIFTI format), and summary statistics tables, will be preserved and shared. The rationale is to facilitate reproducibility, enable secondary use by other researchers, and provide normative data for future studies in aging and Alzheimer’s disease. Data directly obtained from BLSA and OASIS-3 will not be redistributed but can be accessed through the original repositories.

3. **Metadata, other relevant data, and associated documentation:**   
   Metadata will include detailed data dictionaries for all variables, processing pipelines and scripts (documented in README files), study protocols outlining analytic procedures, descriptions of spatial normalization and template creation methods, and documentation of inclusion/exclusion criteria. Where applicable, links to original data sources and instructions for accessing raw data will be provided.

**Element 2: Related Tools, Software and/or Code:**  
Specialized neuroimaging software will be required for accessing and manipulating the shared data, including FSL (FMRIB Software Library), SPM (Statistical Parametric Mapping), and ANTs (Advanced Normalization Tools), all of which are open-source and available for download. Custom scripts and pipelines (Python and MATLAB) used for data processing and analysis will be shared alongside the data via the data repository and GitHub, with documentation provided to facilitate reuse.

**Element 3: Standards:**  
Data and metadata will adhere to widely accepted neuroimaging standards, including the Brain Imaging Data Structure (BIDS) for organization and metadata, and NIFTI format for imaging data. Variable names, units, and definitions will follow the recommendations of the National Institute of Mental Health (NIMH) Data Archive and the Neuroimaging Data Model (NIDM) where possible. Data dictionaries will use standardized terminologies (e.g., Cognitive Atlas, LOINC) to enhance interoperability. All documentation and code will conform to FAIR (Findable, Accessible, Interoperable, Reusable) principles.

**Element 4: Data Preservation, Access, and Associated Timelines**

1. **Repository where scientific data and metadata will be archived:**   
   All newly generated data and documentation will be deposited in the OpenNeuro repository (https://openneuro.org/), which is an NIH-recognized data repository for neuroimaging data and supports BIDS-compliant datasets. Code will be archived in a public GitHub repository and linked to Zenodo for DOI assignment.

2. **How scientific data will be findable and identifiable:**   
   Data will be assigned a persistent Digital Object Identifier (DOI) upon deposition in OpenNeuro and Zenodo. Metadata will include keywords and descriptors to facilitate discovery through standard indexing tools and repository search functions.

3. **When and how long the scientific data will be made available:**   
   All data and associated materials will be made publicly available no later than the time of publication of main study results or at the end of the performance period, whichever occurs first. Data will remain available in the repository for at least 10 years, following repository guidelines and NIH policy.

**Element 5: Access, Distribution, or Reuse Considerations**

1. **Factors affecting subsequent access, distribution, or reuse of scientific data:**  
   All shared data will be de-identified and processed in accordance with HIPAA and institutional policies to protect participant privacy. No limitations are anticipated for the derived datasets, as original data sources (BLSA and OASIS-3) are already broadly accessible to qualified investigators. Users will be required to cite the source datasets and this project’s data appropriately in any reuse.

2. **Whether access to scientific data will be controlled:**  
   Access to the derived analytic datasets and atlases will be open and not controlled. However, users seeking to access raw BLSA or OASIS-3 data must apply directly to those repositories and comply with their data use agreements.

3. **Protections for privacy, rights, and confidentiality of human research participants:**   
   All data shared will be de-identified, with all direct and indirect identifiers removed in accordance with the HIPAA Privacy Rule and institutional review board (IRB) guidance. The original informed consent for BLSA and OASIS-3 participants includes broad data sharing. No individual-level identifiers will be included in any shared files. Data will be stored and managed on secure, access-controlled servers prior to public release.

**Element 6: Oversight of Data Management and Sharing:**  
Compliance with this Data Management and Sharing Plan will be overseen by the Principal Investigator (PI) and the project’s Data Steward. The PI will review data management activities quarterly, ensure timely deposition of data and associated materials, and coordinate with the institution’s Office of Research Compliance. The Data Steward will document data handling, prepare materials for sharing, and maintain records of data releases. Adherence to this Plan will be reported in annual progress reports to NIH.