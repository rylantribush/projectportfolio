# Rylan Tribush
### Data Analytics Portfolio Project: Swire Cola-Cola

## Summary

Home Credit Group seeks to provide home loans to currently underserved communities, but it only wants to give loans to potential clients with the ability to repay. It is difficult to predict if someone with a limited credit history will be able to repay a loan. Therefore, the overall purpose of this project is to develop a model to predict whether an applicant will repay, based on historical data. The outcome variable is binary, so this is considered a supervised classification problem. The data set and the original case competition on which this business problem is based can be found at Kaggle.com. For this project, I worked with fellow MSBA students Ahsan Ahmed, Raunak Sharma, and Scott Silverstein. 

## Solution

After a lot of time working with the data and testing different machine learning models, our group settled on an XGBoost classification model. Our final model has strong predictive performance, which is reflected in an AUC score of .76 on the Kaggle testing data. Download the modeling notebook to see the details.

## Contribution

Our group divided the work pretty equally among the four members. We tried to split up the components of the project in a way that matched our different interests and strengths. I was the one who developed our final model with the highest AUC score. Additionally, I did most of the work organizing and formatting the presentation slides and generated the majority of the final visualizations.

## Business Value

Home Credit is committed to providing a safe borrowing experience to the unbanked population who don't have access to traditional loans are often taken advantage of by lenders. Our solution will help Home Credit accomplish its mission of increasing financial inclusion by allowing it to better predict which potential customers will and will not have difficulty repaying a loan. Our model also provides Home Credit the flexibility to balance the tradeoff between false positive and false negative costs by changing the decision threshold in response to economic and interest rate changes. Given the high costs of mortgages today and the large scale of Home Credit's lending business, even a small increase in predictive accuracy has the potential to generate millions in profit and improve the borrowing experience of thousands of customers. 

## Difficulties

The biggest issue that our group encountered was lack of time. Most of us had full time jobs and a full class schedule, so it was difficult to find time to meet and work on the project. Besides that, we ran into the normal differences of opinion and communication issues that are typical of group projects. Overall, I think we worked well together and I am proud of our results.

## What I Learned

I learned a lot over the course of this project. Before starting this project, I had only used a couple of data mining algorithms on simple toy datasets. Here I had to figure out what to do when there's a lot of messy data and no clear outline of what to do. I had also never given a presentation about data analytics or used Github. Now I feel a lot more confident about how to approach an open-ended analytics project to achieve valuable results. 
