# Final Project: Report

For this project, my partner and I were given a synthetic data set made by IBM. The data used for this project depicts a hypothetical telecommunications company. The data, license, and documentation are provided by Professor Engler’s link to IBM’s GitHub repository. Before beginning our data analysis my partner and I found it beneficial to do some research on popular telecommunication companies such as AT&T and Verizon to better understand the real-world applicability of this assignment. Understanding how churn impacted companies gave us better insight as to how we should analyze our data to aid in the reduction of churn for our hypothetical company. Churn refers to the act of a customer no longer paying for service. Wrangled data will have additional nominal data type in the form of “yes” or “no” for Churn. We expected price to play a large role in the churn, but we were interested in exploring other attributes and how they affected churn. The data provided will be used in our analysis to identify customers at risk of churn in order to propose a solution to limit churn.

The research question my partner and I hoped to answer was which attributes affect churn, and how can we minimize churn. We hypothesized that customers on a month-to-month contract with low tenure will have a higher churn rate because they were not with the company long enough to deem the services any better than another telecommunications company. The selected method of analysis is to perform a statistical test on the data because we believed a statistical test that searches for variance in the data could aid in understanding more about why clients switch services. Before conducting our analysis, we expected there to be specific eye-catching discrepancies in the data between clients who are still paying for the service and clients who are no longer paying for the service. Some thoughts we had are as follows.
1.) There could be a higher income for when churn refers to yes because the higher income means people are able to pay off their phone plans.
2.) The contract length could hinder customer loyalty due to the idea that if people are bound to longer plans and wish to get a new phone they would need to cancel and or pay off their plan therefore resulting in churn being equal to ‘yes.’
Potential implications of our work would be that onboarding will ensure new customers and those in early tenure maintain a belief that services are worth the price. Monthly surveys will help monitor customers and allow for company to mitigate dissatisfaction prior to churn in the early months. Better onboarding, monitoring customer satisfaction, and providing loyalty rewards will result in less churn and maintain steady revenue stream. Providing contract plans that deliver better rates to customers who choose yearly contracts over month-to-month contracts will make customers more inclined to stay with the company longer than the 20-month zone where churn is most prevalent.

We decided to use a statistical test to depict graphs that would show how certain attributes affected the churn rate in customers. We also depicted a decision tree that would show the likelihood of each attribute affecting the churn. Our first step was implementing the necessary modules and libraries needed to accurately perform the tests for this dataset. We then read in the CSV file that contained all of the data we would be studying, and sorted data set by churn, this made it, so our data table showed all churn = “no” together and all churn = “yes” together. After we sorted our data, we presented a bar graph to show churn = “no” and churn = “yes.” We then moved forward and tested certain attributes of the data, the first one being contract length. Based on this analysis alone we decided that the majority of the customers churning are on month-to-month plans resulting in the highest percentage of churn = “yes.” The next attribute we decided to test was the monthly charges in dollars. This test concluded that the majority of the churn = “yes” occurs when the price per month reaches 65 dollar all the way until 110 dollars. This made my partner and I briefly consider ways to lower the monthly costs for customers, however we did not want to act on this until further tests and analysis had been done. In block seven we depict the analysis using a line graph again evaluating the attribute tenure in months. We found that churn = “yes” occurs up until the 20-month length then stabilizes. The way this data looked made my partner and I curious as to how this period of zero to twenty months affects churn. We decided to move forward focusing on this attribute. In block eight we produced a scatter plot showing tenure as a factor of churn. We then moved forward using our statistical test to perform linear regression. In block nine we used code provided to us in a template found under the files section of our class. This block initiates the training of our data so that we can use it to perform linear regression. We then show a binary linear regression where churn = “no” is equal to zero and churn = “yes” is equal to one. Following the same process using the template code in blocks thirteen through fifteen to produce a mean linear regression showing negative correlation. The rest of our code depicts a decision tree. The decision tree is a type of model that displays an algorithm that only contains conditional control statements. Our decision tree was created in a Top-Down Approach, versus a Left-To-Right Approach, for the dataset that was fed during the training. The nodes in the tree described the various test cases with regards to the attribute ‘tenure.’ The type of decision tree was a Classification Tree since we were using a discrete categorical target variable of ‘Churn’ (y variables in code were commented as target variables) to help predict churn based on tenure. The model was created using python and the predictions used a test dataset that was 25% of the total dataset. The remaining 75% of the dataset was assigned as TRAIN data. The decision tree classifier was fit on the TRAIN attribute TENURE and the TRAIN target, or label, CHURN (YES / NO) so that the trained classifier/model could be used to predict CHURN of the TEST data for attribute TENURE. Said another way: The model was trained using the training sets via the FIT function. Applying our trained model to predicting churn based on tenure resulted in an accuracy score of 75.8% for the test data.
  
  My partner and I’s proposed solution would be to analyze the data and determine which attribute affects churn the most. Since churn is affected by the tenure in earlier months, we needed to find a way to combat this so that our telecommunications company does not lose revenue. We feel providing more customer support during the earlier months of service will help our company make a human centric approach to reducing churn and keeping clients. Since churn is clearly occurring in the earlier months of a customer’s plan, we must understand why customers are choosing to leave. Providing surveys for customers to give feedback will also help the process of understanding why churn is occurring before the end of the clients first two years with our telecommunications company. This proposed solution is fair because it considers the users as well as the company at large. The company’s goal is not only to serve customers, but also to maintain revenue. If we make the customers experience more user friendly the customers will in turn be more satisfied giving them less of a reason to churn. The solution considers the finances of the customers by offering customer service lines to aid in the customers overall experience free of charge. As a company the analysis of this data is important because it will give us insight as to why customers are leaving. Testing this proposed solution will prove to be beneficial because after two calendar years we will be able to see whether the churn rate went down or up due to changes in customer service.
  
  The project helped my partner and I learn more about how to analyze data for business decisions. We were able to learn how our decisions as data scientists/analysts could impact not only our company at large but also the clients our company serves. We learned valuable tools on how to benefit customers without hindering our company’s revenue. We also learned how despite how the data looks certain attributes could be affecting the churn more than we originally assumed. This helped us learn more about data visualization and this tool will be beneficial as we move forward in our academic and professional careers and endeavors. We also learned how to make the most out of provided resources and use them to learn how to code better and more efficiently.
