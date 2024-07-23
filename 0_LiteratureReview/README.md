# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: SIMBox Bypass Frauds in Cellular Networks: Strategies, Evolution, Detection, and Future Directions

  - **[Link](https://ieeexplore.ieee.org/document/9501030)**
  - **Objective**: Simbox traffic bypass fraud detection
  - **Methods**: Rule Based system to detect fraud and by generating test calls using TCG to suspected numbers
  - **Outcomes**: Able to detect conventional simbox pattern but due to changing fraud strategies there are more chances to bypass this system
  - **Relation to the Project**: Trying to solve the same problem

- **Source 2**: Telecom Fraud Detection with Machine Learning on Imbalanced Dataset

  - **[Link](https://ieeexplore.ieee.org/document/9911518)**
  - **Objective**: Overall telecom fraud detection including simbox
  - **Methods**: Synthetic data generation using SMOTE and using supervised machine learning algorithms (Logistic Regression, Random Forest, AdaBoost.M1, Naïve Bayes) to detect fraud
  - **Outcomes**: 

    | Performance Parameters | Classifier | J48 | RF | NB | AB.M1 | LR |
    |---|---|---|---|---|---|---|
    | Accuracy |  | 97.1 | 97.2 | 60.51 | 79.95 | 74.98 |
    | Precision |  | 0.992 | 0.99 | 0.563 | 0.96 | 0.71 |
    | Recall |  | 0.951 | 0.951 | 0.938 | 0.625 | 0.82 |
    | F1-score |  | 0.971 | 0.971 | 0.704 | 0.757 | 0.76 |
    | MCC |  | 0.944 | 0.944 | 0.282 | 0.639 | 0.49 |
    | AUC |  | 0.992 | 0.992 | 0.681 | 0.899 | 0.75 |
    | Time to build the model |  | 31.68 | 244 | 11.57 | 46.39 | 24.5 |

    ***Note:** Above results are on synthetic data, in real data results are not same* 


  - **Relation to the Project**: Trying to solve the same problem

- **Source 3**: LSTM-based generation of cellular network traffic

  - **[Link](https://ieeexplore.ieee.org/document/10119094)**
  - **Objective**: Synthetic cellular data generation
  - **Methods**: LSTM
  - **Outcomes**: Generates Generalized CDR level data
  - **Relation to the Project**: As simbox fraud data is highly imbalance, generating synthetic data can help to train better model.
