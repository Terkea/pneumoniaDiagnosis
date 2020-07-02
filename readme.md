The dataset used to conduct this experiment was obtained from [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).
To be able run this notebook locally download the dataset from the link provided and delete the `.DS_Store` files.

# Motivation
The implementation of clinical-decision support algorithms for medical imaging faces challenges with reliability and interpretability. Here, we establish a diagnostic tool based on a deep-learning framework for the screening of patients with common treatable blinding retinal diseases. Our framework utilizes transfer learning, which trains a neural network with a fraction of the data of conventional approaches. Applying this approach to a dataset of optical coherence tomography images, we demonstrate performance comparable to that of human experts in classifying age-related macular degeneration and diabetic macular edema. We also provide a more transparent and interpretable diagnosis by highlighting the regions recognized by the neural network. We further demonstrate the general applicability of our AI system for diagnosis of pediatric pneumonia using chest X-ray images. This tool may ultimately aid in expediting the diagnosis and referral of these treatable conditions, thereby facilitating earlier treatment, resulting in improved clinical outcomes.
Text preluated from [Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning](https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5)

# Content
The dataset is organized into 3 folders `(train, test, val)` and contains subfolders for each image category `(Pneumonia/Normal)`. There are `5,863 X-Ray images` (JPEG) and `2 categories` (Pneumonia/Normal).
Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.


## [Open the notebook](./notebook.ipynb)