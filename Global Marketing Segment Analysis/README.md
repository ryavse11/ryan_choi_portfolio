<!-- Title -->
<h1 align="left">Global Marketing Segment Analysis </h1>


<h2 align="left">Summary </h2>

The Global Marketing Segment Analysis was implemented with the intent of tracking the following metrics. 
1. Global marketing teams' contribution to field marketing
2. Month-over-month performance for each segment
3. AWS marketing region performance vs. monthly/annual goals
4. sub-segment and sub-region drill-down results

The segment analysis results and the dashboard are viewed by all segment leadership, global marketing managers, and marketing reps in AWS marketing team to track each team's KPI attainment and regional field marketing performance at a segment/sub-segment level. I built and delivered the Global Segment Analysis dashboard using Tableau and multiple datasources that I built using Amazon Field Marketing Business Intelligence (FMBI) Redshift clusters.





<h2 align="left">Implementation </h2>

I began the project with looking into the global marketing team’s data infrastructure and explored the field marketing datasets in Amazon FMBI cluster. I applied a broad range of data exploration approaches as they relate to field marketing and segment analysis. I created ETL jobs to simplify the data pulling processes to aggregate the segment and sub-segment datasets. You chose Tableau to analyze and visualize the data. I also used statistical methods (regression) to difficult business problems and understand these methods’ assumptions and limitations. You delivered the BI report and the dashboard with the documentation and enablement sessions for the segment leaders to help the get familiar with the dashboard and filters in it. 

I built and delivered the Global Segment Analysis dashboard using Tableau and multiple datasources that I built using Amazon Field Marketing Business Intelligence (FMBI) Redshift clusters.

![image](https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/02c7ed85-834d-49c9-92f0-4cf1a33b6372)

<image src="https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/13c062c9-c2d5-461a-bdb4-bbd86deaf89a" 
width="750" height="450"/>


<h2 align="left">Business Impact </h2>

The Global Marketing Segment Anlysis provided the segment leaders and campaign managers with the improved visibilities on sub-segment performances. In AMER, after several months of zero Marketing Qualified Leads(MQLs) in Q4 2022, the team generated their first ENT Greenfiled MQLs and SQLs in February 2023 from the F200 Priority campaign resulting SQL pipeline of $108k. In LATAM SMB, the team was able to be more efficient in its email outreach and achieve 197.0% attainment. AMER startup segment worked achieved MQL YoY increase of 456%. Given the recent adjustment in segment capacity, the team look forward to the growth and impact working high quality leads in the corresponding segments using the data from the segment analysis. 

![image](https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/a741b21f-0f4d-4bb4-b0ce-ecb592f746df)


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
