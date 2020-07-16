# Classification_SVM_algorithm_human_cell_dataset_python
we used SVM (Support Vector Machines) to build and train a model using human cell records, and classify cells to whether the samples are benign or malignant.
## SVM
SVM works by mapping data to a high-dimensional feature space so that data points can be categorized, even when the data are not linearly separable. A separator between the categories is found, then the data is transformed in such a way that the separator could be drawn as a hyperplane. Following this, characteristics of new data can be used to predict the group to which a new record should belong.
## Data
The dataset consists of several hundred human cell sample records, each of which contains the values of a set of cell characteristics. The fields in each record are:
ID: patient identifier , Clump: Clump thickness , UnifSize: Uniformity of cell size , UnifShape: Uniformity of cell shape , MargAdh: Marginal adhesion , SingEpiSize: Single epithelial cell size , BareNu: Bare nuclei , BlandChrom: Bland chromatin , NormNucl: Normal nucleoli , Mit: Mitoses , Class: Benign or malignant
## libraries 
- pandas
- numpy
- scikit learn
- mathplotlib
## Algorithm
- support vector machine
## program language
- python
## methods for evaluating
- Confusion Matrix
- Jaccard index
## Analysis
1- distribution of the classes based on Clump thickness and Uniformity of cell size
![1](https://user-images.githubusercontent.com/56628918/87679621-b1bc4800-c77c-11ea-807e-2459d3e83f73.png)

2- confusion matrix

![1](https://user-images.githubusercontent.com/56628918/87679785-e29c7d00-c77c-11ea-9366-325d22a30ea3.png)
