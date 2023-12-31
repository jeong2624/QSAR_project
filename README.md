## Project name : QSAR (Quantitative Structure Activity Relationship) model for the relationship between PTP1B Inhibitor and IC50 value

#### Project time : 2021.11.09 - 2021.12.17

#### Description :
* The project was conducted as part of "Advanced chemoinformatics" class in the Department of Bioinformatics at Soongsil University, Korea.
* The purpose of this project is to build linear regression model by using "[pyqsar](https://onlinelibrary.wiley.com/doi/abs/10.1002/bkcs.11638)" module in python
* According to this project, I want to create a model that represents the relationship between the PTP-1B inhibitor and the IC50 value.
* We obtained the data from the [reference paper](https://www.tandfonline.com/doi/abs/10.1080/10799893.2020.1759092) below.
  
"Quantitative structure-activity relationship (QSAR) and design of novel ligands that demonstrate high potency and target selectivity as protein tyrosine phosphatase 1B (PTP 1B) inhibitors as an effective strategy used to model anti-diabetic agents", David Ebuka Arthur et al. (2020)

* To obtain an SDF file for PTP 1B inhibitors, we utilized the PubChem database by using the Substance ID (SID) number.
* For building QSAR model, we used PaDEL to generate descriptor.

  
#### Software & Package version
* Python 3.9.10
* PaDEL 2.21
* [pyqsar](https://github.com/crong-k/pyqsar_tutorial)
* rdkit 2021.09.4


