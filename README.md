# TATA-GenAI-Powered-Data-Analytics
<img width="900" height="450" alt="image" src="https://github.com/user-attachments/assets/9beefe7c-bf32-44df-a0c9-cca478c99fcc" />


**Welcome** to the GenAI Powered Data Analytics.

Tata Insights and Quants (Tata iQ) is the Tata Group’s advanced analytics and AI center of excellence. Tata iQ partners with companies across the Group to turn data into competitive advantage by enabling smarter, data-informed decision-making.

**During this program, you will step into the role of an AI transformation consultant and complete tasks that replicate the work this role does every day. You’ll learn key skills in:**

Predictive modeling using GenAI tools
Data exploration and quality assessment
Business storytelling and recommendation design
Designing AI-driven systems for fair and responsible automation


**Team at Tata**

<img width="850" height="400" alt="image" src="https://github.com/user-attachments/assets/fd6b1bad-d3a8-4b48-ba10-4f37f05e56ec" />

This team at **Tata iQ** specializes in leveraging **data analytics** and **AI-powered insights to enhance decision-making in the financial sector.** The team collaborates with business leaders and strategy teams across **Tata’s financial services companies to develop predictive models, risk assessments, and AI-driven** intervention strategies for optimizing business outcomes.

# Task 1: Exploratory data analysis and risk profiling**

**What you'll learn**


♦ How to conduct exploratory data analysis (EDA) using GenAI. 

♦ Techniques to handle missing values and ensure data quality. 

♦ Understanding customer risk factors for delinquency. 

♦ How to leverage synthetic data generation to enhance datasets when real data is insufficient.

**What you'll do**


♦ Identify key datasets required to predict delinquency. 

♦ Perform an exploratory analysis on provided datasets, using GenAI tools to assist with summarization, treatment of missing data, risk profiling, and synthetic data creation. 

♦ Document your findings, including data patterns and anomalies that may impact predictions.

# key objectives:

* Review the provided dataset and assess its structure, completeness, and key attributes, and then identify any missing or inconsistent data points that could affect predictions.
* Use GenAI-assisted tools to generate insights while ensuring data confidentiality and avoiding the exposure of sensitive financial information.
* Summarize the patterns, anomalies, and risk indicators that should be considered in later stages of the project in a report.

The first stage of the project: conducting an **exploratory data analysis (EDA)** to assess dataset completeness, identify patterns, and flag potential gaps that could impact delinquency predictions.

# Introduction to exploratory data analysis (EDA)

Before you start working on your project, it's important to build a solid foundation in the key topics you'll need to understand. This preparation will ensure you have the tools and knowledge necessary to approach your tasks with confidence and skill.

**What is exploratory data analysis?**
Exploratory data analysis (EDA) is the first step in understanding a dataset before applying any predictive models or making business decisions. EDA helps analysts uncover patterns, trends, inconsistencies, and missing values to ensure data quality and reliability. In the context of financial services, EDA plays a crucial role in risk assessment, allowing teams to identify key factors contributing to credit card delinquency and build stronger prediction models. Here is why EDA matters in predicting delinquency:

* **Ensures data integrity** – Identifies missing values, duplicates, and inconsistencies before analysis.
* **Highlights patterns and anomalies** – Helps detect trends in customer behavior, such as spending patterns before delinquency.
* **Prevents biased model**s – Reduces the risk of unfair treatment by ensuring diverse data representation.
* **Supports better decision-making** – Provides Geldium’s Collections and Risk teams with clear insights for proactive customer engagement.
  Without a thorough EDA process, predictive models can be built on flawed data, leading to inaccurate insights, poor risk management, and potentially unfair decision-making. Later in this task, you will            examine a dataset related to delinquency risk, identify missing or inconsistent data points, and generate initial insights using GenAI tools.

# Key steps in conducting EDA

EDA consists of four main steps, which can be enhanced with GenAI tools:

# 1️⃣ Understanding the dataset
Before jumping into analysis, take time to familiarize yourself with the dataset. Ask yourself:

* What are the **key variables** (e.g., payment history, income levels, credit utilization)?
* Are there **categorical or numerical** data points?
* Are there **missing or inconsistent values**?
**Using GenAI:** You can use **AI-powered summarization** tools to quickly scan a dataset and generate an overview. Tools such as ChatGPT or Google Gemini can help interpret column headers, suggest relevant features, and summarize key statistics.

💡 Example prompt: "Analyze this dataset and provide a summary of key columns, including common patterns and missing values."

# 2️⃣ Identifying missing values and outliers
Incomplete data can lead to poor predictions. Missing values in credit risk datasets may result from human error, system failures, or unreported financial activity.

Here are some common techniques for handling missing data:

* **Statistical imputation (industry standard):** Replace missing values using well-established techniques such as **mean, median, or regression-based imputation.** (We've provided a resource with further information on imputation below.)
* **Understanding missingness patterns:** Before filling in missing values, determine whether the data is **missing completely at random (MCAR), missing at random (MAR), or missing not at random (MNAR)** to avoid introducing bias. This site includes a great overview document explaining the missing data types.
* **Removing irrelevant data:** If a feature has excessive missing values and cannot be meaningfully imputed without introducing bias, it may be best to exclude it—but only after assessing its impact on model accuracy and fairness..

# Using GenAI (for exploration, not direct imputation):

* AI-powered tools can **automate missing value detection and summarize data gaps,** helping analysts assess which variables require attention.
* GenAI can suggest **potential imputation strategies** based on statistical best practices, but **final decisions should be validated with domain expertise.**
* **Synthetic data generation** may be an option when real data is unavailable, but it should be **validated against real-world distributions** to prevent bias.

💡 Example prompt: "Identify missing values in this dataset and recommend the best imputation strategy based on industry best practices."

# 3️⃣ Understanding relationships between variables
EDA also involves examining how different features interact. For example:

* Do customers with high credit utilization rates have a higher risk of delinquency?
* Is there a correlation between income levels and late payments?

# Using GenAI:

* AI models can automate correlation analysis, helping identify key risk indicators.
* Instead of manually coding formulas, GenAI can summarize variable relationships in natural language.

💡 Example prompt: "Analyze the correlation between customer income and delinquency risk, summarizing key findings in simple terms."

# 4️⃣ Detecting patterns and risk factors
The final step in EDA is to identify patterns that could impact delinquency prediction. These might include:

Customers who miss one payment often miss multiple.
Younger customers or those with recently opened accounts may have different risk profiles.

# Using GenAI:

* AI models can highlight trends in the data, making it easier to understand how different features contribute to delinquency.
* AI-assisted insights can be refined by asking follow-up questions, ensuring that the analysis remains relevant to Geldium’s objectives.

💡 Example prompt: "Analyze trends in late payments and identify the top 3 risk factors associated with delinquency."

Here are some resources to help you 

Click to download file → [Imputation Guide](https://github.com/mroyalreddy07/TATA-GenAI-Powered-Data-Analytics/blob/main/Imputation_Guide_Handout.docx)
