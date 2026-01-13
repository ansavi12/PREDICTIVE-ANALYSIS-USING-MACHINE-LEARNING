# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY*= CODTECH IT SOLUTION

*NAME*= ANSH VIKAS NANAWARE

*INTERN ID*= CTIS2580

*DOMAIN*= DATA ANALYTICS

*DURATION*= 4WEEKS

*MENTOR*= NEELA SANTOSH

Task Description:Machine Learning Model Implementation Using Google Colab

This task focuses on building and evaluating a Machine Learning model in Google Colab to predict outcomes based on previously available data. The objective of the task is to demonstrate the complete workflow of a machine learning project, including data loading, preprocessing, model training, prediction, and insight generation, using a cloud-based environment.

Google Colab was chosen as the execution platform because it provides a scalable, cloud-hosted Python environment with built-in support for popular machine learning libraries such as Pandas, NumPy, and Scikit-learn. This allows the task to be implemented efficiently without requiring local system setup, making it ideal for educational and internship-based projects.

The dataset used in this task consists of student-related information, including roll number, gender, and marks. The dataset was uploaded in CSV format and loaded into Google Colab using Pandas. Initial exploration of the dataset was performed to understand its structure, verify data types, and ensure that the data was correctly imported. This step is crucial in any machine learning task to avoid errors during model training.

Data preprocessing was performed to prepare the dataset for modeling. This included selecting relevant features and defining target variables. Two types of machine learning approaches were demonstrated. First, a classification approach was used to predict whether a student would pass or fail based on marks. Since classification models require at least two target classes, an appropriate threshold was applied to the marks to create balanced pass and fail categories.

Second, a regression model was implemented to predict numerical outcomes, specifically student marks, based on historical data. A Linear Regression model was trained using previously available student records. This model learns patterns from existing data and is capable of predicting marks for new input values. Regression is particularly useful when the target variable is continuous and numerical.

After training the model, predictions were generated for both existing data and new input values. The predicted marks were then used to determine pass or fail status using predefined decision rules. This two-step approach demonstrates how machine learning models can be combined with business logic to derive meaningful outcomes.

Model testing and validation were performed using unseen data to evaluate performance. The results showed that the model was able to generalize well and provide reasonable predictions. This step highlights the importance of separating training and testing data in machine learning workflows to avoid overfitting.

*OUTPUT* = 

<img width="943" height="692" alt="Image" src="https://github.com/user-attachments/assets/2e6fb292-a604-42b4-b744-bfe933a19a31" />
<img width="922" height="690" alt="Image" src="https://github.com/user-attachments/assets/a0023498-6656-40d6-badc-6efd7398bd5d" />
<img width="863" height="696" alt="Image" src="https://github.com/user-attachments/assets/d3e82279-8bf4-4929-aeda-ea249ef9e0aa" />
<img width="931" height="702" alt="Image" src="https://github.com/user-attachments/assets/b0c41610-64ad-48d9-8654-2112f2536235" />
<img width="925" height="751" alt="Image" src="https://github.com/user-attachments/assets/d0045644-76ea-4e7d-b482-9487a2b9086e" />
<img width="748" height="728" alt="Image" src="https://github.com/user-attachments/assets/c337a164-b2b2-45ac-b62f-36f936e362eb" />
<img width="920" height="740" alt="Image" src="https://github.com/user-attachments/assets/acb3047c-8477-4c3a-8309-8e95d0639890" />

The final output of the task includes predicted marks and corresponding pass/fail results, which were clearly displayed in the notebook. These results demonstrate how machine learning can support decision-making processes using historical data.

In conclusion, this task successfully demonstrates the implementation of a machine learning model in Google Colab, covering the complete lifecycle from data ingestion to prediction. The project reflects real-world machine learning practices and fulfills the internship requirements by showcasing predictive analytics, model evaluation, and practical application of previous data.
