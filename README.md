Healthcare Insurance Cost Analysis

Project Overview

This project is a data analytics application designed to explore, analyse, and interpret healthcare insurance cost data using Python. The objective is to identify the key personal and geographic factors associated with higher insurance charges and demonstrate how data analytics supports evidence-based decision-making in an insurance and underwriting context.

The project follows a structured ETL and exploratory analysis workflow using Jupyter Notebooks and Python data analysis libraries. 




Dataset Content

The dataset used in this project is a publicly available healthcare insurance dataset containing anonymised individual-level records. Each row represents a policyholder. The dataset includes the following variables:
	•	age: Age of the policyholder
	•	sex: Gender
	•	bmi: Body Mass Index
	•	children: Number of dependants
	•	smoker: Smoking status (yes / no)
	•	region: Geographic region
	•	charges: Annual insurance charges

The dataset is of moderate size and suitable for exploratory analysis. No personally identifiable information is included. Raw and cleaned versions of the dataset are stored in clearly defined project folders.



Business Requirements

The analysis addresses the following business requirements:
	•	BR1: Understand the overall distribution of insurance charges and whether costs are concentrated among a minority of individuals.
	•	BR2: Assess whether smoking status is associated with significantly higher insurance charges.
	•	BR3: Identify how insurance charges change with age and BMI and whether these relationships appear linear or non-linear.
	•	BR4: Determine whether average insurance charges differ by geographic region.
	•	BR5: Identify correlations between key numeric variables to support a data-driven understanding of cost drivers.




Hypotheses and Validation Approach

The following hypotheses were defined at the outset:
	•	H1: Smokers have higher insurance charges than non-smokers.
	•	H2: Insurance charges increase with age.
	•	H3: Higher BMI is associated with higher insurance charges.
	•	H4: Average insurance charges vary by region, but regional differences are weaker than lifestyle factors such as smoking.

Validation methods:
	•	Grouped descriptive statistics (means and medians)
	•	Visual comparisons using histograms, box plots, scatter plots, and bar charts
	•	Correlation analysis of numeric variables
	•	Evidence-based interpretation rather than model-driven inference



Project Plan

High-Level Steps
	1.	Extract raw data from CSV source
	2.	Clean and prepare data using an ETL pipeline
	3.	Perform exploratory data analysis (EDA)
	4.	Create visualisations aligned to business requirements
	5.	Produce a predictive report
	6.	Interpret findings, limitations, and recommendations

Data Management
	•	Raw data stored in dataset/raw/
	•	Cleaned data stored in dataset/cleaned/
	•	Analysis conducted only on cleaned data
	•	Clear separation between ETL and analysis notebooks


Analysis Techniques Used

Techniques
	•	Descriptive statistics (mean, median, count)
	•	Grouped aggregation and pivot tables
	•	Feature engineering (age bands, BMI bands)
	•	Correlation analysis
	•	Rule-based predictive segmentation

Structure Justification

The analysis progresses from high-level summaries to more granular insights, allowing stakeholders to build understanding step-by-step.

Data Limitations and Alternatives
	•	The dataset is cross-sectional and does not capture changes over time
	•	No clinical health indicators are included
	•	Predictive insights rely on historical patterns rather than forecasts

Use of Generative AI Tools

Generative AI tools were used as a supporting aid for:
	•	Improving code readability and organisation
	•	Refining analysis

All final outputs were reviewed and validated manually.


Ethical Considerations
	•	The dataset is anonymised and contains no personal identifiers
	•	No sensitive medical diagnoses are included
	•	Analysis avoids discriminatory conclusions and focuses on association rather than causation
	•	Findings are framed to support fair and transparent decision-making

Dashboard Design

This project does not include a deployed dashboard. Instead, the notebooks act as a reporting interface through:
	•	Clear section headings and narratives
	•	Visualisations aligned to business questions
	•	Interpretable tables and summaries


Unfixed Bugs

No critical bugs were identified.


Development Roadmap

Challenges
	•	Balancing predictive insight with interpretability
	•	Avoiding over-engineering while meeting assessment criteria

Future Learning
	•	Longitudinal and time-series analysis
	•	Comparing rule-based logic with machine learning models
	•	Building interactive dashboards using Plotly



Deployment

This project was not deployed as a live application. 


Main Data Analysis Libraries
	•	pandas – data loading, cleaning, aggregation
	•	numpy – numerical operations
	•	matplotlib – base visualisations
	•	seaborn – statistical plots and heatmaps

Credits

Content
	•	Public healthcare insurance dataset
	•	Official Python library documentation (pandas, matplotlib, seaborn)

Media
	•	No external media assets were used
