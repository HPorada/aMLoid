# aMLoid
## Analysis of cross-interactions of amyloid signaling sequences using machine learning techniques

### Introduction
The repository contains the code and datasets used in the master's thesis project, "Analysis of cross-interactions of amyloid signaling sequences using machine learning techniques". The project focused on implementation and analysis of chosen machine learning solutions, considering their usage for the analysis of interacting amyloid sequences.

### Abstract
Amyloid sequences are a group of proteins that usually serve signaling or structural functions. Due to their ability to form amyloids - aggregates composed of fibers that accumulate in tissues - they are associated with human protein misfolding diseases, such as Alzheimer's disease, Parkinson's disease, or type II diabetes. The structural and signaling functions of amyloid motifs have been extensively studied in sequences derived from fungi and bacteria.

Machine learning is a broad field based on algorithms and techniques designed to make computer programs resemble human intelligence. Particularly important are the abilities of autonomous learning and improvement through information processing. Among numerous types of machine learning algorithms, deep learning stands out. It utilizes neural networks, which, after analyzing potential project development paths, were chosen for the project implementation.

The aim of the conducted diploma thesis was to analyze cross-interactions of amyloid signalling sequences using selected machine learning techniques. For training the models in the project, a dataset containing amyloid signal sequences from selected publications focusing on the functions of amyloids in fungal and bacterial organisms was used. The dataset consists of 600 pairs of interacting sequences.

Within the project, three types of tasks were proposed, implemented, tested, and analyzed using neural networks:
1. Gap filling in an amyloid sequence.
2. Gap filling in an amyloid sequence considering a second sequence involved in the interaction.
3. Generation of amyloid sequences using GAN (Generative Adversarial Network) models.
Each experiment was described in subsequent chapters, including data preprocessing, discussion of proposed models, implementation details, presentation of results, and the conclusions drawn based on them.

In general, the obtained results indicate that the use of selected machine learning techniques may be effective in analyzing interactions between amyloid sequences. However, it is crucial to properly select and prepare the dataset and choose an appropriate machine learning model structure suitable for the task at hand.

### Datasets
Datasets used in the project were obtained from publications:
1. Motif HRAM - Daskalov A, Dyrka W, Saupe S, ,,Theme and variations: evolutionary diversification of the HET-s functional amyloid motif'', Sci Rep 5, 2015, doi: 10.1038/srep12494
2. Motif BASS - Dyrka W, Coustou V, Daskalov A, Lends A, Bardin T, et al, ,,Identification of NLR-associated Amyloid Signaling Motifs in Bacterial Genomes'', Journal of Molecular Biology, 2020, doi: 10.1016/j.jmb.2020.10.004.
3. Many different motifs - Wojciechowski JW, Tekoglu E, Gąsior-Głogowska M, Coustou V, Szulc N, et al, ,,Exploring a diverse world of effector domains and amyloid signaling motifs in fungal NLR proteins'', PLOS Computational Biology 18, 2022, doi: 10.1371/journal.pcbi.1010787

### Notebooks
Repository contains Jupyter notebooks, providing step-by-step explaination of implementation process and obtained results.

### Dependencies
The project code and notebooks have dependencies on the following libraries and frameworks:
* TensorFlow
* Keras
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

Ensure that you have the required dependencies installed in your environment to run the code successfully.

### License
The code and datasets in this repository are provided under the MIT License. You are free to use, modify, and distribute the code and datasets for academic, research, or personal purposes.

If you use this code or datasets in your work, we kindly request that you cite the original project repository and give appropriate credit.
