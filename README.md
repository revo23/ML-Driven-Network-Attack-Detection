# ML-Driven Network Attack Detection

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/7dd454db-a10e-4997-8621-c809b8416c54" />



**Overview**

In this project, tree-based machine learning models were selected because intrusion detection datasets contain non-linear interactions, mixed numerical features, and complex class boundaries that are effectively captured by ensemble tree methods. Models such as XGBoost, LightGBM, Random Forest, and K-Nearest Neighbors have repeatedly demonstrated strong performance on tabular NetFlow data, especially when dealing with imbalanced or noisy traffic patterns. AutoGluon was chosen as the training framework because it automates model selection, hyperparameter tuning, bagging, and ensembling, allowing multiple high-performing models to be trained efficiently and consistently. This ensures that the final comparison reflects not only raw model performance but also optimized training configurations. Overall, the selected models provide a strong combination of interpretability, robustness, and predictive capability for network intrusion detection.

part of 'CYBERSEC520:Applying ML to Advance Cybersecurity' course which provides a comprehensive exploration of artificial intelligence (AI) and machine learning (ML) in cybersecurity operations. Students will learn to implement and evaluate AI/ML models for various cybersecurity applications.


**Steps**  
Using AutoGluon (Tree-Based Models: XGBoost, LightGBM, Random Forest, KNN)  
This notebook demonstrates an end-to-end machine learning workflow for network intrusion detection using two real-world NetFlow datasets.  

1. Data collection and preprocessing
2. Feature selection and dataset preparation
3. Model training using AutoGluon : Tree-based models including XGBoost, LightGBM, Random Forest, KNN
4. Evaluation on primary and secondary datasets
5. Performance comparison and visualization
6. Interactive prediction interface (Gradio)

**Performence Metrics**
1. Accuracy Score
2. F1 score
3. Confusion Matrix > we want more TP(top left) and TN(bottom right)

<img width="1584" height="891" alt="image" src="https://github.com/user-attachments/assets/b97d4fa3-7e4b-493e-88f3-4e30cf22a2f8" />
<img width="515" height="455" alt="image" src="https://github.com/user-attachments/assets/8a66e73e-1670-477b-bb8a-2d13d0aef89d" />
