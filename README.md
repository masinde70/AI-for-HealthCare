### AI-for-HealthCare

### 2D medical Imaging 
- How it fits into medicine and the healthcare system.
- How to use AI to solve 2D Imaging problems 
- How to take AI from the bench to bedside to be used by doctors to improve patient lives

#### New terms
- **X-ray:** a 2D imaging technique that projects a type of radiation called x-rays down at the body from a single direction to capture a single image.
- Ultrasound: a 2D imaging technique that uses high-frequency sound waves to generate images.
- Computed Tomography (CT): a 3D imaging technique that emits x-rays from many different angles around the human body to capture more detail from more different angles.
- Magnetic Resonance Imaging (MRI): a 3D imaging technique that uses strong magnetic fields and radio waves to create images of areas of the body from all different angles.
- 2D imaging: an imaging technique that pictures are taken from a single angle.
- 3D imaging: an imaging technique that pictures are taken from different angles to create a volume of images.

##### Medical Imaging Workflow
- Picture Archiving and Communication System (PACS)
  * Every Imaging center and hospital have PACS. These systems allows for all medical imaging to be stored in the hospital's servers and transferred to different departments  throughout the hospital.
- Diagnostic Imaging 
  * In diagnostic situations, a clinitian orders an imaging study because they believe that a disease may be present based on the patient's symptoms. Diagnostic imaging can be performed in emergency settings as well as non-emergency settings.
    - Clinical believes something is wrong with the patient 
    - Need imaging to verify
    - e.g diagnosing brain tumor
- Screening
Screening studies are performed on populations of individuals who fall into risk groups for certain diseases. These tend to be diseases that are relatively common, have serious consequences, but also have the potential of being reversed if detected and treated early. For example, individuals who are above a certain age with a long smoking history are candidates for lung cancer screening which is performed using x-rays on an annual basis.
  * Nothing acutely wrong with the patient 
  * Patient in risk group for particular diseases
  * Imaging regularly for early detection
  * e.g regular screening for colonscopies because of family history.
 
 
 ### Application of Algorithms 
 * Track progression growth of tumour overtime -> Segmentation 
 * Identify the area of the lung where the fluid is -> Localization
 * Determine whether a tumor is malignant or benign -> Classification 
 
 ## key points
 * Model
 * Heuristic
 * Bernoul Distribution
 * Prior
 * Likelihood
 * Evidence
 * Posterior
 * Vocabulary 
 * Laplace Smoothing
 * Tokenization
 * Featurization
 * Lemmatization
 * Stemming 
 * Stop Word
 * Vectorizer
   Used in a step featurizing. It transforms some input into something else. One example is binary vectorizer which transforms tokenized messages into a binary vector indicating which items in the vocabulary appear in the message
 * Featurization
    The processin of transforming raw inputs into somethinga model can perform training and prediction on.
    
  ## Key stake holders
  
  #### Clinical Stakeholders
  Clinical stakeholders are radiologists, diagnosing clinicians and patients. Radiologists are likely the end-users of an AI application for 2D imaging. They care about low disruption to workflow and they play an important advisory role in the algorithm development process. Clinicians have less visibility into the inner workings of an algorithm. They also care about low disruption to workflows and they care about the interpretability of algorithm output.
  
  #### Industry Stakeholders
  Industry stakeholders include medical device companies, software companies, and hospitals. Many medical device companies typically have accompanying imaging software
  
  #### Regulatory Stakeholders
  
  The main regulatory stakeholder in the medical imaging world is the Food and Drug Administration (FDA). The FDA treats AI algorithms as medical devices. Medical devices are broken down into three classes by the FDA, Class I, Class II, and Class III, based on their potential risks present to the patient. A device's class dictates the safety controls, which in turn dictates which regulatory pathway they must go down. The two main regulatory pathways for medical devices are 510(k) and Pre-market Approval (PMA). Lower risk devices (Classes I & II) usually take a 501(k) submission pathway. Higher risk devices and algorithms (Class III) must go through PMA.
 
 
 
  
## Glossary
* **X-Ray:** Type of 2D imaging that uses a type of radiation to take pictures of the body's internal structures.
* **Computed Tomography:** Type of 3D imaging that uses x-rays to take pictures at multiple angles of the body's internal structures.
* **Magnetic Resonance Imaging:** Type of 3D imaging that uses radio waves and strong magnetic fields at multiple angles to take pictures of the body's internal structures
* **Mammogram:** A type of 2D x-ray that is specialized for breast imaging
* **Digital Pathology:** A type of 2D imaging that involves the digitization of microscopy images of cell-level biological material
* **Radiologist:** A specialized type of clinician who is trained to read medical imaging data
* **PACS:** Picture archiving and communication system, used for storing and viewing medical images within and across hospitals
* **Screening:** A type of test that is performed on individuals who are in a risk group for a given disease
* **Sensitivity:** Proportion of accurately identified positive cases that a test returns
* **Specificity:** Proportion of accurately identified negative cases that a test returns


### Medical Image Exploratory Data Analysis
#### DICOM
DICOM "Digital Imaging and Communications in Medicine", which is the standard for the communication and management of medical imaging information and related data.



