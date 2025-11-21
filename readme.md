# HealthCare: AI-Powered Multi-Disease Diagnosis Platform

- HealthCare: AI-Powered Multi-Disease Diagnosis Platform is a comprehensive diagnostic support system built on a robust and modern tech stack. 

- The platform integrates a multi-modal approach to disease prediction, utilizing both classical machine learning and deep learning

- For structured data inputs—such as age, blood pressure, and glucose levels—models like Logistic Regression, SVM, and Random Forest are employed via Scikit-learn to predict conditions like heart disease and diabetes.

- For unstructured data, such as chest X-ray images, a Convolutional Neural Network (CNN) built using TensorFlow or PyTorch is employed for pneumonia detection.

- The system architecture features a decoupled frontend (HTML/CSS, Bootstrap, and optionally React.js) and a powerful Python backend (Flask/Django) connected via a REST API.

- This ensures a seamless and interactive user experience.

- User data and prediction results are securely stored in a Server. 

- Designed for scalability and easy deployment HealthCare serves as a vital tool for early health screening, telemedicine, and clinical support.


# Team Member :

- __Rajyaguru Aryan__ : Team Leader 
- __Jadeja Umang__ : Team Member  
- __Patel Mahek__ : Team Member 
- __Patel Princy__ : Team Member 

# Project Run Steps:
1. Install Anaconda
2. Download Project Zip or Clone Project Git Repo
3. Open Full Project Folder on VS code 
4. In VS Code Open cmd(CTRL + J) (note : By default open PowerShell so first change PowerShell to cmd)
5. In cmd enter the command that below mention:
	1. conda create --name healthcure python=3.9
		in that ask y/n in that gives : y
	2. conda activate healthcure
	3. pip install -r requirements.txt
	4. python app.py

Terminate Project:
6. conda deactivate