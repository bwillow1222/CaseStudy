# Case Study: Pet Breed Identification Image Analysis

## Project Overview
Welcome to the case study. Here are all the relevant resources including data, code, and documents. Good luck!

## Software and Platform

### Software:
- **Python 3.8 or higher**

### Required Packages
- **Pandas**: For data manipulation.  
- **Numpy**: For numerical computations.  
- **Matplotlib**/**Seaborn**: For visualizing data distribution and model performance.  
- **PyTorch**: For implementing and fine-tuning the pre-trained neural network (ResNet50).  
- **Jupyter Notebook**: For running and documenting the analysis.

### Platform:
- The project was run in the Rivanna HPC, as access to NVIDIA CUDA is necessary

---

## Map of Repository Structure
```plaintext
bwillow1222/ds4002MI3P3
│
├── DATA/                   # Contains datasets used in the project
│   ├── Data_Dictionary.pdf           # Document explaining dataset structure and variables
│   └── README.md                     # Directions to the source of raw data
│
├── OUTPUT/                 # Contains output figures and tables generated by the project
│   ├── breedDistribution.png               # Breed distribution histogram
│   └─  sampleImage.jpg                     # Representative image used in the study
│
├── SCRIPTS/                # Contains all the Python scripts
│   ├── ImageEDA.ipynb             # Script for data distribution and exploratory plots
│   ├── ImagePreprocess.ipynb      # Script for data cleaning, resizing, and augmentation
│   └── PetImages50.ipynb          # Script testing with many epochs for model tuning
│
├── SOURCES/
│   ├── Cats_and_Dogs.pdf             # Oxford pet breed identification research
│   └── 2023_Shelter_Rport.pdf        # 2023 animal shelter report
│   
├── LICENSE.md              # License file (MIT License)
├── README.md               # This file
└── Rubric.pdf              # File containing instructions for the case study
