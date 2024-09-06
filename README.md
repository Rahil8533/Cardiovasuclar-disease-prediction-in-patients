# Cardiovascular disease prediction in patients
## 1.1 The problem
Cardiovascular disease CVD) is a general term for conditions affecting the heart or blood vessels. It's usually associated with a build-up of fatty deposits inside the arteries (atherosclerosis) and an increased risk of blood clots. It can also be associated with damage to arteries in organs such as the brain, heart, kidneys and eyes.[1] The exact causes of heart disease are unknown however there are several things that may increase one’s risk of getting heart disease, these are known as risk factors. The more risk factors one has, the greater one’s chances of developing cardiovascular disease. Risk Factors for cardiovascular disease include high blood pressure, high cholesterol, smoking, diabetes, obesity, physical inactivity, unhealthy diet, and excessive alcohol use. Genetic factors and age also play significant roles.[1] People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help. The risk factors of heart disease can be used as indicators though which early detection of heart disease is possible. The objective of this project is to use some of these early indicators commonly used by doctors to detect heart disease in an artificial neural network (ANN) deep learning model to understand the efficacy of how well a deep learning model can detect heart disease and compare this with human doctors. The dataset to be used in this project is taken from Kaggle and I will elaborate more on its use later in this document.

## 1.2 Motivation
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide Over three quarters of which takes place in low and middle-income countries. Often, there are no symptoms of the underlying disease of the blood vessels. A heart attack or stroke may be the first sign of underlying disease. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs.[2]

Through such a project I can create a system that could rapidly diagnose heart disease and get timely treatment to patients that may otherwise be subject to long waiting lists for a doctor and not receive treatment in time to address their symptoms.

## 1.3 Objectives
•	Through such a project I aim to create a system that could predict heart disease in patients and get timely treatment to patients that may otherwise be subject to long waiting lists for a doctor and not receive treatment in time to address their symptoms.
•	Create such a model on a cheap easily available platform so that such a model could be exceptionally useful in middle- and low-income countries. 
•	Create a system that can match the performance of doctors in terms of sensitivity and specificity to demonstrate that such a system could augment or even replace doctors so as to free their time up to focus their efforts on addressing patients with cardiovascular diseases rather that spend hours diagnosing patients with cardiovascular disease ultimately reducing their burden and allowing them to save more lives.
## 1.4 Results
1. Model Performance: The consistency of high F1 scores across different neural network architectures suggests that we have successfully captured underlying patterns in the data that are strongly indicative of cardiovascular disease. This consistency also implies a degree of model stability, which is essential for real-world applications.
2. Architectural Innovations: Our implementation of TabNet, a relatively new architecture designed specifically for tabular data, alongside traditional feedforward networks, has provided valuable insights into the strengths of different approaches. TabNet's feature selection mechanism and interpretability features offer potential advantages in understanding the factors contributing to cardiovascular risk.
3. Potential for Clinical Impact: With F1 scores in the mid-to-high 80% range, our models show promise as supportive tools for clinicians. Additionally these models also exceed doctors in their sensitivity by at least 12 percentage [23] points this reduces the odds of missing a patient with heart disease. They could potentially assist in early detection and risk stratification, enabling more timely interventions and personalized patient care strategies. Additionally, the higher sensitivities of the models in comparison to general practitioners especially of that in TabNet and the balanced performance of LVQ could significantly improve healthcare outcomes for patients when used clinically.
