# .github
GitHub Repository Home Page for the University of Barcelona Integrative Crop Ecophysiology Research Group Doctor X UB Software Development

Doctor Nabat: Plant Disorder Diagnosis App
Description:
Doctor Nabat is a mobile and web application that uses a deep learning model to diagnose plant disorders. This tool was developed to assist farmers, particularly in the MENA region, by providing accurate and accessible diagnostic and treatment resources for common crop issues like diseases, pests, and nutrient deficiencies.

Publication Reference Information
This research has been submitted for consideration of publication and the full details of the publication will be updated below once available:
Buchaillot et al., 2024 Ecological Informatics "Framework for deep learning diagnosis of plant disorders in horticultural crops: from data collection tools to user-friendly web and mobile apps"

---------------------------------------------------------
Table of Contents
1. Overview
2. Materials and Methods
   - 2.1 Dataset Collection
   - 2.2 Data/Image Curation
   - 2.3 Development of the Algorithm
   - 2.4 Accessibility of the DL Model
3. Contributing
4. Contact Information
---------------------------------------------------------

1. Overview
Doctor Nabat leverages deep learning for real-time plant disorder diagnosis and treatment suggestions. By combining machine learning with user-centered design, the app aims to help smallholder farmers in the MENA region improve their crop management practices.
 
2. Materials and Methods
2.1 Dataset Collection
Images of diseased plant leaves were collected from trained agriculture technicians across Spain, Tunisia, Egypt, and the UAE. The data collection process used:
- Open Data Kit (ODK): This open-source application was used to build survey forms (XLSForms) for data collection. The ODK app allowed users to capture images and other relevant details (e.g., location, species) on mobile devices and upload them to an ODK Aggregate server hosted on Google Cloud.
- Website: https://getodk.org/

2.2 Data/Image Curation
Once collected, images were curated and organized for analysis using:
- ODK Downloader: An open-source JAVA application developed specifically to manage the large dataset efficiently. It downloaded and organized images and form data, allowing users to rename and sort files in a structured, multi-tiered folder system.
- GitLab Repository: https://gitlab.com/sckefauver/odk-downloader

2.3 Development of the Algorithm
The deep learning model was developed using a Convolutional Neural Network (CNN) architecture, optimized for high accuracy in classifying plant disorders. The development process utilized:
- Google Colab: Open-source programming environment used to load and process images from Google Drive for model training.
- Website: https://colab.research.google.com/
 Python Libraries: Various open-source Python libraries were used for data processing and model development, including: 
- TensorFlow and Keras for building and training the CNN model
- TensorFlow: https://www.tensorflow.org/
- Keras: https://keras.io/
- Pandas and Numpy for data manipulation
- Pandas: https://pandas.pydata.org/
- OpenCV for image preprocessing
- OpenCV: https://opencv.org/

2.4 Accessibility of the DL Model
The Doctor Nabat app was deployed on multiple platforms to ensure accessibility and ease of use.

- GitHub Repository: The trained deep learning models are accessible via a public GitHub repository, allowing others to deploy or contribute to the project.
- GitHub Repository: https://github.com/sckefauver/ml-icba
- Web-Based Application: A web app supporting multiple languages (English, French, Arabic) and accessible on major operating systems was developed, allowing users to upload images and receive diagnoses.
- Web App: https://drnabat.biosaline.org/icba
- Android Mobile Application: The app was also released as an Android application, enabling offline access for farmers in field conditions. It is free and accessible on Google Play.
- Android App: https://play.google.com/store/apps/details?id=org.drnabat

3. Contributing
Doctor Nabat is an open-source project, inviting contributions from developers, researchers, and agricultural experts. To contribute, visit the GitHub repository and follow the guidelines.

4. Contact Information
For questions, feedback, or suggestions, please contact the development team at sckefauver@ub.edu.

# Authors from the University of Barcelona Integrative Crop Ecophysiology Research Group
- Dr. Luisa Buchaillot
   - Lead Researcher as PhD Thesis, [University of Barcelona](http://www.ub.edu/)
- Prof. Jose Armando Fernandez Gallego
   - Expert in Artificial Intelligence, [University of Barcelona](http://www.ub.edu/) and [Universidad de Ibague](https://www.unibague.edu.co/). 
- Prof. José Luis Araus
   - Project Principal Investigator, [University of Barcelona](http://www.ub.edu/)
- Dr. Shawn C. Kefauver
   - Project Scientific Coordinator, [University of Barcelona](http://www.ub.edu/)

# Organizations
- Administered by [University of Barcelona](http://www.ub.edu/) / [Dept. B.E.E.C.A.](https://www.ub.edu/portal/web/dp-beeca/fisiologia-vegeta) / [Integrative Crop Ecophysiology Group](https://integrativecropecophysiology.com/) and [Universidad de Ibague](https://www.unibague.edu.co/). 
- We acknowledge support from the Institucio Catalana de Recerca i Estudis Avançats (ICREA), Generalitat de Catalunya, Spain, and the Ramon y Cajal RYC-2019-027818-I research fellowship from the Ministerio de Ciencia e Innovacion, Spain.
- The Doctor X UB ICBA project was compeleted in collaboration with the [International Center for Biosaline Agriculture] (ICBA)(https://www.biosaline.org/).
- We also acknowledge support from an anonymous donor for their generous support of the Doctor X UB ICBA project and the MENA region.

# License

Copyright 2024 Shawn C. Kefauver

Licensed under the General Public License version 3.0
- [http://www.gnu.org/licenses/gpl-3.0.en.html](http://www.gnu.org/licenses/gpl-3.0.en.html)
- [https://tldrlegal.com/license/gnu-general-public-license-v3-(gpl-3)](https://tldrlegal.com/license/gnu-general-public-license-v3-(gpl-3))
