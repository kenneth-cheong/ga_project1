# Problem Statement
There has been a change several changes in the participation rates in both the SAT and ACT exams between years 2017 and 2018. This report seeks to explore the reasons for the these changes within the U.S categorized by states. The report also aims to make recommendations to the College Board for strategies to improve participation rates in Ohio.


# Executive Summary

### 2017 Data Import & Cleaning
Errors such as extra characters were rectified and percentages were removed to convert all numerical data in numbers with decimal points. 

### 2018 Data Import and Cleaning
Data was found to match the data fields of 2017's data. The cleaned-up data from both 2017 and 2018 were combined to a single data frame for the ease of comparison. 

### Exploratory Data Analysis
The standard deviation for each numerical variable were calculated using three different methods. The highest and lowest states were identified in terms of participation rates and scores. 

### Data Visualization
Histograms, boxplots, heat maps and scatterplots were used to investigate the data and correlations further. 

### Descriptive and Inferential Statistics
Most of the statistics have a close-to-normal distribution. Although the data points add up to more than 30, more data points would further ensure a closer-to-normal distribution for the numerical variables used in this report. 

### Outside Research
Research has been undertaken from the official State Education Departments and other related articles. Some of these include the details of state policies with regards to the compulsory taking of the exams and/or the sponsoring of test fees. 

### Conclusions and Recommendations
State departments of education play a pivotal role in increasing the test participation rates. This can come in the form of state subsidies for the test or making the taking of the test mandatory for all school students. The states of West Virgina, Ohio, Rhode Island and Illinois are examples of such policies which greatly impacted SAT participation rates. The SAT Test Day, which happens on a regular school day also contributed to an increase in the overall SAT participation rate. 

Focus on collaboration with state education departments, colleges and high schools would likely lead to the continued increase in SAT participation rates. 

More research can be done on university admissions criteria in the U.S, SAT test centers and their usage to helps understand how to further drive participation rates. 



# Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*string*|ACT/SAT|The state in the United States of America.| 
|**sat_participation or act_participation**|*float*|ACT/SAT|The percentage expressed as a float on the number of students enrolled in schools|
|**sat_reading_and_writing**|*float*|SAT|The average English reading and writing score in a maximum score of 800.| 
|**sat_math**|*float*|SAT|The average math score in a maximum score of 800.| 
|**sat_total**|*float*|SAT|The combined score of sat_reading_and_writing and sat_math.| 
|**act_english**|*float*|ACT|The average math score in a maximum score of 36.| 
|**act_math**|*float*|ACT|The average math score in a maximum score of 36.|
|**act_reading**|*float*|ACT|The average reading score in a maximum score of 36.|
|**act_science**|*float*|ACT|The average science score in a maximum score of 36.|
|**act_composite**|*float*|ACT|The average score calculated by the 4 ACT scores of each state.|


# Conclusions and Recommendations
#### Key Takeaways

Based on the data, major movements in participation rates are spurred on by the state department of education's policies. If a state were to mandate a requirement for all students to take a particular test, the participation rate for the rate would increase exponentially. From further research, we also found that implementation of such policies are usually met on with high opposition from the competition. 

Ohio state law requires districts and community schools to administer the state-funded ACT or SAT to all grade 11 students. This has resulted in an increase for participation for both ACT and SAT tests. 

Rhode Island has made SAT testing compulsory for all students. This was implemented between 2017 and 2018 and its effects can be seen in the SAT participation, from 71% in 2017 to 97% in 2018.

Illinois, like Rhode Island, has also made SAT testing compulsory for all public high school juniors. This has caused an exponential increase in SAT participation from 9% to 99%. The ACT participation rate was halved during this period. It should be noted that this move by the Illinois State Board of Education opposed this decision and is awaiting the final outcome. 

In West Virginia, the participation for SAT has doubled from 14% to 28% while ACT saw a decrease by 5%. This can be attributed to the education department's implementation of the SAT School Day where high school  students can take the SAT tests on an allocated school day rather than taking in on a weekend and usually at a test center which they do not school at. 

Between 2017 and 2018, 10 states (Colorado, Connecticut, Delaware, Idaho, Illinois, Maine, Michigan, New Hampshire, Rhode Island, and West Virginia) and the District of Columbia covered the cost of the SAT for all their public school students. Three years ago, only three states and the District of Columbia did so. This, and the implementation of the SAT School Day contributed to the overall 25% increase in SAT test-takers. 

As such, the SAT School Day and the cost subsidy of the SAT can be seen to greatly improve SAT participation rates. 

#### Recommendations

Firstly, it is evident that a collaboration with the states' department of education has the highest and most immediate impact on participation rates of a test. This would be in terms of a mandatory test in all schools within the state. 

Having said that, it is also paramount to maintain the working relationships with the states already implementing mandatory tests in their location. This would come in the form of customer service, reliability and efficiency in administering the tests and getting the results. 

Success stories can also be seen in states where the education department subsidizes the full costs of the test, making them more accessible to lower income students. 

Secondly, the college board should explore working with both high schools and colleges. A college's admission criteria based on either of the tests' score would have a huge impact on the perceived value of the test. The value to colleges of a single type of test for the admissions criteria is that they have a single metric which they can rank their applicants by, rather than having to compare their over two sets of metrics. Colleges have also been observed to be moving away from standardized tests. This issue should also be addressed to prove the need for these tests in providing impartial information about their applicants. 


Lastly, further research should be done on the university admissions criteria, the type of test and the scores students have been accepted upon and the composition of students taking both tests. Furthermore, information about the test centers and their usage could also shed some light on the matter. These would help to identify both tactical and strategic targets for College Board to further improve the SAT participation. 
