# diabetes-prediction

Diabetes is a growing global health concern that affects millions of individuals and poses significant challenges to healthcare systems. Early identification of individuals at risk is critical, as timely intervention can reduce complications, improve quality of life, and lower healthcare costs. However, traditional diagnostic methods often rely on clinical tests performed only after symptoms emerge, which limits opportunities for preventive care.

In real-world healthcare data, an additional challenge arises: the number of patients without diabetes greatly exceeds those diagnosed with the disease. This class imbalance makes it difficult for predictive models to accurately detect diabetes cases, as standard machine learning algorithms often favor the majority class, resulting in poor sensitivity and a high rate of missed diagnoses.

The goal of this project is to develop and evaluate machine learning models that can effectively predict diabetes risk from patient lifestyle and health-related features. To address the imbalance in the dataset, this project applies Synthetic Minority Oversampling Technique (SMOTE), which generates synthetic examples of diabetes cases to balance the training data. The models explored—Logistic Regression, Random Forest, and XGBoost—are evaluated on their ability to improve recall (sensitivity), precision, and overall predictive performance.

By leveraging resampling techniques and advanced machine learning models, this project aims to provide insights into which algorithms are most effective in identifying patients at risk for diabetes. In a healthcare context, such predictive tools can support clinicians in early detection and targeted intervention, ultimately improving patient outcomes and resource allocation.
