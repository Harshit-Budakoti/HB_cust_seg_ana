CLUSTER SEGMENT ANALYSIS ![](Aspose.Words.5fda3a16-96a3-489b-b334-1bc98935de2b.001.png)

REPORT

Elaborate Description of 2 cluster segments constructed by K-Means

on Dataset Reduced to 3-dimensions using PCA.

CLUSTER 0  CLUSTER 1

Common  Premium Customers Customers

CLUSTER 0 ![](Aspose.Words.5fda3a16-96a3-489b-b334-1bc98935de2b.002.png)

Cluster 0 : Common Customers

1) Mostly the TOTAL TRANSACTION AMOUNTS are smaller. 75% quantile of TOTAL\_TRANSCTION\_AMOUNTS of this cluster  equates to just an AVERAGE TRANSACTION AMOUNT From CLUSTER 1.

   But the upper limit outlier transactions are at par with top transactions of CLUSTER 1 although lesser in frequency when compared to CLUSTER 1.

2) Far Lower in terms of Credit-Limit.
2) Age :Wider Customer Age spread although most of the customer are in age bracket of 30-60.
2) Months on Book : Anywhere between 10 months-60 months
2) Dependents : Highly Variable but mostly 2-3 dependents for an average customer.
2) Education : A high proportion of customers are Graduates and High-School passouts.
2) Income\_category : Mostly earn less than $40K or earn in the range of $ 40K -$60K. 

`   `This corresponds to Lower-to Middle Income Group

8) Total relationships : Customers in this category are highly probable 3-7 relationships with the credit card company.    These are customers involved in a lot of other services of the company.
8) Average Utilization Ratio : For lower spending customers mostly it is 0 (zero credit utlization)

   `                                `or nearly 0.6. Hence these customers have LOW CREDIT SENSE and SCORE.

`                              `Among the high spending customers it is in the range of 0.3-0.4 (better).

10) Attrition Flag

`   `Most of the attrited customers are from this cluster with total transactions amount less than $5K for most cases and nearly $8K-$10K for a few cases.

`   `Among existing customers from this cluster typical transaction amounts are nearly $5K and in some case $15K also.

11) Gender 

`   `Nearly all the females lie in this cluster and typically have total\_transaction values under $5K and    $15K at a few instances. 

`   `The Males lying in this cluster exhibit nearly the same characteristics as the females in this cluster.

12) Revolving Balance : For low-spending customers it is typically either 0 or $1500. And it was    nearly $1500 -$2000 for high spending customers(which are exclusively attrited female in this cluster).
12) Months inactive : Mostly 3 months but may be higher than that. 
12) Avg Open\_to\_Buy: Mostly lesser than $5K for both high-spenders and low-spenders and strictly less than $20K.
12) Total Amount Change ratio : mostly 0.7 ; in range of 0.3-1.17.  High spenders maintain it at nearly 0.7. 

    `     `Quarter-4 is likely to have slightly lesser amount as compared to Quarter-1 in most cases but some customers with lower transaction amounts spend more in Qtr-4.

16) Higher Attrition rate in this Cluster : 16.5% from this cluster are Attrited\_customers.
16) Marital Status : Divorcees spend nearly $5K- $7K(max). Whereas Single and Married low spending customers spend $5K but others may spend as high as $15K. 

|CLUSTER 1|
| - |
|<p>Cluster No. 1: Premium Customers</p><p>1) Higher in terms of Total Transaction amount in the credit cards.</p><p>2) Way Higher in terms of Credit-Limit. </p><p>`    `These are Exclusive members who are given particularly high credit limit.</p><p>3) Age-Group : 30-60 years with a majority of customers in middle-ages(40-50).</p><p>4) Customers who have 20-50 months on book. Typically Higher Transaction limits</p><p>5) Dependents : Mostly 2-3 dependents on the customer akin to Cluster no. 0.</p><p>6) Education level : Mostly Graduates or High-School graduates akin to Cluster 0.</p><p>7) Income-Category: Mostly customers earn $120K+ followed by customers in $80K-$120K bracket. Upper-Mid to High Earning Customers.</p><p>8) No. of Relationships with company : Varies but mostly 2-3. Involved in lesser no. of services offered by the company.</p><p>9) Utilization Ratio typically lower. Mostly 10 % utilization ratio but strictly less than 20%.</p><p>`    `This corresponds to people with high credit score.</p><p>10) These are mostly Existing Customers; mostly spend $3K-$5K but there is also a smaller proportion of big spenders who spend $15K+</p><p>11) Lower Attrition rate in this Cluster : Only 12.96 % from this cluster are Attrited\_customers.</p>|
|<p>12) Gender Ratio : Females constitute only 9\.45% of this Cluster\. Hence 90+ % are males</p><p>14) Revolving Balance: Average customer or even the High-spenders either have no Revolving balance OR  Revolving balance in the range : $500 -$1500 </p><p>15) Months inactive : Customers are mostly likely to be inactive for 1-3 months. Not more than that</p><p>16) Average Open to Buy ratio: Avg(Current Balance - Credit-Limit) </p><p>`    `Average Customers have this ratio greater than $10K. Only Top Spenders have avg. open to buy ratio less than $10K.</p><p>17) Total Amount Change ratio (Q4/Q1): mostly 0.6 ; in range of 0.4-1.0. </p><p>`    `Quarter-4 is likely to have slightly lesser transaction amount as compared to Quarter-1.</p><p>18) Marital Status : Divorcees spend at max $5K. </p><p>`      `Whereas Single and Married low spending customers spend $5K but others may spend as high as $17K. </p><p>`      `Single and Married customers transaction distribution is nearly identical.</p>|
||

