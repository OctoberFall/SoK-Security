# SoK-Security
Repository for Euro S&amp;P submission "SoK: Modeling Explainability in Security Monitoring for Trust, Privacy, and Interpretability". The repository consists of four notebooks to produce results shown in the paper. You can open each notebook in Google colab and execute each cell. All the required files have been provided as zipped folder in Google drive link. You can either download all the files and notebook in your machine and run locally, or simply run each cell in the Colab following instructions in the notebook.

- PDF_malware_classifier.ipynb: This notebbok builds a multi-layer perceptron classifier to classify PDF samples into benign and malicious. PDF_explanations.ipynb explains the decision of this black box PDF classifier for test PDF samples.
- PDF_explanations.ipynb: This notebook generates explanations for pdf file using three popular explanation strategies: LIME, LEMNA and SHAP.
- deepaid.ipynb: This notebook uses DeepAid for interpreting deep neural network decision on security log.
- lime_log.ipynb: This notebook uses LIME for interpreting deep neural network decision on security log.

