<!-- Title -->
<h1 align="left">AWS ML Lead Prioritization </h1>


<h2 align="left">Summary </h2>

The marketing lead prioritization in AWS was traditionally based on the likelihood of an opportunity created by the associated individual, where the possibility is measured using lead scores. The project (Lorem) aims to measure the impact after applying a machine learning approach to predict marketing qualified leads(MQLs) that would convert into sales qualified opportunities (SQOs). For the project, Chungwoo(Ryan) designed and pulled scoring model feature sets, trained the ML model, led multi-phased A/B testings, and then analyzed the test results to determine if there is enough evidence in the sample data to draw conclusions on the ML-based lead prioritization model. 

<a href="https://github.com/ryavse11/ryan_choi_portfolio_0129/blob/main/AWS%20ML%20Lead%20Prioritization/Model_Feature_Sets.md">ML Scoring Model Feature Set SQL</a>

<h2 align="left">Implementation </h2>

Chungwoo(Ryan) mainly worked on training the ML model on <a href="https://github.com/ryavse11/ryan_choi_portfolio_0129/blob/main/AWS%20ML%20Lead%20Prioritization/ML_traning_dataset_01.SQL">the CS(Commercial Sector) data set </a> that he pulled from the AWS Jarvis database cluster. Starting with around 73k MQLs having ‘completed followed up’, he split the sample into 2 data sets - training and test - based on a date split. The ML model trained on the data set before applying to the test set. The training outcome produces a numeric value, which is called the ML-score. Then, the ML-score was used to rank marketing qualified leads (MQLs) from high to low priority. For example, if MQL A has an ML-score of 0.7, and MQL B has an ML-score of 0.4, MQL A will be prioritized over MQL B.

<a href="https://github.com/ryavse11/ryan_choi_portfolio_0129/blob/main/AWS%20ML%20Lead%20Prioritization/ML_traning_dataset_01.SQL">ML Traning Dataset SQL</a>

<image src="https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/13c062c9-c2d5-461a-bdb4-bbd86deaf89a" 
width="750" height="450"/>


<h2 align="left">Business Impact </h2>

1.	Improved the marketing qualified leads (MQLs) quality (measured by Sale Qualified Opportunities (SQO) conversion rate) shared between marketing and sales organizations by enabling transparent scoring logic and filtering invalid/missing information, further reducing the volume of disqualified MQLs and withdrawn MQLs.

<image src="https://github.com/ryavse11/ryan_choi_portfolio_0129/assets/151677676/c2666ab9-44f0-4338-b7bc-052b6d277f5d" 
width="550" height="450"/>



2.	Provided a complete history of lead engagement with AWS, allowing sellers to have insightful conversations.
3.	The overall MQL-SQO conversion metrics were improved. As shown in the table below, the grade buckets A and B of the ML-based model have been able to capture more leads that resulted in higher MQL-SQO conversions than the equivalent grade buckets of traditional rule-based scoring. The grade buckets below are the percentile rank bins of “ML-based model” scores and traditional “rule-based model” scores. Grade A is the top 10% of each score type, while Grade B is the next 20%, Grade C is the next 30%, Grade D is the next 30%, and Grade E is the final 10%. Moving down these grade buckets, the ML-based and Rule-based model scores each reflect a decline in the actual count of MQL-SQO conversions. This trait tells us that both scoring methods can prioritize MQLs to a valid extent.


      ![image](https://github.com/ryavse11/ryan_choi_portfolio_0129/assets/151677676/e9d19e07-334c-457b-ac62-f602b6dcc455)


4.	Enabled adjustment on MQL volumes based on sellers' capacity and allowed sellers to focus on specific buyer personas with specialized selling strategies.

<h2 align="left">Data Source </h2>

Chungwoo(Ryan) trained an ML model on ASEAN’s Commercial Sales (CS) lead population as input data and measured its Marketing Qualified Lead (MQL) to Sales Qualified Opportunity (SQO) conversion (MQL-SQO CR%) performance. He built the data set by pulling the commercial sector (CS) AMER and EMEA public sector(PS) AMER models in production. The following subsections describe the characteristics of the data.
Data query criteria: biz_unit = ‘CS’, area = ‘ASEAN’ , and only “Completed Follow-Up” MQLs are included.
Data overview:

**Data query criteria:** biz_unit = ‘CS’, area = ‘ASEAN’ , and only “Completed Follow-Up” MQLs are included.

**Data overview:**

<image src="https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/8872cec4-631b-468c-8942-acf032793c4b" 
width="550" height="400"/>


<h2 align="left">Skills Used </h2>

- Descriptive Statistics <br>
- Machine Learning <br>
- Hypothesis Testing  <br>
- Data Modeling <br>
- Data Cleaning <br>
- Query Writing <br>
- ETL - Amazon DataNet <br>
- Data Visualization - Tableau and QuickSight <br>
- Collaboration and Communication






