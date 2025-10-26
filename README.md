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
Copy
Edit
!pip install qiskit==0.43.0
!pip install qiskit-machine-learning==0.5.0
!pip install imbalanced-learn
Upload the anemia.csv file
Run each cell step-by-step
""I built this as part of a hackathon to explore how quantum computing can create real impact, especially in health prediction systems for underserved regions. It’s a small step, but one that blends technology with purpose.""
personal detials{Naveed Ahamed
B.Tech AI & Data Science (3rd year)
GitHub: navvwd
Email: naveed24ahm.1@gmail.com}
Assalamu Alaikum.
