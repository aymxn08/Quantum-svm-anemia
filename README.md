Quantum SVM for Anemia Prediction
This project uses a Quantum Support Vector Machine (QSVM) to predict anemia based on blood test data. It was built with the goal of combining quantum computing and machine learning to tackle real-world health problems in a unique way.
Anemia is a common condition, and early detection is important. In this project, I used just two features from a blood test — Hemoglobin and MCHC — to predict whether someone is anemic. It’s a minimal but effective dataset.
"
The twist? Instead of only using classical models, I used Qiskit to apply a quantum kernel with a Support Vector Machine — something that pushes beyond traditional ML.
"
Technologies Used:
Python
Qiskit (Quantum kernel, Aer simulator)
Scikit-learn (for data preprocessing and classical SVM)
Imbalanced-learn (SMOTE for handling class imbalance)
Pandas, NumPy
Accuracy:
Quantum SVM Accuracy: ~93.7%
Classical SVM Accuracy: ~75%
The quantum approach showed a significant improvement after optimizing feature maps and balancing the dataset.
Open the notebook in Google Colab or Jupyter
Install dependencies:
python

