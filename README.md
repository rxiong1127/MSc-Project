# MSc Project

This repository contains the code and resources for my MSc project on **uncertainty-aware machine learning for particle physics**.  
It is organized into two main parts:

---

## 1. Jet Reconstruction
- Includes the files required for **event generation, jet reconstruction, and preliminary analysis**.  
- **Preliminary analysis**: requires results that are ended as `.yoda`.  
- **Event generation for classifier training**: events are exported to CSV using `.hepmc` files as input.  

---

## 2. Classifiers
- Includes the files required for **data preparation, classifier construction, and result analysis**.  
- The training and testing of the three classifiers (Baseline, Data-Augmented, and Uncertainty-Aware) are implemented in:  
  - `Classifiers_BA/DA/UA.ipynb`  
- Performance analysis is performed in:  
  - `analyse_result.ipynb`  

## **Important:**  
To ensure smooth execution, need to place the required CSV files for each round of training and testing in the **same directory** as `Classifiers_BA/DA/UA.ipynb`. 
To access the CSV files used in this study, go for the link: https://drive.google.com/drive/folders/1CjbbxI8ZGcNhibPPvoBXDqnwCde9QgqT?usp=drive_link
