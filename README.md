# Telecom Customer Churn Analysis Using Python

I did an analysis of Telecom Customer Churn Analysis through Python Libraries (Pandas, Seaborn).

![image](https://user-images.githubusercontent.com/72240938/232255659-1e8fea4e-22fd-4a5c-96d1-61424a893520.png)


#### [Link to Dataset](https://drive.google.com/file/d/1L_0EhArWRIvEg8oZ7jfWgP-mu8MciJhk/view?usp=share_link)

### Tool Used: PyCharm

### Major questions with respect to the dataset are as follows:
* What are the key drivers of customer churn?
*  What customer profile is churned, stayed, and joined? Are they different?
*  Is the company losing high-value customers? If so, how can we retain them?


I divided the analysis into 4 sections for the analysis purpose:
First of all, I answered the major questions through Sections 1 and 2.
Then, further did some analysis in sections 3 and 4.

First of all, loading the dataset via the following command and removing records containing null values:-

![image](https://user-images.githubusercontent.com/72240938/232255017-5ead1df7-9dad-45d0-a270-56666c296ad3.png)

## Section 1:
## Information regarding customer profile and churn status.

Based on the following parameters, I performed the analysis:
• Contract
• Offer Type
• Age Range
• Internet Type
Whereas other factors were there for analysis, though I found these parameters which affect the most among those.
Here, via Pivot Table I did the calculations:

## Contract Vs Churn Status:

#### Code:
![image](https://user-images.githubusercontent.com/72240938/232255218-21e8e8af-9222-440b-a36d-8261ef7bbdae.png)

#### Output:

![image](https://user-images.githubusercontent.com/72240938/232255225-70561876-007d-4dca-bcad-48eac3715c4b.png)

## Offer Type Vs Churn Status:

#### Code:

![image](https://user-images.githubusercontent.com/72240938/232255268-718cb69c-49bc-4d9f-8514-c00acf04abce.png)

#### Output:

![image](https://user-images.githubusercontent.com/72240938/232255274-6ff75796-e552-43d0-a7a6-5cba8e2b1cfd.png)


Similarly, I did for other parameters too.

### Insights:

Here is this table showing the customer profile showing churned, joined, and stayed based on the most count among them:

![image](https://user-images.githubusercontent.com/72240938/232255321-8ae2d2da-3f29-4625-aca0-5522d985827d.png)


Additional count of Churn Reason:

#### Code:

![image](https://user-images.githubusercontent.com/72240938/232255331-ff21f918-36f8-4daa-9887-7bc3ee25e6d2.png)

#### Output:

![image](https://user-images.githubusercontent.com/72240938/232255340-a0ccaae4-b1be-4df8-ad34-1705e8e3948c.png)


## Questions Answered*********************************************************

#### ➡️ (i) Ans:
Key metrics of customer churn  are based on the Contract, Age Range, Internet Type, device quality, and attitude of support person.
### ➡️ (ii) Ans:
From Table 1, we can get an idea of customer profile churn for categories that stayed, churned, and joined overall they are different from each other mainly, but some of them are the same.


## Section 2:

Finding high-value customers based on certain parameters:
• Contract
• Offer Type
• Age Range
• Internet Type
• Gender


### Internet Type Vs Avg Total Revenue

#### Code:

![image](https://user-images.githubusercontent.com/72240938/232255374-e584c7bf-c5ce-452b-a0fc-5ce3d20ce578.png)

### Output:

![image](https://user-images.githubusercontent.com/72240938/232255424-279b5cee-bfd7-4f76-b3d1-8046b3ff00db.png)


Similarly, I did for other parameters too.

#### Insights:
Here is this table showing the high-value customers based on the following parameters:

![image](https://user-images.githubusercontent.com/72240938/232255463-473a6f82-458f-4430-9612-02b7de032766.png)

### Questions answered ****************************

(iii) Ans:
Yes, the Company is losing high-value customers based on the insights from Table 1 and Table 2.
They are mainly on the parameters:
Age Range
Internet Type
For retaining them, customers could be invited to give some sort of feedbacks for the parameters where the churn is high and discuss it.
Based on these feedbacks, telecom company should take necessary actions.



## Section 3:

Some condition and numerical-based questions:
1. Find the average of average monthly GB download with respect to different age ranges
Ans:
#### Code:

![image](https://user-images.githubusercontent.com/72240938/232255537-a9d1967c-d909-4ef9-88e5-1fa262a15b29.png)


#### Output:
![image](https://user-images.githubusercontent.com/72240938/232255541-ab4b4aec-00f4-4499-9fb4-dd50169218ef.png)

2. Find the sum of total revenue generated when the customer has taken unlimited data and Online security service.
Ans:

#### Code:
![image](https://user-images.githubusercontent.com/72240938/232255557-8a90748d-f35d-45c7-ae83-a3e27458c3b6.png)


#### Output:
![image](https://user-images.githubusercontent.com/72240938/232255568-406a5e19-f373-45cd-bd77-cfe140230b68.png)


## Section 4:

Distribution plots across some variables:
1. Find the total revenue distribution for different contract types.

#### Code:

![image](https://user-images.githubusercontent.com/72240938/232255583-39240419-2232-4d0b-b747-c956a0044084.png)


#### Output:

![image](https://user-images.githubusercontent.com/72240938/232255591-c22365e3-909c-4c3b-b800-83163409df96.png)



2. Show the distribution of age across the total revenue generated.
Ans:
#### Code:

![image](https://user-images.githubusercontent.com/72240938/232255594-e6b36f27-bf52-4f49-98df-a3f3bb4f4006.png)


#### Output:

![image](https://user-images.githubusercontent.com/72240938/232255599-4926f2d1-62f5-43c5-a40f-147d7e63d416.png)



### Key insights and questions answered are as follows:

* Key drivers of customer churn are based on the Contract, Age Range, Internet Type, device quality, and attitude of the support person mainly.

* Customer Profile Churn for categories that stayed, churned, and joined overall are different from each other mainly, but some of them are the same

* Yes, the Company is losing high-value customers based on the insights.
They are mainly on the parameters: 
•  Age Range
• Internet Type  

For retaining them, customers could be invited to give some sort of feedbacks for the parameters where the churn is high and discuss it.
Based on these feedbacks, telecom company should take necessary actions.

##### About 23% of overall revenue could be retained if these high-value customers "stayed" 




























































































































































































































