# NBA-2023-24-Analysis-Project
I along with 2 other classmates Dmitry Sorokin, and Henry Yost went through the NBA's 2023-24 player statistics for our project and along with out background knowledge in basketball made sure to omit any faulty and abnormal data like the one below wihtin our dataset to make sure our further tests will be as accurate as possible. Within our analysis we went through 3 difference categories inlcuding a confidence interval that went along a t test, a linear regression test, and a logistic regression test.

![image](https://github.com/user-attachments/assets/e8f20dcd-31cf-412d-8cad-ee02fca4a469)
![image](https://github.com/user-attachments/assets/d692dc28-7609-4994-ae62-766f8e535cbc)

# Confidence Interval and T Test
When diving into confidence interval we wanted to find the 95% confidence interval between a PowerForward and a Center to then be able to compare our confidence interval tests by asking ourselves if the difference between the two means was statistically signifcant to determine if playing a different position usually done by the tallest people on the team affected a player's field goal percentage. 

After confirming our subset data of just pure centers and pure power-forwards were both approximately normal looking at the histograms and completeing the our tests we came to the following conclusions. 

![image](https://github.com/user-attachments/assets/2681943a-f00d-47c4-afdc-a9df46589005)
![image](https://github.com/user-attachments/assets/f9b4e390-cee0-47b0-b08e-16b480e44de6)

- We are 95% confident a on average a center's fg% will fall between 53.32% and 57.54%
- We are 95% confident a on average a powerfoward's fg% will fall between 44.62% and 48.05%
- We are 95% confident that the difference in means between a center and a power-foward will be between 6.86% and 11.38%, and along with a p value below 0.05 mean that the difference in true means is statiscally signifcant meaning a player's postion does matter when determining their porjected field goal percentage between a pure power forward and center. 

# Multi-Linear Regression

Our goal when looking at linear regression was to predict a player's 3 point attempted by using positon, minuted played, points, offensice rebounds, and defensive rebounds as our final explanatory variables after going through Backward Elimintaion. 

After created 5 different players with different sample values for our explanatory variables our Sum of Squared Residuals came out to be 31.0951 which even though it can be improved by add more variables and comparing our model using forward selection

# Logistic Regression



