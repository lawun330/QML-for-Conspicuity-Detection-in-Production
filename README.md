# QML-for-Conspicuity-Detection-in-Production

Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:

  - Maximum team size = 2
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:

  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with Fraunhofer ITWM. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:

  - Click [here](https://drive.google.com/file/d/1AcctFeXjchtEhYzPUsHpP_b4HGlI4kq9/view?usp=sharing) to view the project description.
  - YouTube recording of the project description - [link](https://youtu.be/Ac1ihFcTRTc?si=i6AIVfQQh8ymYQYp)

## Project Submission:

All information in this section will be considered for project submission and judging.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third-party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.

### Team Information:

Team Member 1:
 - Full Name: La Wun Nannda
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx): WQ24-G58ujBYY1tLxtO3

Team Member 2:
 - Full Name: Chit Zin Win
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx): WQ24-VDCiq5LYVoOJjeJ

### Project Solution:

With limited internet access and time, we initially completed three of the five project deliverables before the submission date, and have now finished all five tasks:

1. We finish the codebook sections “Introduction to Quantum Computing”, “Single-Qubit Gates” and “Circuits with Many Qubits” from the [PennyLane Codebook](https://pennylane.ai/codebook/). The repository contains the corresponding notebooks for this task. They are named with an initial of `Pennylane I... .ipynb`.

2. We implement and present the usual steps of the tutorial [Variational Classifier](https://pennylane.ai/qml/demos/tutorial_variational_classifier/) with our own words. The notebook file is named `Task 2. Variational_Classifier.ipynb`. Necessary data is in the directory `variational_classifier/data`.

3. We implement and present our steps in a notebook and comment on the important steps for the tutorial [Quanvolutional Neural Networks](https://pennylane.ai/qml/demos/tutorial_quanvolution/). The notebook file is named `Task 3. Quanvolutional_Neural_Networks.ipynb` and the directory `quanvolution` contains quantum pre-processed data.

4. We prepare a weld defect dataset for conspicuity detection in a production-like setting. Following the project specification, we select a balanced subset of six defect classes, resize and normalize the images, and organize them into reproducible train/test splits. These steps are documented in `Task 5.1. QML_for_Conspicuity_Detection.ipynb`, and the prepared images are stored in the `conspicuity_production_data` directory.

5. We build and compare a classical CNN and a quanvolutional neural network (QNN) for conspicuity detection on the prepared weld dataset. Using a shared classifier architecture, we apply a quantum preprocessing layer (quanvolution) to generate quantum feature maps, train both models on the same train/test split, and evaluate them with validation curves, confusion matrices, and per-class metrics. The full pipeline and analysis are documented in `Task 5.2. QML_for_Conspicuity_Detection.ipynb`, with cached quanvolved data in `quanvolution/conspicuity_production_data`.

All necessary code files and any additional information required to judge our project solution are included in the repository.

### Project Presentation Deck:

_Upload/ Link a 3min. presentation deck here._

See project presentation guidelines [here](https://docs.google.com/document/d/13nWF8AxFAfFYTWEYPT3BpPdYkqtxxSAjmuXj_zcMh-E/edit?usp=sharing)
