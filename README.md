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

# Task 1: Exploratory data analysis and risk profiling

The first stage of the project: conducting an **exploratory data analysis (EDA)** to assess dataset completeness, identify patterns, and flag potential gaps that could impact delinquency predictions.

# Introduction to exploratory data analysis (EDA)

Before you start working on your project, it's important to build a solid foundation in the key topics you'll need to understand. This preparation will ensure you have the tools and knowledge necessary to approach your tasks with confidence and skill.

**What is exploratory data analysis?**
Exploratory data analysis (EDA) is the first step in understanding a dataset before applying any predictive models or making business decisions. EDA helps analysts uncover patterns, trends, inconsistencies, and missing values to ensure data quality and reliability. In the context of financial services, EDA plays a crucial role in risk assessment, allowing teams to identify key factors contributing to credit card delinquency and build stronger prediction models. Here is why EDA matters in predicting delinquency:

* **Ensures data integrity** – Identifies missing values, duplicates, and inconsistencies before analysis.
* **Highlights patterns and anomalies** – Helps detect trends in customer behavior, such as spending patterns before delinquency.
* **Prevents biased model**s – Reduces the risk of unfair treatment by ensuring diverse data representation.
* **Supports better decision-making** – Provides Geldium’s Collections and Risk teams with clear insights for proactive customer engagement.

  Without a thorough EDA process, predictive models can be built on flawed data, leading to inaccurate insights, poor risk management, and potentially unfair        decision-making. Later in this task, you will examine a dataset related to delinquency risk, identify missing or inconsistent data points, and generate initial    insights using GenAI tools.

# Key steps in conducting EDA

EDA consists of four main steps, which can be enhanced with GenAI tools:

# 1️⃣ Understanding the dataset
Before jumping into analysis, take time to familiarize yourself with the dataset. Ask yourself:

* What are the **key variables** (e.g., payment history, income levels, credit utilization)?
* Are there **categorical or numerical** data points?
* Are there **missing or inconsistent values**?

**Using GenAI:**  You can use **AI-powered summarization** tools to quickly scan a dataset and generate an overview. Tools such as ChatGPT or Google Gemini can help interpret column headers, suggest relevant features, and summarize key statistics.

💡 Example prompt: "Analyze this dataset and provide a summary of key columns, including common patterns and missing values."

# 2️⃣ Identifying missing values and outliers
Incomplete data can lead to poor predictions. Missing values in credit risk datasets may result from human error, system failures, or unreported financial activity.

Here are some common techniques for handling missing data:

* **Statistical imputation (industry standard):** Replace missing values using well-established techniques such as **mean, median, or regression-based imputation.** (We've provided a resource with further information on imputation below.)
* **Understanding missingness patterns:** Before filling in missing values, determine whether the data is **missing completely at random (MCAR), missing at random (MAR), or missing not at random (MNAR)** to avoid introducing bias. This site includes a great overview document explaining the missing data types.
* **Removing irrelevant data:** If a feature has excessive missing values and cannot be meaningfully imputed without introducing bias, it may be best to exclude it—but only after assessing its impact on model accuracy and fairness..

**Using GenAI (for exploration, not direct imputation):**

* AI-powered tools can **automate missing value detection and summarize data gaps,** helping analysts assess which variables require attention.
* GenAI can suggest **potential imputation strategies** based on statistical best practices, but **final decisions should be validated with domain expertise.**
* **Synthetic data generation** may be an option when real data is unavailable, but it should be **validated against real-world distributions** to prevent bias.

💡 Example prompt: "Identify missing values in this dataset and recommend the best imputation strategy based on industry best practices."

# 3️⃣ Understanding relationships between variables
EDA also involves examining how different features interact. For example:

* Do customers with high credit utilization rates have a higher risk of delinquency?
* Is there a correlation between income levels and late payments?

**Using GenAI:**

* AI models can automate correlation analysis, helping identify key risk indicators.
* Instead of manually coding formulas, GenAI can summarize variable relationships in natural language.

💡 Example prompt: "Analyze the correlation between customer income and delinquency risk, summarizing key findings in simple terms."

# 4️⃣ Detecting patterns and risk factors
The final step in EDA is to identify patterns that could impact delinquency prediction. These might include:

Customers who miss one payment often miss multiple.
Younger customers or those with recently opened accounts may have different risk profiles.

**Using GenAI:**

* AI models can highlight trends in the data, making it easier to understand how different features contribute to delinquency.
* AI-assisted insights can be refined by asking follow-up questions, ensuring that the analysis remains relevant to Geldium’s objectives.

💡 Example prompt: "Analyze trends in late payments and identify the top 3 risk factors associated with delinquency."

Here are some resources to help you 

Click to download file → [Imputation Guide](https://github.com/mroyalreddy07/TATA-GenAI-Powered-Data-Analytics/blob/main/Imputation_Guide_Handout.docx)

# Here is your task
Before any predictive modeling can take place, it’s crucial to ensure that the dataset you’re working with is complete, accurate, and free of inconsistencies. 

In this task, you will conduct an **EDA on Geldium’s dataset** to help Tata iQ’s analytics team and Geldium’s decision-makers understand the current state of their data. Your analysis will shape how the company refines its delinquency risk model and improves its intervention strategies.

**Here are the steps:**

# Step 1: Review the dataset and identify key insights
Before predictive modeling can begin, it’s essential to understand the dataset’s structure and assess its quality. In this first step, you'll **examine** [Geldium’s dataset](https://github.com/mroyalreddy07/TATA-GenAI-Powered-Data-Analytics/blob/main/Geldium%E2%80%99s%20Dataset.xlsx) to spot any issues and identify early risk indicators.

# What to do:

* Open the dataset and review the key columns. Use the **Dataset Description Guide** to understand what each variable represents.
* Use a GenAI tool (like ChatGPT or DeepSeek) to help quickly summarize the dataset and highlight potential issues.

    * Think about what insights you need from GenAI. What questions would help you explore the dataset effectively? If needed, refer to Section 5 (Key Steps in          Conducting EDA) for examples of AI prompts—but feel free to modify them or create your own! For additional guidance on structuring AI prompts, check out           this article on prompt engineering techniques.
    * **Identify missing or inconsistent data** that could skew your analysis (e.g., missing payment history, unusual credit utilization rates).
    * **Detect early risk indicators.** Which variables might be most relevant for predicting delinquency?

# Step 2: Address missing data and data quality issues
Now that you've identified gaps, it’s time to decide how to handle missing data to maintain accuracy.

**What are the common causes of missing data?**
Missing data can occur due to:

* **Random errors** (e.g., a system glitch fails to record a payment).
* **Skewed data collection** (e.g., high-income customers are less likely to disclose salary details).
* **Customer behavior** (e.g., financially distressed individuals may avoid reporting debt).

Understanding the cause helps determine the best approach for handling missing values.

**How to handle missing values:**
* **Deleting missing data** – If only a **small percentage** of data is missing, removing incomplete entries may be the best approach. However, this can reduce   the sample   size.
* **Imputation (replacing missing values) –**
    * **Mean, median, or mode imputation** fills gaps with typical values.
    * **Forward or backward filling** uses existing data trends to estimate missing entries.
* **AI-Assisted Imputation –**
    * GenAI models can help **detect patterns** and suggest imputation strategies and statistical techniques (e.g., mean, median, or regression-based imputation).
    * AI tools can also suggest **synthetic data** where needed, provided **data privacy is maintained.**

Beyond missing values, check for duplicates, inconsistent formatting, and logical errors (e.g., high credit scores with multiple missed payments). By maintaining data integrity, you ensure that predictive models generate fair and accurate delinquency assessments.

# What to do:

* Identify gaps or missing values in critical features (e.g., payment history, income, credit utilization).
* Determine the best treatment approach for each case:
      * **Remove:** Drop columns with excessive missing data.
      * **Impute:** Fill in missing values using **mean, median, or predictive modeling.**
      * **Generate synthetic data:** Use AI tools to create realistic values while maintaining fairness and distribution patterns.
* Use GenAI to assist with suggesting strategies as well as automating parts of the imputation process

# Step 3: Detect patterns and risk factors
With a cleaned dataset, your next goal is to uncover patterns and key risk factors that influence delinquency.

# What to do:

* Analyze relationships between variables and delinquency outcomes (e.g., is high credit utilization associated with missed payments?).
* Use GenAI tools to help surface insights and prioritize key variables.
* Highlight any unexpected findings that may require further investigation by the analytics team.
* Document key risk indicators and any insights that could impact delinquency prediction. Include patterns that seem obvious as well as any surprising trends that   might need deeper investigation.

# Step 4: Submit your EDA report
* Using the template provided, prepare a brief report summarizing your findings:
      * Key patterns and anomalies detected in the dataset.
      * A summary of missing values and how they were handled.
      * Risk indicators that may impact delinquency predictions.

Uploaded your [EDA summary report](https://github.com/mroyalreddy07/TATA-GenAI-Powered-Data-Analytics/blob/main/EDA_Example_Answer.docx)

# Here are some resources to help you

Click to download file's 👇

[Dataset Description Guid](https://github.com/mroyalreddy07/TATA-GenAI-Powered-Data-Analytics/blob/main/Updated_Dataset_Description_Guide.pdf) 

[EDA_SummaryReport_Template](https://github.com/mroyalreddy07/TATA-GenAI-Powered-Data-Analytics/blob/main/Task%201%20EDA_SummaryReport_Template.docx)

# Task 2: Predicting delinquency with AI

**First, what is predictive modeling?**

Predictive modeling is the process of **using historical data to forecast future outcomes.** In the context of financial services, it helps institutions like Geldium identify customers who are at risk of delinquency so they can take proactive measures. Traditional predictive modeling typically requires coding expertise, but GenAI tools can assist analysts in building, testing, and refining models with less manual coding.

# Here’s how to approach the task:
[Data Set](https://github.com/mroyalreddy07/TATA-GenAI-Powered-Data-Analytics/blob/main/Delinquency_prediction_dataset.xlsx)
# Step 1: Generate model logic using GenAI
Use a GenAI tool to **outline a structured approach** for a predictive model based on the dataset provided.  Rather than coding the model, focus on conceptualizing key components, including:

* The type of model you would use (e.g., logistic regression, decision trees, neural networks).
* Key input features and how they contribute to predictions.
* The general workflow of how the model would process the data to generate outputs.

**Note:** You’ll be working with the same dataset from Task 1. While you don't have to clean or modify the data, your analysis should reflect what you learned during EDA.

# Step 2: Justify your model choice
Once you've outlined your model, it’s important to explain why you chose it. Use what you’ve learned about model interpretability, accuracy, and use cases in financial services.

* Justify why the selected model is appropriate for predicting delinquency.
* Discuss strengths, trade-offs, and why the model fits Geldium’s needs.
* Consider interpretability, ease of deployment, and handling of financial data.
* Connect your reasoning to real-world business needs (e.g., regulatory compliance, transparency).

# Step 3: Plan how to evaluate model performance
A good model must predict both **accurately and fairly.** It’s critical to assess the model’s success and ensure it avoids biased or misleading outcomes. Think about how you would: 

* Identify appropriate evaluation metrics (accuracy, F1 score, AUC, fairness checks).
* Assess the model’s accuracy and reliability
* Check for bias or unfair treatment across different customer groups
* Interpret evaluation metrics and decide when the model needs improvements

# Step 4: Submit your plan
Using the provided template, submit a structured plan that includes:

* Your generated model logic (either GenAI output or a paraphrased version)
* Your model justification — why you chose it and how it fits the task.
* Your evaluation strategy, explaining how you would assess accuracy and fairness.

Deliverable: Submit a Word or PDF file of your plan below.

# Here are some resources to help you

Click to download file's 👇
[Task 2_ModelPlan_Template](https://github.com/mroyalreddy07/TATA-GenAI-Powered-Data-Analytics/blob/main/Task%202_ModelPlan_Template.docx)
