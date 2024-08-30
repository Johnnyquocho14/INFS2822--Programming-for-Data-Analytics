# INFS 2822- Programming for Data Analytics 

## **File dictionary**
**Built with …**

•	Python (Pandas, NumPy, Scikit-learn, and Matplotlib)

•	Jupiter notebook

•	Excel   

### **File Dictionary** 

•	INFS 2822_T3_2022_ Group assignment brief: Assignment brief on what needs to be delivered in the report 

•	W12A-G04_Code.ipynb: Coding file for the group report.  

•	W12A-G04_report.docx: Report on analyzing car crashes in NSW using Python

### **Motivation**

Requirement Summary:

•	Analyse NSW road crash data from 2017-2021 to understand factors contributing to car crashes and their severity.

•	Investigate how external factors such as weather conditions and speed limits influence car crash severity.

•	Identify timing and seasonal patterns in car crashes.

•	Explore the extent of geographical influences on the frequency of car crashes.

•	Utilize data visualization tools (e.g., Pandas, Matplotlib, Seaborn) and predictive models (e.g., Linear Regression, Logistic Regression, Decision Tree Classification) to provide actionable insights and recommendations for Transport for NSW.

### **Summary of the code**

•	Data analysis was conducted using Python in a Jupyter notebook.

•	Key libraries employed include Pandas for data manipulation, Matplotlib and Seaborn for data visualization, and Scikit-learn for building and evaluating machine learning models.

•	Data preprocessing steps included handling missing values, converting categorical variables into numerical formats, and standardizing data where necessary.

•	Multiple models were developed, including Linear Regression to analyze the relationship between speed limits and crash severity, and Logistic Regression and Decision Tree Classification to predict the likelihood and severity of crashes based on various factors.

•	Visualizations such as pie charts, bar graphs, and heatmaps were generated to display insights from the data.

### **Summary of Results** 
•	**Speed Limits:** Higher speed limits were found to correlate with higher fatality rates in crashes. Speed management was recommended as a crucial area for intervention.

•	**Weather Conditions:** Contrary to expectations, the majority of crashes occurred in fine weather, suggesting that driver complacency may play a role in crash occurrences.

•	**Timing and Seasonality:** Data indicated higher fatality rates during daytime, particularly on weekends. Seasonal patterns showed spikes in crashes during summer and holiday periods, likely due to increased traffic and possibly impaired driving.

•	**Geographical Influence:** Western Sydney, especially areas like Bankstown and Liverpool, exhibited higher crash frequencies. Targeted interventions in these areas were recommended.

## **Model Performance:**

•	**Linear Regression:** Demonstrated a weak correlation between speed limits and crash severity, suggesting the need for more sophisticated models to capture these relationships.

•	**Logistic Regression:** Showed moderate effectiveness in predicting crash severity, with an accuracy of 56.7%. However, it struggled with precision for non-severe crashes.

•	**Decision Tree Classification:** Provided valuable insights into the factors contributing to crash severity, emphasizing the importance of speed limits and road classification.

## **Recommendations:**
	•	Focus on daytime driving education and awareness campaigns to reduce fatal crashes during high-traffic periods.
 
	•	Implement stricter speed management policies, particularly in high-speed zones.
 
	•	Enhance safety measures in high-incident areas such as Bankstown and Liverpool.
