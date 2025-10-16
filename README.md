# CV-Skin-Cancer-Detection
High-performance machine learning pipeline (EfficientNet-B5 with SimAM attention) for automated skin cancer detection using smartphone-quality images, paired with a study on clinical adoption readiness in the Russian healthcare system.

# A Study on the Application and Effectiveness of Machine Learning Methods for Skin Cancer Detection 

This repository contains the code, data analysis, and supplementary materials for the Bachelor's Thesis, “A Study on the Application and Effectiveness of Machine Learning Methods for Skin Cancer Detection”.

The research addresses the critical challenge of translating high-performing AI models into viable clinical tools by combining a quantitative model building pipeline with qualitative implementation research. The primary focus is on developing a robust solution for teledermatology using images of a quality similar to those taken with a smartphone.

Key Features & Methodology

AI Architecture: The final classification model is EfficientNet-B5 enhanced with the SimAM attention module.


Dataset: The model was trained on the SLICE-3D dataset which simulates real-world teledermatology scenarios using non-dermatoscopic, smartphone-quality images.


Performance Optimization: Systematic experimentation was conducted across loss functions, data augmentation approaches, CNN backbones, and attention modules.


Explainable AI (XAI): Model predictions are interpreted using multiple saliency-map techniques, including Grad-CAM, XGradCAM, ScoreCAM, and AblationCAM, to improve clinician trust and interpretability.


Implementation Readiness: Qualitative research used the TEHAI framework (Translational Evaluation of Healthcare AI) and semi-structured interviews with Russian clinicians to probe real-world feasibility and barriers.

Key Findings
Technical Performance (Quantitative)
The final model—EfficientNet-B5 with SimAM attention—demonstrated high performance suitable for a screening tool:


Partial AUC: 0.1841 at minimum True Positive Rate (TPR) > 0.8.

The model’s performance on smartphone-quality images was found to be superior to that of the clinicians based solely on the images, justifying its use as a screening tool in teledermatology.

Implementation Feasibility (Qualitative)
The thematic analysis of clinician interviews revealed a critical translational gap:


Value: Clinicians highly value the diagnostic utility of AI for screening.


Barriers: Significant barriers to adoption include regulatory ambiguity, a lack of AI education for specialists, and the absence of patient context/anamnesis in AI predictions.


Trust: XAI tools moderately improved trust, particularly when saliency maps aligned with clinical reasoning.
