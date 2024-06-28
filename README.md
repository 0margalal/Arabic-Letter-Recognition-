## Project: Arabic Character Recognition using Machine Learning

Overview
This project involves recognizing Arabic handwritten characters using three different machine learning models: Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Neural Networks (NN). The dataset consists of images of Arabic characters flattened into CSV files.

Dataset
Training Images: 13,440 samples, each of size 32x32 pixels, flattened into a 1024-length vector.
Training Labels: 13,440 labels, each representing an Arabic character.
Testing Images: 3,360 samples, each of size 32x32 pixels, flattened into a 1024-length vector.
Testing Labels: 3,360 labels, each representing an Arabic character.
Data Preparation
Normalization: Each image is normalized.
Visualization: A function to reconstruct and display images from their flattened vectors.
Experiments and Results
1. Support Vector Machine (SVM)
Training: SVM model trained on the training data.
Testing: Confusion matrix and average F1-scores provided for the test data.
2. K-Nearest Neighbors (KNN)
Hyperparameter Tuning: Different values of K are evaluated using validation data, and average F1-scores are plotted to determine the best K.
Testing: Best K value model tested, confusion matrix, and average F1-scores provided for the test data.
3. Neural Networks (NN)
Model Architectures: Two different architectures were tested, varying in hidden layers, neurons, and activation functions.
Training: Error and accuracy curves plotted for training and validation data.
Model Selection: The best model saved and used to make predictions on new unlabeled data.
Testing: Best model tested, confusion matrix, and average F1-scores provided for the test data.
Conclusion
Model Comparison: Results of the models compared to suggest the best-performing model.
Deliverables
Code: Python files (.py).
Report: PDF containing team members' names, IDs, code, and screenshots of outputs.
The dataset can be downloaded from [this link](https://drive.google.com/file/d/1u3tnEY-eMmeUNaKP31YBCVoty9s5VCsz/view?usp=sharing).

