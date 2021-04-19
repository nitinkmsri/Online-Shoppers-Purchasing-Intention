# Online-Shoppers-Purchasing-Intention
ML on Online Shoppers Purchasing Intention Dataset

Online Shoppers Purchasing Intention Dataset Data Set
====================================================================================

Author: 
Nitin Kumar (University of Texas at Dallas[Business Analytics])
Jyoti Verma (University of Texas at Dallas[Business Analytics])

1. Introduction
Website: UCI Machine Learning Repository
Page link: https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset
1.1. Data Set Information:
The dataset consists of feature vectors belonging to 12,330 sessions. The dataset was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.
1.2. Source:
C. Okan Sakar Department of Computer Engineering, Faculty of Engineering and Natural Sciences, Bahcesehir University, 34349 Besiktas, Istanbul, Turkey

Yomi Kastro Inveon Information Technologies Consultancy and Trade, 34335 Istanbul, Turkey

1.3. Attribute Information:
S.No.	Attribute Name	Data Type
1.	'Administrative'			int
2.	'Administrative_Duration'	float
3.	'Informational'				int
4.	'Informational_Duration'	float
5.	'ProductRelated'			int
6.	'ProductRelated_Duration'	float
7.	'BounceRates'				float
8.	'ExitRates'					float
9.	'PageValues'				float
10.	'SpecialDay'				float
11.	'Month'						string
12.	'OperatingSystems'			int
13.	'Browser'					int
14.	'Region'					int
15.	'TrafficType'				int
16.	'VisitorType'				string
17.	'Weekend'					Boolean
18.	'Revenue'					Boolean
"Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another.

The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site.

The value of "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session.

The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session.

The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction.

The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8.

The dataset also includes operating system, browser, region, traffic type, visitor type as ## returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.
