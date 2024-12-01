# Implementation of paper - Privacy-Preserving Machine Learning for Collaborative Agriculture Research


<!-- ABOUT THE PROJECT -->
### Author Information

####  Osama Zafar
- **Institution**: Case Western Reserve University  
- **City**: Cleveland  
- **State**: Ohio  
- **Email**: [oxz23@case.edu](mailto:oxz23@case.edu)

####  Rosemarie Santa González
- **Institution**: Georgia Institute of Technology  
- **City**: Atlanta  
- **State**: Georgia  
- **Email**: [rgonzalez308@gatech.edu](mailto:rgonzalez308@gatech.edu)

####  Gabriel Wilkins
- **Institution**: University of Wisconsin–Madison  
- **City**: Madison  
- **State**: Wisconsin  
- **Email**: [gwilkins@wisc.edu](mailto:gwilkins@wisc.edu)

####  Alfonso Morales
- **Institution**: University of Wisconsin–Madison  
- **City**: Madison  
- **State**: Wisconsin  
- **Email**: [morales1@wisc.edu](mailto:morales1@wisc.edu)

####  Erman Ayday
- **Institution**: Case Western Reserve University  
- **City**: Cleveland  
- **State**: Ohio  
- **Email**: [exa208@case.edu](mailto:exa208@case.edu)

<!-- ABOUT THE PROJECT -->
## About The Project

We propose a privacy-preserving framework that enables secure data sharing for research and development while mitigating privacy risks. The framework combines dimensionality reduction techniques (i.e., Principal Component Analysis (PCA), and differential privacy by introducing Laplacian noise) to protect sensitive information. The proposed framework is validated on real-life datasets. We demonstrate how this framework can facilitate collaboration among farmers, be used to train machine learning (ML) models, and secure data aggregation to support broader research objectives. The adoption of the framework can empower researchers and policymakers to leverage agricultural data responsibly, paving the way for transformative advances in data-driven agriculture. By addressing critical privacy challenges, this work supports secure data integration, fostering innovation and sustainability in agricultural systems.



<!-- GETTING STARTED -->
## Getting Started

These are Jupyter Notebooks compatible with Google Colab. To run, you can upload each notebook and all relevant CSV files and execute all cells. All notebooks are stand alone and can be executed independent of each other
Privacy_Preserving_Clustering(Crop Recommendation Dataset).ipynb
Privacy_Preserving_Clustering_(Wisconsin_Dataset).ipynb
Privacy_Preserving_Fed_ML_Model_Training (Crop Recommendation Dataset).ipynb

For local execution please consult the first cell of the executing notebook for all the imported libraries.
<!-- Architecture Workflow: -->
## Architecture Workflow

- Researchers use a global PCA model on public data to identify desired farmer attributes.
- Farmers transform their private data as differentially-private PCA outputs.
- The researcher combines transformed data to identify farmers with desired attributes.
- The researchers receive differentially-private PCA outputs from farmers.
- Identifies farmers with desired attributes without direct access to private datasets.
- Researchers query aggregated information from identified farmers.
- Links private farmer data with public agriculture datasets for analysis

