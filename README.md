# bioinformaticsProject
Cancer classification based on gene expression; explored SVM-based cancer classification based on gene expression profiles.

## Dataset
`duke breast-cancer` provided on the [LIBSVM website](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html#duke%20breast-cancer)

Details:
- Source: `MW01a`
- Preprocessing: Instance-wise normalization to mean zero and variance one. Then feature-
wise normalization to mean zero and variance one. The data are split into training (38), and
validation (4). `SKS03a`
- No. of classes: 2
- No. # of data: 44
- Np. of features: 7,129

Files:
- duke.bz2 (combined)
- duke.tr.bz2 (tr)
- duke.val.bz2 (val)

## SVM tool: 
You can use SVM in packages such as Weka, python scikit_learn, or others you know.

### Steps:
1) Load the dataset
(example: http://sbbi-panda.unl.edu/svm-workshop/materials/classification_grid_search.html)
2) Performed PCA analysis
(example: http://sbbi-panda.unl.edu/svm-workshop/materials/classification_grid_search.html)
3) Built a classifier (try different kernels such as linear and RBF kernels)
(example: http://sbbi-panda.unl.edu/svm-workshop/materials/classification_grid_search.html)
a. feature selection
b. grid search for optimal parameters
c. Evaluated the performance using selected matrices, e.g., accuracy,
sensitivity, specificity, or MCC.
4) Compared the performances by using different kernels, reduced
features, or different measure matrices
Recorded what you have done for each task and observations in the report summarizing the results when different settings are used.
