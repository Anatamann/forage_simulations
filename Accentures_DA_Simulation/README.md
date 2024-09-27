# DA and Visualization by Accenture
*Summary*: An ad-hoc analysis of Social Buzz which is a rapidly growing social media platform. The clients have a specific request to find the **top 5 category of the platform** along with two other requests related to Data practice and business opportunity.

## Executive Summary
1. 16 content categories in total on the platform currently.<br> 
2. Top5 categories of the platforms are *animals, science, healthy-eating, technology, food.*<br>
3. Healthy content ratio in all 16 categories.<br>
4. The difference between 1st and 2nd top categories is 1.1% while other categories share a difference of <1%.<br><br>
***Suggestions**: Focus on maintaining a healthy ratio of all the content categories on the platform by algorithm adjustments.<br>
Build a better company-user relationship around healthy-eating / food sector.*

### Resources 
Three data sets:<br>
1. Content.csv<br>
2. Reaction.csv<br>
3. ReactionTypes.csv<br>

*Content table* comprises of *1000* rows with contentID, ContentType & Category columns.<br>
*Reaction table* consists of *25553* rows of user reaction data.<br>
*ReactionTypes table* contains the *reaction score* of each reaction types(16).<br>

### Steps
1. Cleaned the data of all the tables
2. Created a DataModel for analysis
3. We deduce the Top 5 categories of the platform
4. Presentation to the client<br><br>
#### Data Model
<img src="Screenshots/DataModel Screenshot.JPG">

### Final Insight Summary
Platform has a total of **16 categories** and out of which the **top5** category analysis revealed that the highest engaged content is mostly **real life and factual based contents**. 

The distribution is quite healthy among all the 16 categories but after analyzing one level deeper into the top5 categories we found that the 1st category is tailing away from other categories which can result into a monotonous experience for the other user base on the platform. 

Top5 categories also consists of two food realted contents namely *food* and *healthy-eating* which can be an indication of health concious users on the platform.

### Suggestions Summary
*Algorithm adjustment to mantain a healthy ratio of contents among all category on the platform* such that one category don't dominate the whole platform.

Suggested that the platform should *do some promotional events or sponsoring the contents related to food and healthy-eating for better platform-user relationship*.
