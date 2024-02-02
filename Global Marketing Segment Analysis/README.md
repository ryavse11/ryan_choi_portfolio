<!-- Title -->
<h1 align="left">Global Marketing Segment Analysis </h1>


<h2 align="left">Summary </h2>

The Global Marketing Segment Analysis was implemented with the intent of tracking the following metrics. 
1. Global marketing teams' contribution to field marketing
2. Month-over-month performance for each segment
3. AWS marketing region performance vs. monthly/annual goals
4. sub-segment and sub-region drill-down results

The segment analysis results and the dashboard are viewed by all segment leadership, global marketing managers, and marketing reps in AWS marketing team to track each team's KPI attainment and regional field marketing performance at a segment/sub-segment level. I built and delivered the Global Segment Analysis dashboard using Tableau and multiple datasources that I built using Amazon Field Marketing Business Intelligence (FMBI) Redshift clusters.<a href="https://github.com/ryavse11/ryan_choi_portfolio_0129/blob/main/AWS%20ML%20Lead%20Prioritization/Model_Feature_Sets.md"> 

<h2 align="left">Implementation </h2>

I trained the ML model on <a href="https://github.com/ryavse11/ryan_choi_portfolio_0129/blob/main/AWS%20ML%20Lead%20Prioritization/ML_traning_dataset_01.SQL">the CS(Commercial Sector) ASEAN data set </a> that I pulled from the Jarvis database cluster in AWS. Starting with around 73k MQLs having ‘completed followed up’, I split them into 2 data sets - training and test - based on a date split. The model then trains on the training set before being applied on the test set. The outcome of the latter step produces a numeric value which we call the ML-score. This ML-score is used to rank MQLs from high to low priority. For example, if MQL A has an ML-score of 0.7, and MQL B has an ML-score of 0.4, MQL A will be prioritized over MQL B.

<a href="https://github.com/ryavse11/ryan_choi_portfolio_0129/blob/main/AWS%20ML%20Lead%20Prioritization/ML_traning_dataset_01.SQL">ML Traning Dataset SQL</a>

<image src="https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/13c062c9-c2d5-461a-bdb4-bbd86deaf89a" 
width="750" height="450"/>


<h2 align="left">Business Impact </h2>

1.	Improved the MQL quality (measured by Sale Qualified Opportunities (SQO) conversion rate) shared between marketing and sales organization, by enabling transparent scoring logic and filtering invalid/missing information, further reducing the volume of disqualified MQLs and withdrawn MQLs.

<image src="https://github.com/ryavse11/ryan_choi_portfolio_0129/assets/151677676/c2666ab9-44f0-4338-b7bc-052b6d277f5d" 
width="550" height="450"/>



3.	Provide complete history of lead engagement with AWS, allowing sellers to have insightful conversations.
4.	The overall MQL-SQO conversion metrics were improved and grade buckets A and B of the ML based model are able to capture more leads that experience MQL-SQO conversions than the equivalent grade buckets of traditional rule based scoring. The grade buckets below are the percentile rank bins of “ML based model” scores, and traditional “rule based model” scores. Grade A is the top 10% of each score type, whilst Grade B is the next 20%, Grade C is the next 30%, Grade D is the next 30% and Grade E is the final 10%. Moving down these grade buckets, the ML based and Rule based model scores each reflect a decline in the actual count of MQL-SQO conversions. This trait tells us that both scoring methods can prioritize MQLs to a good extent.


      ![image](https://github.com/ryavse11/ryan_choi_portfolio_0129/assets/151677676/e9d19e07-334c-457b-ac62-f602b6dcc455)


5.	Enable adjustment on MQL volumes based on seller’s capacity, and allow sellers to focus on specific buyer persona with specialized selling strategy.

<h2 align="left">Data Source </h2>

I trained an ML model on ASEAN’s Commercial Sales (CS) lead population as our input data, and measured its Marketing Qualified Lead (MQL) to Sales Qualified Opportunity (SQO) conversion (MQL-SQO) performance. I used the data by building the commercial sector (CS) AMER, CS EMEA and public sector(PS) AMER models in production. The following sub sections describe the characteristics of the data.

**Data query criteria:** biz_unit = ‘CS’, area = ‘ASEAN’ , and only “Completed Follow-Up” MQLs are included.

**Data overview:**

<image src="https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/8872cec4-631b-468c-8942-acf032793c4b" 
width="550" height="400"/>


<h2 align="left">Skills </h2>
- <b>Descriptive Statistics <br>
- Hypothesis Testing  <br>
- Data Visualization <br>
- Data Cleaning <br>
- Data Analysis <br>
- SQL(Redshift)/ETL(DataNet) </b><br>
