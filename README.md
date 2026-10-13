# Hi, I'm Rajesh 👋

### Computer Science & Technology Undergraduate | Machine Learning, Deep Learning & Computer Vision

I'm a Computer Science and Technology undergraduate at **Hefei University, China**, interested in machine learning, deep learning, computer vision, and systematic model evaluation.

I build hands-on projects with Python and machine-learning frameworks, focusing on understanding model behaviour, comparing approaches, and documenting experimental results.

🎓 Preparing for MSc opportunities in **Machine Learning, Artificial Intelligence, and Computer Vision**.

---

## 👨‍💻 About Me

- 🎓 B.Sc. Computer Science and Technology undergraduate at Hefei University
- 🧠 Interested in machine learning, deep learning, and computer vision
- 🔬 Exploring CNN architectures, neural network behaviour, and experimental evaluation
- 🔥 Developing practical experience with PyTorch
- 📊 Interested in model comparison, reproducibility, and data analysis
- 💻 Working with Python, Java, JavaScript, SQL, HTML, and CSS
- 🌏 Preparing for postgraduate study and future research opportunities

---

## 🛠️ Technical Skills

**Programming**

`Python` `Java` `JavaScript` `SQL` `HTML` `CSS`

**Machine Learning & Data Science**

`Scikit-learn` `Pandas` `NumPy` `SciPy` `Matplotlib` `Seaborn`

- Data preprocessing and feature engineering
- Classification, regression, and clustering
- Cross-validation and hyperparameter tuning
- Model comparison and performance evaluation
- Feature importance and data visualization
- Model deployment with Flask

**Deep Learning**

`PyTorch` `CNNs` `Neural Networks` `TensorBoard`

- Neural network fundamentals
- CNN implementation and architecture comparison
- Training workflows and loss analysis
- Validation-based checkpoint selection
- Multi-seed experimental evaluation

**NLP & Recommendation Systems**

- Text preprocessing and TF-IDF
- Cosine similarity and text classification
- Content-based recommendation
- Skill extraction and hybrid scoring

**Tools & Platforms**

`Git` `GitHub` `Flask` `VS Code` `Jupyter Notebook` `TensorBoard` `MySQL`

---

## 🔬 Featured Deep Learning Projects

### 1. FashionMNIST CNN Depth & Width Study

**PyTorch · Deep Learning · Computer Vision · Experimental Evaluation**

A multi-seed experimental study comparing CNN architectures on FashionMNIST. The goal is to investigate how network depth and width relate to classification performance using repeated runs and systematic evaluation.

**Experimental setup**
- Compared CNN5, CNN5Wide, and CNN7
- Evaluated three architectures across five random seeds (15 runs)
- Selected checkpoints using validation loss
- Used matched seeds to support paired comparisons
- Recorded accuracy, loss, and variation across runs
- Generated plots and structured result files for analysis

**Colab validation results — five runs per architecture**

| Architecture | Mean validation accuracy |
|---|---:|
| CNN5 | 93.29% ± 0.16 percentage points |
| CNN5Wide | 93.19% ± 0.22 percentage points |
| CNN7 | 92.55% ± 0.33 percentage points |

A paired comparison between CNN5 and CNN7 gave **p = 0.0143**.

**Separate CPU test-set results**

| Architecture | Mean test accuracy | Standard deviation |
|---|---:|---:|
| CNN5 | 92.48% | 0.30 percentage points |
| CNN5Wide | 92.37% | 0.20 percentage points |
| CNN7 | 92.07% | 0.20 percentage points |

In these experiments, increasing depth did not improve performance. The differences are relatively small, and five seeds on one dataset provide limited evidence for broad conclusions. I therefore treat these findings as exploratory and focus on the experimental methodology, variation across runs, and transparent reporting.

**Technologies:** Python, PyTorch, SciPy, NumPy, Pandas, Matplotlib, FashionMNIST

🔗 [View Project](https://github.com/Rajesh-code11/fashionmnist-cnn-depth-study)

---

### 2. FashionMNIST CNN with PyTorch

**PyTorch · CNN · Image Classification**

An image-classification project implementing and comparing CNN architectures on FashionMNIST. The project explores convolutional network design, model training, evaluation, and visualization.

**Topics:** PyTorch, CNNs, Image Classification, Training Curves, Loss Analysis

🔗 [View Project](https://github.com/Rajesh-code11/fashionmnist-cnn-pytorch)

---

### 3. ResNet-50 on FashionMNIST with PyTorch

**PyTorch · ResNet-50 · Deep Learning · Computer Vision**

A from-scratch implementation of ResNet-50 adapted for 28 × 28 grayscale FashionMNIST images. The model uses custom bottleneck residual blocks and random initialization rather than pretrained weights.

**Experimental setup**
- Implemented four residual stages with `[3, 4, 6, 3]` bottleneck blocks
- Adapted the input convolution and pooling layers for small grayscale images
- Trained with SGD, momentum, and weight decay
- Recorded training and test metrics using TensorBoard
- Generated accuracy and loss curves and exported epoch-level results to CSV

**Recorded results — five epochs, CPU**

| Metric | Result |
|---|---:|
| Training accuracy | 92.60% |
| Test accuracy | 91.01% |
| Total parameters | 23,522,250 |

Test accuracy increased from 84.21% in epoch 1 to 91.01% in epoch 5. This is a preliminary experiment rather than a fully tuned benchmark: training stopped after five epochs while performance was still improving, and the test set was evaluated after every epoch.

**Technologies:** Python, PyTorch, ResNet-50, FashionMNIST, TensorBoard, Matplotlib

🔗 [View Project](https://github.com/Rajesh-code11/fashionmnist-resnet50-pytorch)

---

## 📚 Machine Learning & NLP Projects

### 4. AI Job Skill Gap Analyzer

**NLP · Skill Matching · Recommendation**

An NLP-powered system that compares technical skills with job requirements, identifies missing skills, estimates job compatibility, ranks job matches, and generates learning priorities.

**Topics:** Skill Extraction, TF-IDF, Cosine Similarity, NLP, Hybrid Scoring

🔗 [View Project](https://github.com/Rajesh-code11/job-skill-gap-analyzer)

---

### 5. Handwritten Digit Recognition

**Neural Networks · Image Classification**

A handwritten-digit classification project comparing Logistic Regression with a multilayer perceptron (MLP). The tuned MLP achieved **98.33% test accuracy**, compared with 97.22% for Logistic Regression.

The MLP was tuned using GridSearchCV with 24 configurations and five-fold cross-validation. Error analysis identified digit 8 as the most challenging class, with 91% recall.

**Topics:** Neural Networks, MLP, GridSearchCV, Classification, Error Analysis

🔗 [View Project](https://github.com/Rajesh-code11/handwritten-digit-recognition)

---

### 6. Customer Churn Prediction

**Supervised Learning · Classification**

A machine-learning project that predicts whether customers are likely to leave a service. It compares five classifiers on 7,043 telecom customer records using pipelines, five-fold cross-validation, and a held-out test set.

Logistic Regression achieved a test ROC-AUC of 0.842 and an F1-score of 0.607. Hyperparameter tuning did not improve the test F1-score.

**Topics:** Classification, Data Preprocessing, Model Comparison, F1-Score, ROC-AUC

🔗 [View Project](https://github.com/Rajesh-code11/customer-churn-prediction)

---

### 7. House Price Prediction Web App

**Regression · Model Deployment · Flask**

A house-price prediction project using the California Housing dataset, containing 20,640 samples. It compares Linear Regression, Random Forest, and Gradient Boosting before tuning the Random Forest model with GridSearchCV.

The tuned model achieved an R² of 0.806 and an RMSE of 0.504. The final model is served through a Flask web application with input validation.

**Topics:** Regression, Random Forest, Gradient Boosting, GridSearchCV, Flask, Input Validation

🔗 [View Project](https://github.com/Rajesh-code11/house-price-prediction-app)

---

### 8. Movie Recommendation System

**NLP · Recommendation Systems**

A content-based recommendation system that uses movie information and text similarity to recommend similar movies.

**Topics:** TF-IDF, Cosine Similarity, Text Processing, Recommendation Systems

🔗 [View Project](https://github.com/Rajesh-code11/movie-recommendation-system)

---

### 9. Customer Segmentation

**Unsupervised Machine Learning · Data Analysis**

A machine-learning project that groups customers according to their characteristics and behaviour to explore customer segments and discover patterns in the data.

**Topics:** Clustering, Unsupervised Learning, Data Analysis, Visualization

🔗 [View Project](https://github.com/Rajesh-code11/customer-segmentation)

---

### 10. Spam Email Detection

**NLP · Text Classification**

A text-classification project using the SMS Spam Collection dataset to distinguish spam from legitimate messages. It compares SVM, Logistic Regression, and Naive Bayes using TF-IDF features.

SVM achieved **98.12% test accuracy** in the recorded experiment.

**Topics:** NLP, TF-IDF, Text Classification, Model Evaluation

🔗 [View Project](https://github.com/Rajesh-code11/spam-email-detection)

---

### 11. Iris Classification

**Machine Learning · Model Comparison**

A classification project using the Iris dataset to compare machine-learning algorithms and evaluate their performance through cross-validation.

**Topics:** Classification, Cross-Validation, Model Comparison, Feature Importance

🔗 [View Project](https://github.com/Rajesh-code11/iris-classification)

---

### 12. Titanic Survival Prediction

**Machine Learning · Classification**

An end-to-end machine-learning project predicting passenger survival using data preprocessing, cross-validation, and hyperparameter tuning.

**Topics:** Data Preprocessing, Random Forest, SVM, K-Fold Cross-Validation, Hyperparameter Tuning

🔗 [View Project](https://github.com/Rajesh-code11/titanic-survival-prediction)

---

## 📈 My Learning Approach

> Learn the concept → Build an experiment → Evaluate the results → Investigate the behaviour → Document the findings.

I aim to move beyond simply training a model. My projects increasingly emphasize structured workflows, comparisons between approaches, clear evaluation metrics, reproducibility, and honest documentation of results and limitations.

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

- **GitHub:** [Rajesh-code11](https://github.com/Rajesh-code11)
- **Email:** [alerajesh76@gmail.com](mailto:alerajesh76@gmail.com)

---

⭐ Thanks for visiting my profile!

I'm continuously learning, experimenting, and building projects to deepen my understanding of machine learning and artificial intelligence.
