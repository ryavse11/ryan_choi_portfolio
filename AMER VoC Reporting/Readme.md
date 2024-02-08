<!-- Title -->
<h1 align="left">AMER Marketing VoC Reporting </h1>


<h2 align="left">Summary </h2>

AWS AMER Marketing VoC Reporting aims to gather customer sentiment and aggregate the feedback into a Tableau dashboard that AWS AMER marketing stakeholders can see to understand each campaign's impact on customer behavior and propensity. Chungwoo(Ryan) led the project and built the AMER VoC reporting leveraging AWS Salesforce data, Tableau data source, survey flow, survey work process map, and the API provided by Qualtrics.  

![image](https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/038a606f-566c-48f2-bdd6-aebd1e64c4ca)


<h2 align="left">Implementation </h2>

To collect valid customer feedback for VoC reporting, Chungwoo(Ryan) created the AMER Marketing work process map (see below) and built multiple Qualtrics survey questionnaires to help AWS marketing reps streamline the data feed process. The streamlined process map that Chungwoo(Ryan) created is used by all marketing reps when they converse with the customers and collect customer sentiment. The work process map is currently incorporated in the AWS AMER marketing Wiki page for reference. 

![image](https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/fc50e593-1019-4c86-8d4f-a8650ceda0c8)

Chungwoo(Ryan) connected the Tableau AMER VoC dashboard with the Qualtrics data repository. He automated data feed from Qualtrics for the VoC reporting designed for all AMER marketing managers, campaign owners, campaign managers, MRC managers, reps, and AWS FM (field marketing) stakeholders. After implementation, he also supported the AWS marketing stakeholders by providing Qualtrics survey and VoC report customization to help stakeholders track customer sentiment with different AWS campaigns and events. Qualtrics data is extracted into the AWS FMBI data repository and then combined with SFDC data daily utilizing Campaign Member ID in AWS SFDC as a primary key to pull the corresponding customer data for the VoC reporting. 

![image](https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/9742c9f2-f366-4c03-87fc-1fbde3d30adb)


<h2 align="left">Business Impact </h2>

The AMER Marketing VoC Report improved the quality of marketing qualified leads(MQLs) that originate from an AWS tier-1 Event or Acceleration Initiative. In Q1 2023, the conversion rate of marketing-qualified leads (MQLs) to sales-qualified leads (SQLs) in AMER increased to 56% from 43% conversion rate of automated MQLS. The resulting conversion rate generated +372 MQLs YoY, contributing $7.6M in the SQL pipeline. During this time, AMER marketing reps engage customers on a 1:1 basis following a campaign or in support of Acceleration Initiatives using Qualtrics survey and the streamlined AMER Marketing work process map above.

<h2 align="left">Data Source </h2>

The AMER Marketing VoC analysis pulls data from Field Marketing Business Intelligence(FMBI) data sources in the AWS Redshift cluster. Chungwoo also created data sources using custom SQLs to pull the AWS Salesforce tables containing campaign members, lead flow sequential, and funnel stages. Qualtrics data is extracted from its data repository and is combined with SFDC data using Campaign Member IDs as the primary key to join customers' demographic data in SFDC and Qualtrics survey questionnaire response data. 


<h2 align="left">Skills Used </h2>
- Process Diagram Modeling <br>
- Data Integration using Qaultrics APIs
- Data Modeling  <br>
- Data Cleaning <br>
- Qualtrics Survey Design <br>
- Data Visualization - Tableau <br>
- SQL <br>
- ETL(Amazon DataNet)<br>
- Collaboration and Communication

