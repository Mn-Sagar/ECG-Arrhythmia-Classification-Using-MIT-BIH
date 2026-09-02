# ECG-Arrhythmia-Classification-Using-MIT-BIH
This project applies machine learning and deep learning to ECG heartbeat classification using the MIT-BIH Arrhythmia Database. The work focuses on preparing ECG signals, mapping heartbeat labels into five AAMI classes, training several classifiers, and comparing their performance.
Objective
To gain practical experience with biomedical signal data and build a reliable baseline for automatic arrhythmia
classification.
Dataset
MIT-BIH Arrhythmia Database. The notebook segments 109,437 heartbeats into five AAMI groups: N, S, V, F, and Q.
Methods
• ECG signal normalization and heartbeat segmentation
• AAMI five-class label mapping
• Logistic Regression
• Random Forest
• XGBoost
• 1D CNN
• Classification reports, confusion matrices and ROC-based evaluation
Main Results
The notebook shows strong performance from tree-based models. Random Forest reaches about 98.2% accuracy in
the recorded runs. Performance is strongest for the common N and Q classes, while the smaller F and S classes remain
more difficult.
Research Value
The project demonstrates hands-on work with real ECG signals, multiclass healthcare classification, model comparison,
and evaluation under class imbalance.
Limitations
The classes are highly imbalanced. The current notebook uses a beat-level train/test split, so the results should be
presented as a technical portfolio result rather than a claim of clinical validation.
Next Step
A natural next step is patient-independent validation and a separate explainability study.
