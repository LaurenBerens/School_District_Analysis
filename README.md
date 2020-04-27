# School_District_Analysis
Python3/Anaconda school district testing analysis

## **How is the district summary affected?**

The district summary is affected in the charter school types only.  The charter data lowered substantially after updating the reading and math scores for 9th graders at Thomas H.S.  The charter school type overall percentage passing rate of reading and math testing dropped 3%.  Reading and Math passing rate dropped 4% each within the Charter school type.  

## **How is the school summary affected?**

Thomas H.S. overall performance took a substantial hit following the update to the 9th grade data.  The Thomas High School initially had an overall passage rate of 90.9%. Following the update to the 9th grade data at Thomas H.S., this school sat at a 65.1% overall passage rate.  This is a 25.8% drop in overall passage rate by removing 9th grade scores from the data.

## **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?**

The Thomas High School ranking among the other 14 schools was initally 2nd highest scoring school with a 90.9% overall passage rate. Following the update to the Thomas H.S. 9th grade data, Thomas H.S. dropped to 8th place in school rankings with a 65.1% overall passage rate.  The update to the 9th grade testing data make Thomas H.S. drop 25.8% in the overall testing outcomes.  The inaccurate 9th grade data inflated the overall school scores by over 25%.

## **How does replacing the ninth-grade scores affect the following:**

###### * Math and Reading Scores by Grade

The 9th grade math and reading scores were all replaced by NaN from Thomas High School following the data update.  No other grade specific data was affected by this change within Thomas High School.  The overall 9th grade data for all schools was slightly lowered upon amending the data to reflect NaN in the 9th graders testing at Thomas H.S.

###### * Scores by School Spending

There was no change in the amount of money schools were spending per capita due to there being no change in the number of students accounted for.  However, there is an evident change in the overall passing % within the four spending categories by this data adjustment.  In the $630-$644/capita bin, the overall passage rate dropped from 62.86% down to 56.39% following the data update to Thomas H.S. 9th graders.  This is a 6.47% drop due to Thomas H.S. amended data within the spending bin. 

###### * Scores by School Size

All passing rates within the school size bin category of medium dropped 6% across the board following the Thomas H.S. data update.  Thomas H.S. is a medium sized school.  Initially the overall passing percentage for math and reading for medium sized schools was 91% where math was at 94% and reading was 97%.  Upon updating the 9th grade data at Thomas H.S., the overall passing percenage dropped to 85% where math was 88% and reading was 91% passing rate. 

###### * Scores by School Type

Upon reviewing the charter school type, we can see where these overall scores were affected between 3-4% folling the data amendments due to 9th grade Thomas H.S. updates.  Initially, the overall passing rate for charter schools was 90% passing with 97% reading passage and 94% math.  Following the data update, the overall passage rates for charter schools dropped to 87% with 90% math and 93% reading passing rate.  This reflects a 3%-4% drop in passing percentages across the passing categories.
