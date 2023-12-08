Author - Khushi Bansal, Ritika Kumari, Dhanraj Bhosale <br>
1.	INTRODUCTION 
The project includes a comprehensive overview of the Multiple Disease prediction model using machine learning (ML) models implemented in Python, and a user interface developed with Streamlit, the intuitive user interface to build an application. In today's world, the demand for healthcare data has significantly increased and allows us to develop accurate and user-friendly tools that will definitely ensure a significant impact on early diagnosis and treatment. The project focuses on addressing specific needs, and challenges existing in the healthcare sector. We aim to improve healthcare, and patient outcomes and ensure overall efficiency in disease prediction.
 
1.1	Purpose of the project 
      In the case of the disease prediction system using ML, the target beneficiaries would be patients who are at risk of developing a particular disease. The system would use ML algorithms to analyze patient data and predict the likelihood of developing a disease based on various factors. Patients who are identified as being at high risk could then be targeted for early intervention and treatment.

Another potential beneficiary of such a system would be healthcare providers. By using ML algorithms to analyze patient data, healthcare providers could make more informed decisions about patient care and resource allocation. For example, they could identify patients who are at high risk of developing a particular disease and provide them with targeted interventions to prevent or delay the onset of the disease.

1.2	Target Beneficiary 
      
1. Patients and Healthcare Consumers:

Individuals seeking medical care and services.
Patients with specific medical conditions or healthcare needs.

2.	Vulnerable or Underserved Populations:

Low-income individuals or families.
Marginalized or disadvantaged communities.
Rural or remote populations with limited access to healthcare.

3.	Elderly or Geriatric Population:

Seniors who may have unique healthcare needs.
 
1.3 Project Scope 
 
Data-Driven Healthcare: ML-based disease predictive systems harness the power of big data, including patient records, medical imaging, genetic information, and lifestyle data to make informed predictions about an individual's risk of developing a particular disease.

Early Detection: These systems aim to detect diseases at their earliest stages, enabling early intervention and treatment, which can significantly improve patient outcomes and reduce healthcare costs.

1.4 References: 
•	Smith, A. (2020). Machine learning applications in disease prediction. Journal of Health Informatics, 15(3), 120-135.
<br>
•	Johnson, B. C. (2019). Machine Learning in Healthcare. Academic Press
<br>
•	Rodriguez, D., & Perez, S. (2018). A comparative analysis of disease prediction models using machine learning. In Proceedings of the International Conference on Health Informatics (ICHI) (pp. 45-52).
<br>
•	Wilson, E. (2021). Leveraging machine learning for early disease detection. HealthTech Journa
<br>
•	Heart disease prediction using supervised machine learning algorithms: Performance analysis and comparison Md Mamun Ali a , Bikash Kumar Paul a,b,c , Kawsar Ahmed b,c,* , Francis M. Bui d , Julian M. W. Quinn e , Mohammad Ali Moni e,f,
<br>
•	Disease Prediction System using Support Vector Machine and Multilinear Regression
<br>
•	International Journal of Innovative Research in Computer Science & Technology (IJIRCST) ISSN: 2347-5552, Volume, 8, Issue, 4, July, 2020
<br>
 
2. PROJECT DESCRIPTION 
 
2.1 Reference Algorithm  <br>

1. Logistic Regression <br>
2. Support vector machine <br>
2.2 Data/Data Structure <br>
Data structures used for disease prediction:
<br>
1. Outlier treatment :  outlier treatment is the process of identifying and addressing outliers in a dataset. Outliers are data points that significantly differ from the majority of the data and can skew the results of statistical analyses. Outlier treatment is essential for ensuring the accuracy and reliability of data-driven decisions and models.
<br>
2. Sparse data structure :  
A sparse data structure is a data structure specifically designed to efficiently store and manipulate data in which a significant portion of the values are zero or null. In many applications, such as scientific computing, natural language processing, and certain types of databases, data can be sparse, meaning that only a small fraction of the data points actually contain meaningful information. Storing such data in a regular, dense data structure would be highly inefficient in terms of memory usage and computation time. Sparse data structures aim to address this issue by only storing non-zero or non-null values and their corresponding indices.

2.3 SWOT Analysis <br>
Strengths	Weaknesses
- Can predict multiple diseases using a single analysis.	- The accuracy of the predictions may vary depending on the quality of the data used to train the model.
- Can help doctors and patients make informed decisions about their health.	- The system may not be able to predict all diseases with equal accuracy.
- Can be used to monitor the patient’s condition and warn the patients in advance to decrease mortality ratio.	- The system may require a large amount of data to train the model.
	- The system may not be able to predict new diseases that have not been trained on.
	
Opportunities	Threats
- Can be used to improve the quality of healthcare.	- The system may be vulnerable to cyber - attacks.
- Can be used to reduce healthcare costs.	- The system may not be accessible to everyone due to technological barriers.

2.6 Design and Implementation constraints  
 
  

Fig:1

2.7 Design Diagram
 
 
3. SYSTEM REQUIREMENTS  
3.1 User Interface  
For design and implementation, we will be using Streamlit for building our user interface in Python. Spyder, and Collab for frontend and backend respectively. GitHub for seamless collaboration.
3.2 System Interface  
The Language we will use is Python.
3.3 Database Interface  
We have our data set in Excel
4. NON-FUNCTIONAL REQUIREMENTS 
4.1 Performance Requirements  
      Performance requirements for a healthcare project outline the specific criteria and expectations regarding the performance of the project, its components, and the healthcare systems or services it aims to improve. These requirements ensure that the project meets its objectives, delivers high-quality healthcare services, and aligns with industry standards and best practices. Here are some key performance requirements for a healthcare project:
1. Response Time:
Define acceptable response times for critical healthcare systems, such as electronic health records (EHRs) and telemedicine platforms, to ensure that healthcare professionals can access and update patient information quickly.
2. System Availability:
Specify the minimum allowable system downtime for healthcare applications to ensure availability for patient care and data access.
3. Data Security and Privacy:
Set performance requirements for data encryption, access controls, and authentication mechanisms to protect patient data in compliance with healthcare privacy regulations (e.g., HIPAA).
4. Scalability:
Ensure that healthcare systems can scale to accommodate a growing number of patients and healthcare providers without compromising performance.
5.Interoperability:
Define standards and performance requirements for data exchange between different healthcare systems and devices to promote interoperability and seamless data sharing.
Accuracy and Precision:
 For Heart Disease : 85% <br>
 For Parkinson’s Disease: 87% <br>
For Diabetes: 77 % <br>
