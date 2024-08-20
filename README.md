<body>

<h1 align="center">🔍 Breast Cancer Classification Project 🔬</h1>

<p align="center">
    <img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg" alt="Python Version">
    <img src="https://img.shields.io/badge/Framework-Scikit--Learn-yellow.svg" alt="Framework">
</p>

<p align="center">
    This project applies multiple machine learning models to classify breast cancer diagnoses using clinical data. 
    The main goal is to accurately predict whether a tumor is malignant or benign.
</p>

<h2>📂 Project Structure</h2>
<ul>
    <li><code>data.csv</code> - The dataset used for training and testing the models.</li>
    <li><code>breast_cancer_classification.ipynb</code> - The Jupyter Notebook containing the code, explanations, and visualizations.</li>
    <li><code>README.md</code> - Project documentation in Markdown format.</li>
</ul>

<h2>🛠️ Installation & Requirements</h2>
<p>To run this project locally, you'll need the following libraries:</p>
<ul>
    <li><a href="https://pandas.pydata.org/">Pandas</a></li>
    <li><a href="https://numpy.org/">NumPy</a></li>
    <li><a href="https://matplotlib.org/">Matplotlib</a></li>
    <li><a href="https://scikit-learn.org/stable/">Scikit-learn</a></li>
</ul>

<p>You can install these dependencies using pip:</p>
<pre><code>pip install pandas numpy matplotlib scikit-learn</code></pre>

<h2>📊 Dataset</h2>
<p>The dataset used in this project is the <strong>Breast Cancer Wisconsin (Diagnostic) Dataset</strong>, which includes features extracted from breast cancer cell images, such as radius, texture, perimeter, area, and smoothness. The target variable is the diagnosis, which can either be Malignant (M) or Benign (B).</p>

<p><strong>Features:</strong></p>
<ul>
    <li>Mean Radius</li>
    <li>Mean Texture</li>
    <li>Mean Perimeter</li>
    <li>Mean Area</li>
    <li>Mean Smoothness</li>
    <li>... and many more</li>
</ul>

<h2>📈 Models Used</h2>
<p>Several classification algorithms were implemented and compared using 10-fold cross-validation:</p>
<ul>
    <li><strong>Logistic Regression</strong></li>
    <li><strong>K-Nearest Neighbors (KNN)</strong></li>
    <li><strong>Support Vector Machine (SVM)</strong></li>
    <li><strong>Decision Tree</strong></li>
    <li><strong>Random Forest</strong></li>
    <li><strong>Naive Bayes</strong></li>
    <li><strong>Linear Discriminant Analysis (LDA)</strong></li>
</ul>

<h2>⚙️ Model Evaluation</h2>
<p>To ensure the robustness of the models, 10-fold cross-validation was employed. The results were visualized using a bar chart to compare the average accuracy of each model.</p>
<pre><code>
LDA: 95.6%
Logistic Regression: 97.8%
K-Nearest Neighbors: 96.4%
Support Vector Machine: 97.5%
Decision Tree: 92.1%
Random Forest: 96.26%
Naive Bayes: 94.9%
</code></pre>

<h2>🏆 Final Model Performance</h2>
<p>The <strong>Support Vector Machine (SVM)</strong> was selected as the final model due to its outstanding performance. It achieved an accuracy of <strong>98.25%</strong> on the test set.</p>

<h2>📊 Visualizations</h2>
<p>The project includes visualizations such as:</p>
<ul>
    <li>Bar chart comparing model accuracies.</li>
    
<h2>🔗 References</h2>
<ul>
    <li><a href="https://scikit-learn.org/stable/">Scikit-learn Documentation</a></li>
    <li><a href="https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)">Dataset Source</a></li>
</ul>

<h2>🤝 Contributing</h2>
<p>Contributions, issues, and feature requests are welcome! Feel free to check the <a href="https://github.com/hellopavi/breast_cancer_classification/issues">issues page</a> if you want to contribute.</p>

<p>Don't forget to give a ⭐️ if you like this project!</p>

</body>
</html>
