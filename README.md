# Parkinsons-disease-detection

![image](https://github.com/user-attachments/assets/7f210c1a-7eac-4d0c-9662-ef1e40669ba1)


**📌 Overview**
Parkinson’s disease is a progressive neurological disorder that affects movement, speech, and other functions. Early diagnosis is critical for effective treatment and quality of life. In this project, we explore the use of machine learning techniques to detect Parkinson’s disease based on biomedical voice measurements.

Using a Support Vector Machine (SVM) classifier, we analyze a dataset consisting of various vocal features extracted from individuals' voice recordings. The model distinguishes between healthy individuals and those with Parkinson’s, showcasing the power of ML in the medical diagnostic domain.

** Dataset Features**

* name - ASCII subject name and recording number

* MDVP:Fo(Hz) - Average vocal fundamental frequency

* MDVP:Fhi(Hz) - Maximum vocal fundamental frequency

* MDVP:Flo(Hz) - Minimum vocal fundamental frequency

* MDVP:Jitter(%)

* MDVP:Jitter(Abs)

* MDVP:RAP

* MDVP:PPQ

* Jitter DDP - Several measures of variation in fundamental frequency

* MDVP:Shimmer,

* MDVP:Shimmer(dB)

* Shimmer:APQ3

* Shimmer:APQ5

* MDVP:APQ

* Shimmer:DDA - Several measures of variation in amplitude

* NHR,HNR - Two measures of ratio of noise to tonal components in the voice

* status - Health status of the subject (one) - Parkinson's, (zero) - healthy

* RPDE,D2 - Two nonlinear dynamical complexity measures

* DFA - Signal fractal scaling exponent

* spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation


**🔧 Technologies Used**

* Programming Language: Python
  
* Libraries:

* Pandas – Data manipulation

* NumPy – Numerical operations

* Matplotlib, Seaborn – Data visualization

* Scikit-learn – Model training and evaluation

* Model Used: Support Vector Machine (SVM)

**✅ Results**

* The SVM model achieved high accuracy and showed clear separation between the classes.

* Visualizations helped in understanding the distribution of features and correlations between them.

**📌 Conclusion**

This project demonstrates how machine learning can aid in medical diagnosis by leveraging vocal biomarkers. While not a replacement for clinical diagnosis, it can serve as a valuable screening tool and a step toward AI-assisted healthcare solutions.

