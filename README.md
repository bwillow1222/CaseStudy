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
│   
├── LICENSE.md              # License file (MIT License)
├── README.md               # This file
└── 

```
## Instructions for Reproducing Results

1. **Clone the repository**:
   ```bash
   git clone https://github.com/bwillow1222/ds4003MI3P3.git
   cd project
2. **Install the required packages**
   ```bash
   pip install -r requirements.txt
3. **Run data preprocessing**
   ```bash
   jupyter notebook SCRIPTS/ImagePreprocess.ipynb
4. **Model implementation**
   ```bash
   jupyter notebook SCRIPTS/PetImages.ipynb
5. **Check the results:**
   View the visualizations and performance metrics in the `OUTPUT/` folder.

## References
[1] A. Parkhi, A. Vedaldi, A. Zisserman, and C. V. Jawahar, "The Oxford-IIIT Pet Dataset," Visual Geometry Group, University of Oxford, 2012. [Online]. Available: https://www.robots.ox.ac.uk/~vgg/data/pets/

[2] N. Chaure, "Variants of ResNet: A Comparative Analysis," Medium, 2020. [Online]. Available: https://medium.com/@nayanchaure601/variants-of-resnet-a-comparative-analysis-63fdc1573b34

[3] Analytics Vidhya, "Top 4 Pre-Trained Models for Image Classification + Python Code," 2020. [Online]. Available: https://www.analyticsvidhya.com/blog/2020/08/top-4-pre-trained-models-for-image-classification-with-python-code/#h-resnet50
