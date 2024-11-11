
# DNA Classification using Machine Learning

This project uses machine learning to classify DNA sequences as either promoters or non-promoters. 

**Dataset:**

The project utilizes the "Molecular Biology (Promoter Gene Sequences) Data Set" from the UCI repository. This dataset contains 106 gene sequences, 53 promoters (+) and 53 non-promoters (-). Each sequence is represented by 57 nucleotide positions (A, G, T, C).

**Data Preprocessing:**

1. **Data Loading and Cleaning:** The data is loaded from the UCI repository and cleaned by removing tab characters.
2. **One-Hot Encoding:** Nucleotides are converted to numerical values using one-hot encoding to make them suitable for machine learning algorithms.
3. **Train-Test Split:** The data is divided into training and testing sets using a 75%-25% split for model training and evaluation.

**Machine Learning Models:**

The project explores the performance of several machine learning models, including:

* K-Nearest Neighbors
* Gaussian Process Classifier
* Decision Tree Classifier
* Random Forest Classifier
* Neural Network (MLPClassifier)
* AdaBoost Classifier
* Gaussian Naive Bayes
* Support Vector Machine (SVM) with Linear, RBF, and Sigmoid kernels

**Model Evaluation:**

Models are evaluated using 10-fold cross-validation and accuracy as the scoring metric. The classification report provides detailed insights into precision, recall, F1-score, and support for each class.

**Results:**

The results show that SVM (linear kernel) and Neural Network (MLPClassifier) exhibit the best performance on this dataset, achieving high accuracy, precision, and recall. Other models may require further hyperparameter tuning to improve their performance.

**Conclusion:**

This project demonstrates the potential of machine learning in DNA classification for identifying promoter sequences. The insights gained from the model evaluation can guide further research and applications in bioinformatics and computational biology.
