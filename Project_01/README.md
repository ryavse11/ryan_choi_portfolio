<!-- Title -->
<h1 align="left">Machine Learning Based Lead Prioritization </h1>


<h2 align="left">Summary </h2>

All leads are not equal in terms of quality and priority. Traditionally, it has been based on the likelihood of an opportunity being created by the associated individual, where the likelihood is measured using a lead score. The project aims to measure the impact of applying a machine learning approach to predict MQLs that would convert into a sales qualified opportunity (SQO). 

<h2 align="left">Approach </h2>

I trained the ML model on the CS ASEAN data. Starting with around 73k MQLs having ‘completed followed up’, I split them into 2 data sets - training and test - based on a date split. The model then trains on the training set before being applied on the test set. The outcome of the latter step produces a numeric value which we call the ML-score. This ML-score is used to rank MQLs from high to low priority. For example, if MQL A has an ML-score of 0.7, and MQL B has an ML-score of 0.4, MQL A will be prioritized over MQL B.


<h2 align="left">Business Impact </h2>

1.	Improve the MQL quality shared between marketing and sales organization, by enabling transparent scoring logic and filtering invalid/missing information, further reducing the volume of disqualified MQLs and withdrawn MQLs.
2.	Provide complete history of lead engagement with AWS, allowing sellers to have insightful conversations.
3.	The overall MQL-SQO conversion metrics were improved and grade buckets A and B of the ML based model are able to capture more leads that experience MQL-SQO conversions than the equivalent grade buckets of traditional rule based scoring.
	< align="center">![image](https://github.com/ryavse11/ryan_choi_portfolio_0129/assets/151677676/ac51dee3-61e1-4364-88ea-4f2ed75e3db0)

   ![image](https://github.com/ryavse11/ryan_choi_portfolio_0129/assets/151677676/048a4037-1179-4be3-9e86-18ba2549fc16)

![image](https://github.com/ryavse11/ryan_choi_portfolio_0129/assets/151677676/b167a787-073d-4051-865a-8bcb9483c4af)

5.	Enable adjustment on MQL volumes based on seller’s capacity, and allow sellers to focus on specific buyer persona with specialized selling strategy.

<h2 align="left">Data Sources </h2>

I trained an ML model on ASEAN’s Commercial Sales (CS) lead population as our input data, and measured its Marketing Qualified Lead (MQL) to Sales Qualified Opportunity (SQO) conversion (MQL-SQO) performance. This model was used to build the CS AMER, CS EMEA and PS AMER models that are currently in production. The following sub sections describe the characteristics of our data.

**Data query criteria:** biz_unit = ‘CS’, area = ‘ASEAN’ , and only “Completed Follow-Up” MQLs are included.

**Data overview:**

![image](https://github.com/ryavse11/ryan_choi_portfolio_0129/assets/151677676/a018fdcf-941a-4816-888b-15af25a74c9c)
