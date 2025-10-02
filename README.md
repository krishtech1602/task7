 Task 7: Support Vector Machines (SVM)
 Objective

Implement SVM (Support Vector Machine) for binary classification using Linear and RBF kernels, perform hyperparameter tuning, and visualize decision boundaries.

 Tools & Libraries

Python

NumPy, Matplotlib

Scikit-learn

 Dataset

Breast Cancer dataset (sklearn.datasets)

Target: Malignant (0) / Benign (1)

Steps

Load and preprocess dataset (scaling, train-test split).

Train Linear SVM and RBF SVM.

Tune parameters C and gamma using GridSearchCV.

Evaluate models with classification report & cross-validation.

Visualize decision boundaries (2D features).

 Results

Best RBF parameters found via GridSearchCV.

Accuracy ~95–97% (varies slightly).

Linear SVM → Straight margin.

RBF SVM → Non-linear curved margin.
