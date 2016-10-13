# Data_Visualization
This is a Data Visualization project for Prosper Loan Data.
#                                           Prosper Loan Data Visualization
#Summary 
Prosper Marketplace is a peer-to-peer lending marketplace connecting those who need a loan to those who have extra money to lend. I investigated the performance of Prosper Loan from the Investor and Borrower point of views by looking at the LenderYield and BorrowerAPR and type of loans. I was interested to show the relation between above mentioned variables based on the loan status and borrowers credit ratings. It will be possible to find out what type of loan and to what level of ProsperRating has lowest risk and highest return for investors. In other hand for each borrower can find out what type of loan has lowest BorrwerAPR.

#Design 
I used the Martini Glass structure to provide above mentioned variables animated and then used by reader in an interactive way. The animation can be paused by clicking on each one of the loan types and hover on the bar chart for different Prosper Ratings. The x axis shows Prosper Ratings and y axis shows the total number of investors for each category of prosper ratings. Each different colored sections of the bar chart shows the “Loan Status” of each loan. Hovering on each section will show the related values for “Term”, “Lender Yield”, “Borrower APR”, “Loan Status”, “Prosper Rating”, and the number of “Investors” in a particular loan.
The Loan Status is color coded with indication legend on the top left corner of the graph. The Loan Type is shown as a horizontal bar chart on the right side with the length of each bar showing the number of loans in each category.
Among several different information that can be extracted from this data visualization, readers can explore the data interactively. For example:
a.	The length of each Loan Type can show investors and borrowers the popular loan types through which they can see which loans can be invested quickly.
b.	The distribution of the Loan Status for each loan type among borrowers with different Prosper Rating shows investors which rate has higher yield with lower risk. 
c.	Borrowers can investigate with their particular Prosper Rating, what type of loans has higher chance to be fulfilled on time.
d.	Investors can find their expected returned yield per borrowers rating and also loan types.
e.	Borrowers can investigate the amount of APR they might end up paying per their rating and the type of loan they are requesting.

#Feedback 
I received following feedbacks from three of my colleagues and final version of the data visualization is based on their feedbacks: ion from the first sketch to the final visualization
1-	The first sketch visualization was Writer Oriented and didn’t show enough information on the graph. So I added more specifications by adding legends to the graph.
2-	The second sketch was not animated and still was Writer oriented. So I used the Storyboard Control with the tick event for the reader to visualize the data properly. 
3-	The y axis originally was showing the commutative values for  “Lender Yield” which was not informative enough for readers, so I received a feedback as to change it to   “Investors” variable which gives better sense to the investors and borrowers to compare and learn about the loans and find out if a loan type is popular enough for investing or if requested will be fulfilled quickly. 


#Resources 
Dimple:
http://dimplejs.org/
Margin Convention:
http://bl.ocks.org/mbostock/3019563
Storyboard Control: http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
dimple.chart:
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart#methods-1
Create Data Visualizations in JavaScript using Dimple and D3:
https://www.sitepoint.com/create-data-visualizations-javascript-dimple-d3/





