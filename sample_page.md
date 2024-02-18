#  A/B Hypothesis Test Analysis

## Summmary 
This report aims to describe in detail the findings of A/B hypothesis test which was designed to compare the two versions of webpage. The new version of webpage has been created to increase awareness about newly introduced food and drink offerings. The objective of this action is to increase revenue. The test involves addition of banner of products in food and drink category at the top of website.
The way control and treatment group will see the webpage is shown below:
<img src="images/Project1/webpage_summary_1.jpg?raw=true" width="900" height="500" />
Users will be randomly assigned to both groups.  

### Data
To extract GloBox data, we made an SQL query and subsequently conducted analysis using Google Sheets and Tableau. The query and associated tasks in Google Sheets can be found appended to the conclusion of this document. We examined the following variables:
- User id
-	Country
-	Average amount spent
<p align = "center" width="100%">
<img src="images/Project1/Data_image_amount_spent_by_gender_2.jpg" width="500" height="400" />
</p>
<p align = "center" width="100%">
<img src="images/Project1/Data_image_amount_spent_by_device_3.jpg" width="500" height="400" />
</p>

-	Gender
<p align = "center" width="100%">
  <img src="images/Project1/Total_users_by_gender_4.jpg" width="400" height="300" />
</p>

-	Device
<p align = "center" width="100%">
<img src="images/Project1/Total_users_by_device_5.jpg" width="400" height="300" />
</p>

- Group
<p align = "center" width="100%">
<img src="images/Project1/Total_users_by_group_6.jpg" width="400" height="300" />
</p>

-	Converted Users
<p align = "center" width="100%">
<img src="images/Project1/Converted_users_by_group_7.jpg" width="400" height="300" />
</p>

<p align = "center" width="100%">
<img src="images/Project1/Converted_users_by_device_8.jpg" width="400" height="300" />
</p>

<p align = "center" width="100%">
<img src="images/Project1/Converted_users_by_gender_9.jpg" width="400" height="300" />
</p>


### Test parameters
To assess the potential impact of the new webpage design, I'll examine the following variables:

-	Conversion rate
If the user makes one or more purchases after joining the experiment, it would be considered as conversion. 

-	Amount Spent
Average amount spent by users from both group is considered to investigate whether new web design contributes to increase in revenue or not?
### Analysis
The hypothesis testing A/B and confidence interval calculation will be performed on both variables conversion rate and amount spent. 

<p align = "center" width="100%">
<img src="images/Project1/Conversion_rate_group_wise_10.jpg" width="400" height="300" />
</p>
The above figure has shown that there is difference in conversion rate between both groups. The difference in bar lengths can be seen. Our analysis aims to determine whether this difference signifies a significant relationship between the new webpage design and Group B.

**Hypothesis Test**

Null hypothesis states that there is no difference in conversion rate between both groups. And alternative is that there is difference in conversion rate between both groups. The difference in conversion rate among control and treatment group is not zero.
  H_0: p_2-p_1=p_0  or p_1= p_2
  H_1 : p_2-p_1<>p_0
Where:
p_1 = conversion rate for control group A
p_2 = conversion rate for treatment group B

**Test details**

<ins> Two sample z test with pooled proportion (Two tail test) </ins>

Two sample z-test with pooled proportion is used because in Null hypothesis we consider difference in conversion rate to be zero. Hence, we have assumed that variance of two populations is same. The pooling is related to the estimation of standard error. In this pooling version of z-test both proportions are averaged and only one is used for calculation of standard error.
Test statistic  T=  ((p ̂_1-p ̂_2 )-p_0)/√(p ̂(1-p ̂)(1/n_1 +1/n_2 ))
P value = 2*P(Z> |T|) = 0.0001117008208
 Where:
- H_0,H_1=Null and alternative hypothesis 
- p_1,p_2=population proportions
- p_0= null value,the value we think the difference in population proportions might be
- p ̂_1,p ̂_2= sample proportions for samples 1 and 2,respectively
- p ̂ = the pooled sample proportion
- T = T statistic
- n_1,n_2=  sample size for samples 1 and 2
- Z = the standard normal distribution



```javascript
if (isAwesome){
  return true
}
```

### 2. Assess assumptions on which statistical inference will be based

```javascript
if (isAwesome){
  return true
}
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
