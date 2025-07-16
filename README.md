# DentFuseNet: Dynamically Weighted
Interpretable Ensembles for Multi-Condition
Dental and Oral Cancer Diagnostics


Abstract
Despite the increasing application of deep learning in medical image analysis, current
systems for dental and oral diagnostics often suffer from limited generalizability, task-specific
fragmentation, and lack of interpretability factors that constrain their clinical reliability and
adoption. Existing models typically address either dental pathology or oral cancer detection in
isolation, and single-model architectures are prone to inconsistent errors and poor performance
on imbalanced datasets. To address these challenges, we propose DentFuseNet, a unified,
interpretable, and dynamically weighted ensemble framework that integrates four complementary
convolutional neural network (CNN) architectures DenseNet121, EfficientNetV2, ResNet50,
and InceptionV3. Our system simultaneously performs two tasks: (1) multi-class classification
of five prevalent dental conditions (Caries, Gingivitis, Hypodontia, Tooth Discoloration, Ulcers),
and (2) binary classification of oral lesions (Benign vs. Malignant). The ensemble employs
a validation-based weighting scheme to optimize the contribution of each model, enhancing
both robustness and predictive reliability. Extensive experiments on two publicly available
clinical datasets demonstrate that DentFuseNet achieves state-of-the-art performance: 99.68%
accuracy and a Matthews Correlation Coefficient (MCC) of 1.00 for dental condition classification,
and 98.53% accuracy with an MCC of 0.97 for oral cancer detection without any fine-tuning
longside a notably low false-negative rate of 2.4% for malignant lesions. Furthermore, the
framework integrates Grad-CAM and t-SNE visualization techniques to provide interpretable,
clinically aligned insights into model decision-making, promoting trust and transparency.
These findings confirm the effectiveness of ensemble strategies in overcoming limitations of
single-model approaches and demonstrate the feasibility of deploying unified AI systems for
multi-condition oral diagnostics. This work sets a new performance benchmark and offers
a scalable path toward clinically viable, AI-assisted screening tools. Future research will
explore external validation and integration of multi-modal data to enhance generalization and
applicability across diverse clinical environments.
