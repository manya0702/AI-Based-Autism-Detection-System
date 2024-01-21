# AI Based Autism Detection System


# Problem Statement

Autism Spectrum Disorder (ASD) is a complex neurodevelopmental condition that impacts individuals of all ages. This disorder comprises of symptoms ranging from social and communicational challenges to an exhibition of repetitive behaviors. Early diagnosis and prognosis of ASD is focal for managing its symptoms, supplementing learning outcomes, and social skill development. Conventional diagnosis of ASD based on behavioral evaluations confronts problems owing to the lack of clear-cut rules. On the other hand, Machine Learning and Deep Learning models-based techniques excel in diagnosing ASD by assessing behavioral factors, finding even the tiniest contrariety in gaze and facial attributes. 

# Objective

We aim to propose an AI based Autism Detection System that incorporates two distinct models targeting different age groups. For children in the age group of 2 to 8 years, the Xception model was used to capture the degree of facial dysmorphology from images in order to ascertain the possibility of Autism. For individuals aged 9 or above, Light Gradient Boosting Machine (LGBM) Classifier is used to capture the relationship of various indicators like Autism Spectrum Quotient score, age, gender, ethnicity, etc. in determining ASD. This multifaceted approach enhances accuracy while catering to the unique characteristics and needs of both children and adults with Autism.

# Results

To detect Autism amongst individuals of different age groups, different ML and DL based classifiers have been employed on the two datasets. For the dataset constituting individuals aged 2-8 years, CNN and multiple pre-trained models have been applied. On comparing the performance metrics of these models, it was inferred XceptionNet was the best performing model. The model exhibited an accuracy of 85% with the macro-average Precision, Recall F1-Score and AUC ROC scores being 86%,85%,85% and 0.92 respectively.

On the other hand, for the dataset constituting individuals aged 9 years and above, multiple ML classifiers were applied. On comparing the performance metrics of various algorithms, it can be inferred that Light Gradient Boosting Machine classifier was the best performing model. The model exhibited an accuracy of 99% with the macro-average Precision, Recall and F1-Scores being 98%,99%,98% respectively.

