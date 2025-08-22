# Silabus Pelatihan AI Pertamina EP Cepu

## Materi 1: Warming up - Dasar-dasar Data Science
- Sistem AI Berbasis Data
- CRISP-DM (Cross-Industry Standard Process for Data Mining)
- Tipe Data
- Exploratory Data Analysis

## Materi 2: Dasar-dasar AI dan Machine Learning
- Overview AI dan ML
- Unsupervised
    - Clustering
- Supervised
    - Klasifikasi
    - Regresi

## Materi 3: Clustering
- Pengenalan Algoritma: K-Means dan DBScan
- Implementasi
- Evaluasi

### Referensi Workflow KNIME
| Workflow Name                                         | Method / Algorithm                | Link                                                                 |
|-------------------------------------------------------|-----------------------------------|----------------------------------------------------------------------|
| Performing a k-Means clustering                       | KMeans                            | [KNIME Hub](https://hub.knime.com/s/QqKlIQmDnCAg0lEQ)                |
| Analyze Data by Training a k-Means Clustering on Location Data | KMeans                            | [KNIME Hub](https://hub.knime.com/s/gZluj12KJvYshWKz)                |
| Training Clustering Algorithms (All in One)           | KMeans, Hierarchical, DBScan      | [YouTube](https://youtu.be/i47dBwK8KfQ?si=gyD6eG3DfjCD4Vs_) / [KNIME Hub](https://hub.knime.com/s/i2KZgrjZFBTOW5dY) |
| KNIME for Finance - DBScan Fraud Detection            | DBScan                            | [KNIME Hub](https://hub.knime.com/s/qkkQyf-9fTLWV_1G)                |
| 03_DBSCAN                                             | DBScan                            | [KNIME Hub](https://hub.knime.com/s/WgQVjVJugr9Nu24W)                |
| 01_HierarchicalClustering                             | Hierarchical                      | [KNIME Hub](https://hub.knime.com/s/rlXFxYxQmbgNgSsM)                |

## Materi 4: Klasifikasi
- Pengenalan Algoritma: Decision Tree, Random Forest, SVC, Logistic Regression
- Implementasi
- Evaluasi
- Feature Importance

### Referensi Workflow KNIME
| Workflow Name                                                     | Method / Algorithm              | Link                                                                 |
|-------------------------------------------------------------------|---------------------------------|----------------------------------------------------------------------|
| 03_LogisticRegression                                             | Logistic Regression             | [KNIME Hub](https://hub.knime.com/s/LWHdcrt_DFIepk0p)                |
| SVM_Solution                                                      | Support Vector Machine (SVM)    | [KNIME Hub](https://hub.knime.com/s/rnzxfDElze4t7RRd/most-recent)    |
| 01_Evaluating_Classification_Model_Performance                    | Decision Tree                   | [KNIME Hub](https://hub.knime.com/s/wWrebA_HNv4hHDDG/most-recent)    |
| Analyze Data by Training a Decision Tree Classifier for Churn Prediction | Decision Tree                   | [KNIME Hub](https://hub.knime.com/s/tqVpSXd1crC_Fes6/most-recent)    |
| Decision_Tree_Solution                                            | Decision Tree                   | [KNIME Hub](https://hub.knime.com/s/rH4ZHDIPVfpyJ7Y3/most-recent)    |
| Ensemble_Solution                                                 | Ensemble (Boosting/Bagging)     | [KNIME Hub](https://hub.knime.com/s/w2zdQ-7LW_suhNsi/most-recent)    |
| Fraud Detection: Model Training                                   | Ensemble (Boosting/Bagging)     | [KNIME Hub](https://hub.knime.com/s/gwBpbUtj0awOERjg/most-recent)    |
| Train Python Scikit-learn (sklearn) models in KNIME               | External (scikit-learn)         | [KNIME Hub](https://hub.knime.com/s/XODrB8IVRDJAhXAt/most-recent)    |
| AutoML Regression and Classification Examples                     | External (AutoML)               | [KNIME Hub](https://hub.knime.com/s/ifIPg5Pr0hCk62GS/most-recent)    |

## Materi 5: Regresi
- Pengenalan Algoritma: Linear Reg., Support Vector Reg., Random Forest Reg., Gradient Boosting Reg.
- Implementasi
- Evaluasi
- Feature Importance
- Transformasi: Tanpa Normalisasi, Standard Scaling, Min-Max Scaling

### Referensi Workflow KNIME
| Workflow Name                                                     | Method / Algorithm              | Link                                                                 |
|-------------------------------------------------------------------|---------------------------------|----------------------------------------------------------------------|
| Analyze Data by Training a Linear Regression model for House Price Prediction | Linear Regression              | [KNIME Hub](https://hub.knime.com/s/L0B6FOtL36a9ItSK)                |
| Linear_Regression_Solution                                        | Linear Regression              | [KNIME Hub](https://hub.knime.com/s/4IWU7jTAqK-6mUA6)                |
| 04_Evaluating_Regression_Model_Performance                        | Linear Regression              | [KNIME Hub](https://hub.knime.com/s/ijM45fGpZId_JJd3)                |
| Support Vector Regression with Weka                               | Support Vector Regression (SVR)| [KNIME Hub](https://hub.knime.com/s/2dfxtGFcu4iuHhv_/most-recent)    |
| 9. Random Forest Regression                                       | Random Forest Regression       | [KNIME Hub](https://hub.knime.com/s/6dkpKR7RShJyNV9d)                |
| Gradient Boosting Regression                                      | Gradient Boosting Regression   | [KNIME Hub](https://hub.knime.com/s/FrCbsQc9sYXNFsFT)                |

## Materi 6: Overview Deep Learning
- [Arsitektur Dasar Neural Network](https://playground.tensorflow.org)
- Implementasi berbasis citra ([YOLO](https://colab.research.google.com/drive/1F5aJXRLt9nZHFem_rIYz6TSMqPdQQh1x?usp=sharing) dan [Roboflow](https://universe.roboflow.com/computer-vision-8kpih/synapsis-ppe/dataset/513))
- Referensi untuk pembelajaran lanjutan

## Materi 7: Basic Forecasting
- Pengenalan Algoritma: AutoARIMA, [Tree-Based Regressor](http://www.saedsayad.com/decision_tree_reg.htm)
- Penggunan pipeline library untuk forecasting: Pycarets Regression
- Perbandingan model statistik, machine learning berdasarkan studi kasus
- Hubungan regresi dengan forecasting

### Referensi Workflow KNIME
| Workflow Name                                  | Method / Algorithm                   | Link                                                                 |
|------------------------------------------------|--------------------------------------|----------------------------------------------------------------------|
| Accessing, Transforming and Modeling Time Series | ARIMA                                | [KNIME Hub](https://hub.knime.com/s/HahI9s4ecV71ILKT) / [Blog](https://www.knime.com/blog/building-a-time-series-analysis-application) |
| ARIMA - Simple Time Series Forecasting         | ARIMA                                | [KNIME Hub](https://hub.knime.com/s/y2O5e2XzYL5yOzuf/most-recent)    |
| 04_Model_Comparison                            | ARIMA, Random Forest, Linear Regression, Seasonal Naive, Moving Average, SARIMA, LSTM | [KNIME Hub](https://hub.knime.com/s/nKtuhSdxZhStS-0E)                |

## Materi 8: Advanced Forecasting
- Studi Kasus
- Recursive Multi-Step Forecasting
- Zero-shot forecasting: Amazon Chronos
- Ensemble Learning via PyCarets

### Referensi Workflow KNIME
| Workflow Name                                  | Method / Algorithm                   | Link                                                                 |
|------------------------------------------------|--------------------------------------|----------------------------------------------------------------------|
| Time Series Prediction                         | Linear Regression (AR)                | [KNIME Hub](https://hub.knime.com/s/kyzNLnmNn0WWLeaY/most-recent)    |
| Energy Demand Prediction                       | LSTM                                  | [KNIME Hub](https://hub.knime.com/s/7rJt-XwC7NhVsx0o/most-recent)    |
| Simple auto-regressive model to predict a time series | Linear AR, Polynomial AR             | [KNIME Hub](https://hub.knime.com/s/9SsXq6DBqEsW8q-5/most-recent)    |

## Materi 9: Overview Generative AI
- Overview Generative AI
- Demonstrasi: Stable Diffusion

## Materi 10: Praktik LLM untuk Use Case Specific
- Overview Large Language Models (LLM): Ollama, LangChain
- Panduan Setup dan Instalasi
- Menambah pengetahuan LLM dari dokumen: Retrieval-Augmented Generation (RAG)

### Referensi Workflow KNIME
| Workflow Name                                              | LLM Task   | Link                                                                 |
|------------------------------------------------------------|------------|----------------------------------------------------------------------|
| Research Paper Summaries Generation using Generative AI    | Summary    | [KNIME Hub](https://hub.knime.com/s/rwRKSUITKpjRoTgr/most-recent)    |
| 2.5 - Retrieval Augmented Generation ChatApp               | RAG        | [KNIME Hub](https://hub.knime.com/s/nBhjtxPFqFxnqGst/most-recent)    |
| 02 Retrieval-Augmented Generation (RAG)                    | RAG        | [KNIME Hub](https://hub.knime.com/s/bjL92F4Sk2IMXNJi)                |
| Evaluate a RAG system                                      | RAG        | [KNIME Hub](https://hub.knime.com/s/1nGSF64K7js9NSDm/most-recent)    |
| Parsing Raw Data with LLMs                                 | Parse Data | [KNIME Hub](https://hub.knime.com/s/DYIrs5bTV6VjSsRU/most-recent)    |

## Wrap-up
- Deployment di HuggingFace
- Review materi keseluruhan
- Diskusi case study