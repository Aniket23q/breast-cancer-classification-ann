Project Overview
In this project, I’ve built an Artificial Neural Network (ANN) to help classify breast cancer tumors as either benign (B) or malignant (M) using patient diagnostic data.
The main goal is to support early detection because catching cancer early can make a big difference in treatment and survival rates.

⚙️ Requirements
Before you run the project, make sure you have these Python libraries installed:

pandas

numpy

scikit-learn

matplotlib

seaborn

You can quickly install them using this command:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib seaborn
📊 Dataset
The project uses the Breast Cancer Wisconsin (Diagnostic) Dataset.
This dataset contains features collected from digitized images of breast mass cell samples, focusing on key measurements to detect tumors.


✨ Feature Overview
Here are some of the important features used to train the model:

ID: Unique ID for each patient sample

Diagnosis: Malignant (M) or Benign (B)

Radius, Texture, Perimeter, Area: Measurements that describe the size and shape of the tumor

Smoothness, Compactness, Concavity: Surface and contour characteristics

Symmetry, Fractal Dimension: Indicators of tumor structure and shape irregularities

🗂️ Project Structure
text
Copy
Edit
breast-cancer-classification-ann/
│
├── breast_cancer_ann.ipynb   # Main Jupyter Notebook
├── breast_cancer_data.csv    # Dataset file
├── README.md                 # Project documentation
└── requirements.txt          # (Optional) List of libraries
📈 What’s Inside
Data cleaning and preprocessing

Feature scaling

Splitting data into train/test sets

Building an ANN model using Scikit-learn

Model evaluation (accuracy, precision, recall, F1 score)

Visualizations to understand model performance
