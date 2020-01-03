# Logical_rythm

This project is basically a contest based project.
The project consisted of two problems-

1.Find The Fund

Description:
Majumdar, Khanna and Rawat have been invited to the 20th Annual Global Entrepreneurship Summit in Los Angeles, because of their exceptional skills in the field of Machine Learning. The investors in the summit are curious to know about the various incubating startups that are participating in the summit, and are also interested in funding them, if they are impressed by their work.

The organisation team of the event has the data of all the companies that participated in the previous editions and also some outsourced data about other startups. They are willing to share the data with our three friends, provided they help investors in deciding whether they should invest in a particular startup or not.

Can you help our three friends in their task?

Evaluation:

We will be using categorisation accuracy to calculate the performance of your model. Categorisation accuracy is basically the same as sklearn.metrics.accuracy_score(). Which calculates (the number of correct predictions)/(total number of predictions).

Data Description
The data contains information about 40 thousands companies, spread across the globe, in the form of 17 columns, each having specific information about the respective company.

File descriptions:

train.csv - the training set
test.csv - the test set
sampleSubmission.csv - a sample submission file in the correct format


Columns Description:

ID - Id of the Company
company_name - Name of the Company
website - Company Website URL
op_status - Operational status (0 = closed or operating, 1 = acquired)
domain - Industry Category of the company, including up to four subcategory divisions
founded_on - The date the company was founded (in string format ‘2003-09-04’)
hq_country_code - Country Code of the company’s HQ
hq_state_code - State Code of the company’s HQ
hq_region - Region of the company’s HQ
hq_city - City of the company’s HQ
total_funding_usd - Total Amount raised in all the funding rounds
funding_rounds - Total count of the funding rounds
first_funding_date -Date the company first raised funding (in string format ‘2008-07-11’)
last_funding_date - Date the company last raised funding (in string format ‘2010-10-28’)
num_investors - Number of investors
first_funding_utc - Time (in UTC) the company first raised funding (in string format ‘2010-10-28’)
last_funding_utc - Time (in UTC) the company last raised funding (in string format ‘2010-10-28’)
successful_investment - Output Label; whether investment will be successful or not (0 = unsuccessful, 1 = successful)



