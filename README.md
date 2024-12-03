# Classification-Of-Drug-Using-Neural-Networks
This project demonstrates how to use a Neural Network model to categorize drugs based on patient information including age, gender, blood pressure, cholesterol, and sodium-to-potassium ratio. We construct a predictive model by processing and assessing the data to accurately identify the appropriate drug class. This research focuses on the practical use of machine learning in the healthcare business.

# Getting Started
Set up the project on your own PC for development and testing using the instructions below.

# Prerequisites
The following software and libraries are required:
Python 3.8 or higher
Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn
Install the prerequisites by running:
pip install numpy pandas matplotlib seaborn scikit-learn

# Installing
Clone the repository using the code below:
git clone <repository-url>.
Navigate to the project directory.
CD Drug Classification
Put the dataset file drugdataset (1).csv in the project directory.
Run this Python script:
drug_classification.py
This script will preprocess the data, train the Neural Network model, and return the evaluation results.

# Running the tests.

**Data Preprocessing Validation**
Ensures that the dataset is loaded and processed properly.
Example: Verifying the distinct medication classifications using the code 
data.Drug.unique() 
**Model Evaluation Tests**
A Confusion Matrix and Classification Report are generated to assess model performance, using the code below:
print(confusion_matrix(y_test, predictions)
Print (classification_report(y_test, predictions, target_names=target_names, zero_division=0))
**Coding Style Tests**
Ensure that your code follows Python's PEP 8 style guide. Use tools such as flake8.
Pip install flake8 flake8 drug classification.py

# Deployment
For live deployment:
Implement the model in a web or desktop application using frameworks such as Flask or Django.
To enable scalability, deploy the application on a cloud platform such as AWS, Azure, or GCP.

# Built with:
Scikit-learn: machine learning and data preprocessing platform.
Pandas: Data manipulation and analysis.
Matplotlib/Seaborn: Data Visualization

# Contributing

We are happy to accept contributions to this project! Whether you're resolving a problem, updating the code, or creating a new feature, your assistance is greatly valued. Please take the following actions to ensure a smooth contribution process:
**Fork the repository.**
To create your own copy of this repository, click the "Fork" button at the top of the repository page.
**Clone your fork.**
Clone the forked repository on your local system.
**Create a branch.**
Create a new branch for your changes. Choose a descriptive name, such as add-visualization or fix-scaling-issue.
**Make your changes.**
Update the code or documentation as necessary.
Ensure that your changes are consistent with the project's structure and code standards.
Include notes for any sophisticated logic or changes.
**Test your changes.**
Run the script to ensure that your updates function as intended.
If you're introducing new functionality, incorporate or update existing tests.
**Commit your changes.**
Create a clear commit statement that describes what you've done.
**Push to your Branch.**
Push the branch containing your changes to your forked repository.
**Open a pull request (PR).**
Go to the original repository and create a pull request for your split branch. Make sure to:
Provide a compelling title and description for your PR.
Explain why the modification is necessary and what problem it solves.
**Review and collaborate.**
The maintainers will review your PR. Be open to comments and prepared to make changes if necessary.

We appreciate you taking the time and effort to improve this project. 

# Versioning
We follow Semantic Versioning (SemVer) for tracking updates.

# Authors
Archana Anish

# License
This project is released under the MIT License. See the LICENSE.md file for more information.

# Acknowledgments
Thank you to the creators of scikit-learn for their incredible tools that make machine learning accessible.
Thank you to everyone who contributes to the Python data science community and makes projects like this possible!

