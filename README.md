# Hi, I'm Rajesh 👋

### Computer Science & Technology Undergraduate | Machine Learning, Deep Learning & Computer Vision

I'm a Computer Science and Technology undergraduate at Hefei University, China, interested in **machine learning, deep learning, computer vision, and model evaluation**.

I build hands-on projects with Python and machine-learning frameworks, focusing on understanding model behaviour, comparing approaches, and documenting results. I'm currently developing my PyTorch skills through CNN experiments and multi-seed evaluation studies.

I'm preparing for future **MSc research opportunities in Machine Learning, Artificial Intelligence, and Computer Vision**.

---

## 👨‍💻 About Me

- 🎓 B.Sc. Computer Science and Technology undergraduate at Hefei University
- 🧠 Interested in Machine Learning, Deep Learning, and Computer Vision
- 🔬 Exploring CNN architectures, model behaviour, and systematic evaluation
- 🔥 Currently developing practical experience with PyTorch
- 📊 Interested in data analysis, experimental comparison, and reproducible workflows
- 💻 Experience with Python, Java, JavaScript, SQL, HTML, and CSS
- 🌏 Preparing for international postgraduate study and research opportunities

---

## 🛠️ Technical Skills

### Programming
`Python` `Java` `JavaScript` `SQL` `HTML` `CSS`

### Machine Learning & Data Science
`Scikit-learn` `Pandas` `NumPy` `SciPy` `Matplotlib` `Seaborn`

- Data preprocessing and feature engineering
- Classification and regression
- Clustering and unsupervised learning
- Cross-validation and hyperparameter tuning
- Model comparison and evaluation
- Feature importance and data visualization
- Serving a trained model through a web app

### Deep Learning
`PyTorch` `Convolutional Neural Networks (CNNs)` `Neural Networks`

- Neural network fundamentals
- CNN architecture implementation and comparison
- Training and validation workflows
- Loss and accuracy analysis
- Multi-seed experimental evaluation

### NLP & Recommendation Systems

- Text preprocessing and TF-IDF
- Cosine similarity
- Text classification
- Content-based recommendation
- Skill extraction and hybrid scoring

### Tools
`Git` `GitHub` `Flask` `VS Code` `Jupyter Notebook` `TensorBoard` `MySQL`

---

## 🔬 Featured Deep Learning Projects

### 1. FashionMNIST CNN Depth & Width Study

**PyTorch · Deep Learning · Computer Vision · Experimental Evaluation**

A multi-seed experimental study comparing CNN architectures on FashionMNIST. The project looks at how network depth and width relate to classification performance, using repeated runs instead of a single training result.

**Experimental setup**
- Compared CNN5, CNN5Wide, and CNN7 architectures
- Ran each architecture with five random seeds (15 runs per experiment stage)
- Selected checkpoints by minimum validation loss
- Used a fixed data-split seed for consistency
- Recorded accuracy, loss, and variation across runs
- Created plots and structured result files for analysis

**Colab validation results (exploratory, n = 5 paired runs)**

| Architecture | Mean validation accuracy |
|---|---:|
| CNN5 | 93.29% ± 0.16% |
| CNN7 | 92.55% ± 0.33% |

A paired t-test between CNN5 and CNN7 gave p = 0.0143.

**Separate CPU test-set results**

| Architecture | Mean accuracy | Standard deviation |
|---|---:|---:|
| CNN5 | 92.48% | 0.30 percentage points |
| CNN5Wide | 92.37% | 0.20 percentage points |
| CNN7 | 92.07% | 0.20 percentage points |

Adding depth did not improve performance in this setup. The gaps on the test set are small, and the statistical test uses only five paired runs on one dataset, so I treat the result as exploratory. The point of the project is the comparison method and reporting variation across runs, not a single accuracy number.

**Technologies:** Python, PyTorch, SciPy, FashionMNIST, CNNs, NumPy, Pandas, Matplotlib

🔗 [View Project](https://github.com/Rajesh-code11/fashionmnist-cnn-depth-study)

---

### 2. FashionMNIST CNN with PyTorch

**PyTorch · CNN · Image Classification**

An image-classification project implementing and comparing CNN architectures for the FashionMNIST dataset. The workflow covers data preparation, model training, evaluation, and visualization.

**Topics:** PyTorch, CNNs, Image Classification, Training Curves, Loss Analysis

🔗 [View Project](https://github.com/Rajesh-code11/fashionmnist-cnn-pytorch)

---

## 📚 Machine Learning & NLP Projects

### 3. AI Job Skill Gap Analyzer

**NLP · Skill Matching · Recommendation**

An NLP-powered system that compares technical skills with job requirements, identifies missing skills, estimates job compatibility, ranks job matches, and generates learning priorities.

**Topics:** Skill Extraction, TF-IDF, Cosine Similarity, NLP, Hybrid Scoring

🔗 [View Project](https://github.com/Rajesh-code11/job-skill-gap-analyzer)

---

### 4. Handwritten Digit Recognition

**Neural Networks · Image Classification**

A handwritten-digit classification project that compares Logistic Regression (97.22% test accuracy) with a multilayer perceptron (MLP) tuned with GridSearchCV (24 configurations, 5-fold cross-validation). The tuned MLP reached 98.33% test accuracy (354/360). Error analysis showed digit 8 was the hardest class, with 91% recall.

**Topics:** Neural Networks, MLP, GridSearchCV, Classification, Error Analysis

🔗 [View Project](https://github.com/Rajesh-code11/handwritten-digit-recognition)

---

### 5. Customer Churn Prediction

**Supervised Learning · Classification**

A machine-learning project that predicts whether customers are likely to leave a service. It compares five classifiers on 7,043 telecom customer records, using pipelines, 5-fold cross-validation, and a held-out test set. Logistic Regression performed best (ROC-AUC 0.842, F1-score 0.607), and hyperparameter tuning did not improve test performance.

**Topics:** Classification, Data Preprocessing, Model Comparison, F1 Score, ROC-AUC

🔗 [View Project](https://github.com/Rajesh-code11/customer-churn-prediction)

---

### 6. House Price Prediction Web App

**Regression · Model Deployment · Flask**

A regression project that predicts house prices from the California Housing dataset (20,640 samples). It compares Linear Regression, Random Forest, and Gradient Boosting, then tunes the Random Forest with GridSearchCV (R² = 0.806, RMSE = 0.504). The final model is served through a Flask web app with input validation.

**Topics:** Regression, Random Forest, Gradient Boosting, GridSearchCV, Flask, Input Validation

🔗 [View Project](https://github.com/Rajesh-code11/house-price-prediction-app)

---

### 7. Movie Recommendation System

**NLP · Recommendation Systems**

A content-based recommendation system that uses movie information and text similarity to recommend similar movies.

**Topics:** TF-IDF, Cosine Similarity, Text Processing, Recommendation Systems

🔗 [View Project](https://github.com/Rajesh-code11/movie-recommendation-system)

---

### 8. Customer Segmentation

**Unsupervised Machine Learning**

A project that groups customers based on their characteristics and behaviour to explore customer segments.

**Topics:** Clustering, Unsupervised Learning, Data Analysis, Visualization

🔗 [View Project](https://github.com/Rajesh-code11/customer-segmentation)

---

### 9. Spam Email Detection

**NLP · Text Classification**

A natural language processing project that classifies messages as spam or non-spam on the SMS Spam Collection dataset. It compares SVM, Logistic Regression, and Naive Bayes with TF-IDF features. SVM performed best at 98.12% test accuracy.

**Topics:** NLP, TF-IDF, Text Classification, Model Evaluation

🔗 [View Project](https://github.com/Rajesh-code11/spam-email-detection)

---

### 10. Iris Classification

**Machine Learning · Model Comparison**

A classification project using the Iris dataset to compare machine-learning algorithms and evaluate their performance.

**Topics:** Classification, Cross-Validation, Model Comparison, Feature Importance

🔗 [View Project](https://github.com/Rajesh-code11/iris-classification)

---

### 11. Titanic Survival Prediction

**Machine Learning · Classification**

An end-to-end machine-learning project predicting passenger survival using preprocessing, cross-validation, and model tuning.

**Topics:** Data Preprocessing, Random Forest, SVM, K-Fold Cross-Validation, Hyperparameter Tuning

🔗 [View Project](https://github.com/Rajesh-code11/titanic-survival-prediction)

---

## 📈 My Learning Approach

> Learn the concept → Build an experiment → Evaluate the results → Investigate the behaviour → Document the findings.

I aim to move beyond simply training a model. My projects increasingly emphasize structured workflows, comparison between approaches, clear evaluation metrics, and documentation of results and limitations.

---

## 🎯 Current Research Interests

- Computer Vision and Image Classification
- Deep Learning and CNN Architectures
- Neural Network Behaviour
- Experimental Design and Model Evaluation
- Reproducible Machine-Learning Experiments

I'm continuing to strengthen my theoretical foundations and practical skills as I prepare for postgraduate study and future research opportunities.

---

## 📫 Connect With Me

- GitHub: [Rajesh-code11](https://github.com/Rajesh-code11)
- Email: [alerajesh76@gmail.com](mailto:alerajesh76@gmail.com)

---

⭐ Thanks for visiting my profile!

I'm continuously learning, experimenting, and building projects to deepen my understanding of machine learning and artificial intelligence.
