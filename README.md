Lead Scoring Case Study
Objective
X Education, an online education company, offers industry professionals various courses. The company receives many leads through their website and marketing efforts on platforms like Google and other websites. These leads are generated when potential customers show interest by browsing courses, watching videos, or filling out contact forms. Additionally, leads also come through referrals.

Once leads are captured, the sales team reaches out via calls and emails to convert them into paying customers. However, the lead conversion rate is currently only around 30%, meaning for every 100 leads, only about 30 are converted into paying customers.

To improve the efficiency of their sales process, X Education wants to identify which leads are most likely to convert—referred to as "Hot Leads." By focusing on these high-potential leads, the company aims to improve the conversion rate and reduce the time wasted on less promising leads.

The task is to build a logistic regression model that will assign a lead score (0-100) to each lead. A higher score will indicate a higher likelihood of conversion, while a lower score will indicate the lead is less likely to convert. Additionally, the model should be adaptable for future business requirements.

Process Overview
The following steps will be followed to develop the lead-scoring model:

1. Data Reading
The dataset includes various lead details, such as their activity on the website and engagement with the company.
2. Data Cleaning
Handling missing or inconsistent values to ensure the quality and integrity of the data.
3. Exploratory Data Analysis (EDA)
Understanding key trends, correlations, and distributions in the data that could impact lead conversion.
4. Creating Dummy Variables
Transforming categorical data into numerical format to be used in the logistic regression model.
5. Data Splitting
Splitting the cleaned data into training and test sets to evaluate model performance.
6. Model Building
Using logistic regression to build a predictive model that assigns a score between 0 and 100 to each lead.
7. Making Predictions
Using the model to predict the likelihood of conversion for leads in the test set.
8. Model Evaluation
Assessing the performance of the model using accuracy, precision, recall, and other metrics.
9. ROC Curve
Evaluating the model’s performance using the ROC (Receiver Operating Characteristic) curve, which helps determine the trade-offs between true positive and false positive rates.
10. Precision-Recall Analysis
Analyzing the balance between precision (positive predictive value) and recall (sensitivity) to optimize the model for lead conversion.
Files Provided
Lead Score Case Study Aayushi Meenu.ipynb: A Jupyter Notebook showing the Python code used for data analysis and model building.
Assignment Subjective Questions.pdf: A document answering subjective questions related to the case study.
Lead Score Case Study.pdf: A final presentation summarizing findings and recommendations.
Leads.csv: The dataset containing lead details.
Leads Data Dictionary.xlsx: A data dictionary explaining the fields in the dataset.
Summary.pdf: A summary report outlining the steps performed in the Jupyter Notebook.
Next Steps
Adjusting to Future Requirements:
The model needs to be flexible enough to accommodate potential changes in the company’s lead scoring requirements.
This could include the introduction of new features or changes in the relative importance of existing features.
Final Presentation:
A PowerPoint presentation will summarize the results and insights from the model, along with actionable recommendations for improving the lead conversion process at X Education.
This structured approach will help X Education efficiently identify high-potential leads, thereby improving their lead conversion rate and maximizing sales productivity.








