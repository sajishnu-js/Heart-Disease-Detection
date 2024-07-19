# Heart-Disease-Detection

Cardiovascular disease is the foremost cause of the death, in which it affects millions of deaths worldwide. Early detection of the disease plays a crucial role in improving the patient outcomes. In recent time, Artificial intelligence demonstrates promising outcomes in medical diagnostics.

This study aims to improve the accuracy of the diagnosis of heart disease by utilizing algorithms specifically XGBoost, Long Short-Term Memory (LSTM) and Transformer and combination of XGBoost and LSTM.

The system receives input in the form of EEG signal from comatose patients along with patients details such as CPC, Age and Sex. Every model is trained using an extensive database from unknown patients. The Hybrid model that combines the advantages of both algorithms such as XGBoost and LSTM achieved an impressive accuracy rate of 90%, which shows the potential of ensemble learning. We introduced a novel hybrid model which effectively combines the advantages of LSTM and XGBoost, utilizing the strength of structured and sequential data. This contribution is especially useful in situations when early detection and timely treatment are necessary for enhancing patient outcomes. By developing a robust model which achieves higher classification accuracy, we can predict the patient outcomes and can give timely treatments.

Evaluation metrics for models:

XGBoost: 75% accuracy. Class 0 - Precision: 66%, Recall: 55%, F1: 60%. Class 1 - Precision: 78%, Recall: 85%, F1: 81%. Macro F1: 71%, Weighted F1: 74%.

LSTM: 72% accuracy. Class 0 - Precision: 50%, Recall: 18%, F1: 26%. Class 1 - Precision: 75%, Recall: 93%, F1: 83%. Macro F1: 54%, Weighted F1: 67%.

Transformer: 55% accuracy. Class 0 - Precision: 34%, Recall: 33%, F1: 34%. Class 1 - Precision: 65%, Recall: 66%, F1: 66%. Macro F1: 50%, Weighted F1: 55%.

Combined (XGBoost & LSTM): 90% accuracy. Class 0 - Precision: 91%, Recall: 84%, F1: 87%. Class 1 - Precision: 89%, Recall: 94%, F1: 92%. Macro F1: 90%, Weighted F1: 90%.

This project demonstrates the potential of AI in heart disease detection, achieving a 90% accuracy with a combined XGBoost and LSTM model. This innovative approach highlights AI's ability to enhance early diagnosis and improve patient outcomes in the medical field.
