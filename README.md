# CBA1C07-BUSINESS-INTELLIENCE-FUNDAMENTALS

BIFN AY2021 Apr - Assignment Spec(1)
Temasek Polytechnic
School of Informatics & IT

Specialist Diploma in Business Analytics
Specialist Diploma in Financial Analytics

		AY 2020/2021 April Semester



Business Intelligence Fundamentals
CBA1C07

Assignment
	
Business Intelligence Fundamentals (CBA1C07)
Assignment Specification

	Objectives

This assignment aims to assess students’ theoretical understanding and practical knowledge of concepts covered in independent learning and practical sessions.

	Learning Outcomes

After completing this assignment, students should be able to:
	Explain the concepts and benefits of business intelligence;
	Apply various techniques for data profiling and data cleaning;
	Perform data integration and transformation (if necessary);
	Perform data exploration using Descriptive Statistics;
	Apply concepts of Linear Regression to explore relationship between variables; and
	Present your understanding on the business requirement, evaluate the results from data exploration and make recommendations.

	Introduction 

This assignment requires you to apply the business intelligence concept of understanding the business problem, auditing the data, employing various techniques for data cleaning, performing data integration and transformation (if necessary), performing data exploration and interpreting the results. You will need to produce a report detailing the work you have done for each stage of your work.

This assignment is an individual component, which contributes towards 70% of your final subject score.  
 
	Datasets 

In this assignment, you will make use of the datasets FRANCHISE_500 and FRANCHISE_CEO which can be found in PolyMall.  
The data was taken from the site (https://www.entrepreneur.com/franchise500), which was originally sourced from publicly available information from the entrepreneur site (https://www.entrepreneur.com), but had been cleansed, analysed or aggregated where appropriate to facilitate discussion.
The FRANCHISE_500 dataset is a subset of data taken from above-mentioned site and has the following names and descriptions:
Name	Description
2016_rank	Ranking of Franchise in 2016
company	Name of company
category_detail	Business category
franchise_500_rank	Top 500 Franchise ranking
initial_investment	Initial ivestment required for franchising
high	Maximum amount of investment required for franchising
change_in_units_1_yr	Change in franchise units within 1 year
change_in_units_3_yr	Change in franchise units within 3 year
founded	Year the company is founded
franchising_since	Year Franchising started
corporate_address	Corporate Address
veteran incentives	Incentives given to franchisee operators
highest rank	Highest ranking on the franchise listing
lowest rank	Lowest ranking on the franchise listing
where_seeking_franchise	Locations where Franchising is available 
operations	The type of training provided for franchising 



The FRANCHISE_CEO dataset is taken from above-mentioned has the following names and descriptions:
Name	Description
company	Name of company
ceo	Name of the ceo
parent company	Parent company of the franchise
net worth required	Net worth requirement for franchisees
liquid cash requirement	Non-borrowed and cash on hand liquid cash requirement
Initial franchise fee	Fees paid to franchisor when franchise agreement is signed
	Task – Case Study
The dataset comes from studying the franchise industry to gather the most comprehensive franchise ranking for franchisees in the U.S. or Canada only. And with each year, the ranking becomes increasingly competitive, as more and more companies see the value of expansion through franchising and throw their hats into the ring. The list shows just how varied the franchise world has become, offering prospective franchisees a myriad of choices, from more traditional options, like restaurants, maintenance services, and gyms to the latest trends.
So just how do we go about evaluating and ranking such a diverse pool of opportunities? 
What You Need To Do
As a business analyst of a company, you are to explore the data and find out some insights of the trends of franchises.

Before you can visualize and perform analysis on the data, there is a need to understand the business requirements, understand the data and perform data cleaning and exploration. 

In order to quantify the increase or decrease of number of franchise units, some methodologies to be used to estimate the change in franchise units in one or three years and the net worth requirement and liquid cash requirement

The methodologies are as follows:
	A base of 1,000 is used for change in units 1 Yr. Therefore, if Change in Units in 1 Yr is +0.7% + 11 units, change in franchise units in 1 Yr = 0.7/100  × 1,000 + 11 = 18 franchise units. For null values in change in franchise units it can be replaced with overall average value.
	A base of 1,000 is used for change in units 3 Yr. Therefore, if Change in Units in 3 Yr is +9.6% + 7 units, change in franchise units in 3 Yr = 9.6/100  × 1,000 + 7 = 103 franchise units. For null values in change in franchise units it can be replaced with overall average value.

	The average is used for given range of net worth requirement and liquid cash requirement. Therefore, if net worth requirement is $80,000 - $310,000, the net worth requirement = (80,000 + 310,000)/2 = $195,000. For null net worth and liquid cash requirement, it can be replaced with the overall average value.
The Template
The following are considerations for your assignment which you can use as a template:

Business Understanding
Describe the business scenario and provide one business problem you are trying to solve.

Data Profiling
Audit your data and explain the data profiling done. Highlight any problems discovered (such as missing values and inconsistencies). Take screenshots of your work.
 
Data Cleaning
Document the steps that you have used to resolve the issues found in data profiling above. Take screenshots of your work. Explain the rationale for the data cleaning technique used. 
 
Data Integration
Link the two data tables together. Ensure that their relationships are either one to many or many to one. Indicate the join key used. Document the relationship by taking screenshots of your work. 

Data Transformation
Document any calculated columns/formulae used and provide appropriate explanations. 

Note: For numeric columns, please remember to change data type to decimal/whole number for analysis purpose later. 

Data Exploration
Capture the screenshots of the charts that you have used to explore the data distribution, spread of data and relationship between variables. Provide interpretation of your charts.
 
Conclusion/Recommendation
Provide a conclusion/recommendation to the business.


Special Note
For this assignment, the focus is on data profiling, data cleaning, data exploration, data integration and transformation. Please follow the approach found in Topic 4 / Practical 4 to 6 using Microsoft Power BI. 

You also need to use the underlying statistics and business intelligence concepts learnt in Topic 1 to 3 / Practical 1 to 3 to help you identify the problem statement, analyze the results and make appropriate conclusion and recommendations.

There is no need for you to perform in-depth data analysis, data visualization and dashboard conceptualization (as these will be covered in your next subject - Business Intelligence Project).
 
	Deliverables

There are 2 deliverables for this assignment: 

(i)	Solution

A Microsoft Power BI(.pbix) file must be submitted. Please ensure that all the work you have done for data profiling, data cleaning, data exploration and data integration and transformation are captured in the Power BI file. 

(ii)	Report (including the link for the video walk-through)

A report that is not more than 10 pages excluding cover page, references and appendices must be submitted. The report must be in a format that is readable using MS Word. 

Please ensure that you have the following in your report:

	Your report is comprehensive for the marker to appreciate the work you have done without having to reference your Power BI file;  

	Proper acknowledgement and referencing are included (if applicable); 

	The report is preceded by the cover page and declaration of originality of work provided in Annex A and B respectively.

	All documentation, output of results and analysis are aligned with the marking criteria on page 9.  

	The report includes a download link of a five-minute video walk-through of your work which highlights key insights you have found in your analysis.


NOTE

	Please refer to the file: How To Create A Video and Upload To YouTube.pdf for the step-by-step guide.

	DO NOT SUBMIT the mp4 file into PolyMall due to storage size issues. You just need to copy and paste the download link into your report.

	Ensure that the privacy setting is set to “unlisted”. Unlisted videos are only accessible to people who know the video link but not the public. 


	Mode of Submission and Deadline

The deliverables must be submitted in soft copy (one word document and one pbix file) via PolyMall Safe Assign submission before 21 June 2020, 11:59 PM.

Please take note of the polytechnic’s guideline on penalty for late submissions
	Late and < 1 day: 10% deduction from absolute mark given for the assignment e.g. 75 marks (100 marks max) becomes 65 marks (deduct 10% of 100 marks)
	Late >=1 and <2 days: 20% deduction from absolute mark
	Late >=2 days: 0 marks awarded

 
	Marking Criteria


Deliverable	Excellent	Good	Fair	Poor
Report
(including Presentation)


		Very clear identification of problem statement.
	Detailed documentation of data profiling,  cleaning, exploration, integration and transformation.

	Well-formatted report with good logical flow.

	Clearly written and insightful analysis and conclusion.		Reasonably clear identification of problem statement.
	Reasonable documentation of data profiling, cleaning, exploration, integration and transformation.

	Well-formatted report with reasonably good logical flow.
	Clearly written and reasonably insightful analysis and conclusion.		Unclear identification of problem statement.
	Documentation of data profiling, cleaning, exploration, integration and transformation had some missing elements.
	Poorly-formatted report but with some logical flow.

	Analysis and conclusion not clearly written with not much insights provided.		No identification of problem statement.

	Documentation of data profiling, cleaning, exploration, integration and transformation was unclear or missing.
	Poorly-formatted report with little coherent.
	Poor analysis and conclusion with no/flawed insights.
Solution


		Completely identified data problems.
	Identified data problems were resolved completely.
	Much data transformations were done.
	Charts created were relevant and coherent to the business objective.		Partially identified data problems.
	Identified data problems were reasonably resolved
	Reasonable data transformations were done.
	Charts created were reasonably relevant and coherent to the business objective.		Poorly identified data problems.

	Identified data problems were partially resolved

	Few data transformations were done.
	Charts created were somewhat relevant to the business objective but not effectively presented.		Unable to identify data problems.
	No resolution done as no data problem was identified.
	No data transformation was done.
	Charts created were irrelevant to the business objective or presented in confusing manner.


***** End of Assignment Specification *****
Annex A: Cover Page Template

Specialist Diploma in Business Analytics
Specialist Diploma in Financial Analytics

AY2020/2021 Apr Semester


Business Intelligence Fundamentals
(CBA1C07)


Assignment

Submitted by

STUDENT NAME (student admission number)
                                 

Date of Submission

Annex B: Declaration of Work Originality Template 

Specialist Diploma in Business Analytics
Specialist Diploma in Financial Analytics
Business Intelligences Fundamentals (CBA1C07)
AY2020/2021 Apr Semester 
Assignment


Submitted by:  <Student admission number > <Student full name>

Date:  <signing date in dd /mm/yyyy format>


“By submitting this work, I am declaring that I am the originator of this work and that all other original sources used in this work have been appropriately acknowledged.

I understand that plagiarism is the act of taking and using the whole or any part of another person’s work and presenting it as my own without proper acknowledgement.

I also understand that plagiarism is an academic offence and that disciplinary action will be taken for plagiarism.”



Name and Signature of student: …………………………………...

