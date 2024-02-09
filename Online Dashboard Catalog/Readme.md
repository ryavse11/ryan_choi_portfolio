<!-- Title -->
<h1 align="left">Online Dashboard Catalog </h1>


<h2 align="left">Summary </h2>

AWS AMER Marketing VoC Reporting aims to gather customer sentiment and aggregate the feedback into a Tableau dashboard that AWS AMER marketing stakeholders can see to understand each campaign's impact on customer behavior and propensity. Chungwoo(Ryan) led the project and built the AMER VoC reporting leveraging AWS Salesforce data, Tableau data source, survey flow, survey work process map, and the API provided by Qualtrics.  

![Dashboard Catalog_01](https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/adf7d711-6a2c-4e59-9eb1-769910de2dfd)


<h2 align="left">Implementation </h2>

To collect valid customer feedback for VoC reporting, Chungwoo(Ryan) created the AMER Marketing work process map (see below) and built multiple Qualtrics survey questionnaires to help AWS marketing reps streamline the data feed process. The streamlined process map that Chungwoo(Ryan) created is used by all marketing reps when they converse with the customers and collect customer sentiment. The work process map is currently incorporated in the AWS AMER marketing Wiki page for reference. 

![Dashboard Catalog_02](https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/c73d4b82-46da-429c-a255-d1f7a6514d91)

Chungwoo(Ryan) connected the Tableau AMER VoC dashboard with the Qualtrics data repository. He automated data feed from Qualtrics for the VoC reporting designed for all AMER marketing managers, campaign owners, campaign managers, MRC managers, reps, and AWS FM (field marketing) stakeholders. After implementation, he also supported the AWS marketing stakeholders by providing Qualtrics survey and VoC report customization to help stakeholders track customer sentiment with different AWS campaigns and events. Qualtrics data is extracted into the AWS FMBI data repository and then combined with SFDC data daily utilizing Campaign Member ID in AWS SFDC as a primary key to pull the corresponding customer data for the VoC reporting. 

![Ryan Choi AWS Tableau Profile](https://github.com/ryavse11/ryan_choi_portfolio/assets/151677676/3178ffe0-b1ed-41e3-bcd4-13b0e912fb77)



<h2 align="left">Business Impact </h2>

Since its launch, the AMER Marketing VoC analysis has contributed to improving the quality of marketing qualified leads(MQLs) from AWS Tier-1 Events or AWS Acceleration Initiatives. In Q1 2023, the conversion rate of marketing-qualified leads (MQLs) to sales-qualified leads (SQLs) from AMER AWS Summit Online campaigns increased to 56% from 43% conversion rate of automated MQLS. The increased conversion rate generated +372 MQLs YoY, resulting in $7.6M in the SQL pipeline. During this time, AMER marketing reps engaged customers on a 1:1 basis following the AWS Summit Online campaigns using Qualtrics survey questionnaires and the streamlined AMER Marketing work process map that Chungwoo(Ryan) created. 

<h2 align="left">Data Source </h2>

The AMER Marketing VoC analysis pulls the campaign member data from Field Marketing Business Intelligence(FMBI) data sources in the AWS Redshift cluster. Chungwoo created data sources using custom SQLs to pull the AWS Salesforce tables containing campaign members, lead flow sequential, and funnel stages. Qualtrics data is extracted from its data repository and is combined with SFDC data using Campaign Member IDs as the primary key to join customers' campaign engagement data stored in SFDC and Qualtrics survey questionnaire response data. 


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

