## BUET Multi-Center Colposcopy Dataset

### Overview
This repository contains a novel, multi-center colposcopy dataset created to address the limited representation of Bangladeshi patients in publicly available datasets. Curated in collaboration with multiple clinical sites in Dhaka, Bangladesh. This dataset provides a diverse and robust collection of clinical images and corresponding medical scores to aid in cervical cancer screening research. 

### Ethics & Data Privacy
Data collection and usage strictly adhered to ethical guidelines:
* **IRB Approval:** Protocols were approved by BUET and the respective collaborating clinical hospitals.
* **Patient Privacy:** A strict anonymization procedure was implemented to ensure no personally identifiable information (PII) was retained.
* **Informed Consent:** Participants explicitly provided informed consent and maintained the right to withdraw throughout the process.

### Dataset Structure
After filtering for cases with adequate documentation, the combined dataset comprises **768 patient cases**, yielding **3,072 images** in total. 

For each patient, a four-image series was obtained, corresponding to the following applications:
* Normal Saline
* Acetic Acid
* Green Filter
* Lugol’s Iodine

**Clinical Metadata Included:**
* Transformation zone type
* Total Swede score (which can be mapped to a provisional diagnosis)

### Swede Score Distribution
The clinical reports document five distinct Swede Score characteristics. The score distributions across the dataset are summarized in the table below:

| Characteristic | Score 0 | Score 1 | Score 2 |
| :--- | :--- | :--- | :--- |
| **Aceto-White Uptake** | 293 | 409 | 66 |
| **Margin and Surface** | 441 | 312 | 15 |
| **Vessels** | 635 | 84 | 49 |
| **Lesion Size** | 336 | 357 | 75 |
| **Iodine Staining** | 207 | 439 | 122 |
