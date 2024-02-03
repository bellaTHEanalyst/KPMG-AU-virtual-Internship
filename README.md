# KPMG-AU-virtual-Internship

![](https://github.com/bellaTHEanalyst/KPMG-AU-virtual-Internship/blob/main/kpmgJpeg.webp)

## Task 1: Data Quality Assessment

I arrive at my desk after the initial client meeting. I have a voicemail on my phone which contains the following instructions.

[Voicemail transcript below]
 

“Hi there – Welcome again to the team! The client has asked our team to assess the quality of their data; as well as make recommendations on ways to clean the underlying data and mitigate these issues.  Can you please take a look at the datasets we’ve received and draft an email to them identifying the data quality issues and how this may impact our analysis going forward?

I will send through an example of a typical data quality framework that can be used as a guide. Remember to consider the join keys between the tables too. Thanks again for your help.”


[Read email below]

Hi there,

As per voicemail, please find the 3 datasets attached from Sprocket Central Pty Ltd:

Customer Demographic 
Customer Addresses
Transaction data in the past three months
Can you please review the data quality to ensure that it is ready for our analysis in phase two. Remember to take note of any assumptions or issues we need to go back to the client on. As well as recommendations going forward to mitigate current data quality concerns.

I’ve also attached a data quality framework as a guideline. Let me know if you have any questions.

Thanks for your help.

Kind Regards
Your Manager


 

Here is my task:

Draft an email to the client identifying the data quality issues and strategies to mitigate these issues. Refer to ‘Data Quality Framework Table’ and resources below for criteria and dimensions which you should consider.

The client provided KPMG with 3 datasets:
- Customer Demographic

- Customer Addresses

- Transactions data in the past 3 months

This is a project from my KPMG data analytics virtual internship program where work as a Data Analyst to performed three tasks:

Data Quality Assessment: Assessment of data quality and completeness in preparation for analysis.

Data Insights: Targeting high value customers based on customers demographic and attributes.

Data Insights and Presentation: Using visualizations to present insights.

## TASK 1 SOLUTION
 
Subject: Addressing Data Quality Issues and Mitigation Strategies

Dear Sprocket Central Pty Ltd,

I hope this email finds you well. We have conducted a thorough review of the data sets provided, and I wanted to bring to your attention some data quality issues that we have identified along with suggested strategies for mitigation.

- Transaction Dataset:

Quality Issues:
Blank cells in the fields of online order, brand, product line, product class, product size, list price, standard cost, and product first sold date.
Inconsistent data types across the table.

- Customer Demographic Dataset:

Quality Issues:
Blank cells in last name, DOB, job title, and tenure fields.

Incorrect data (U, F, M, Femal) in the Gender field.

Incorrect data in the DOB field.

Deletion of the default column containing non-printable letters.

- Customer Address Dataset:

Quality Issues:

Data inconsistency in the state (NSW / VIC). It would be preferable to consistently use either "NSW" or "VIC" throughout the data entry instead of mixing with New South Wales and Victoria, respectively.

**Mitigation Strategies:**

Standardization:

Standardize the entry format for categorical variables (e.g., gender) to avoid inconsistencies.

Implement data validation rules to ensure completeness in essential fields.

Cleaning:
Address blank cells through imputation techniques based on the context of each dataset.

Correct data inaccuracies manually or through automated data cleaning processes.

Documentation:

Establish clear data entry guidelines, especially for state abbreviations, to maintain consistency.

Provide training and resources to data entry personnel for accurate and uniform data input.

Regular Audits:

Implement regular data audits to identify and rectify any emerging issues promptly.

Set up automated alerts for potential errors during data entry.

By addressing these data quality issues and implementing the suggested strategies, we aim to enhance the accuracy, completeness, and consistency of your datasets. This, in turn, will contribute to more reliable analyses and decision-making processes.

Please feel free to reach out if you have any questions or if you would like to discuss these strategies further.

Best regards,

Isabella Martins,

Data Analyst,

Martinzzbella@gmail.com.

## Task 2:Data insights

 Using the result from Task 1 I would be analyzing  the  cleaned datasets (from Task 1) to uncover patterns and trend which would be used to help make informed decision about the 1000 new customers (in the new_customer dataset) should be targeted to drive the most value for the organization. (SPROCKET LTD.)

The three phases involved in this module were;

· Data Exploration

· Model development

· Interpretation

Data exploration
 
