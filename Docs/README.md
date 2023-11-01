# Predicting Customer Service Requests
## Introduction
High-speed internet is so essential to the way we live, work and play that we can’t imagine a world without it. Remote working, learning, social media and streaming couldn’t be possible without a stable connection. But end users living in rural or underserved areas face a tremendous disadvantage: fast internet access is either unavailable or unaffordable. No matter what stands in the way of availability, you hold the key to bringing more reliable internet to customers and communities across the country—and to helping close the digital divide.
<br/><br/>How? By building digital equity through a fiber-based network. This means everyone has equal access to:
- High-speed connectivity regardless of location or other geographical circumstances.
- Resources and services that increase digital knowledge and skills.
- New internet technologies without needing to move away from communities they know and love.
<br/>By taking advantage of an advanced, existing fiber network, you can better serve your end users with the access they need—the moment they need it.
## High Level Network Architecture
![Alt Figure above depicts the high-level network architecture for fiber broadband service. It is a typical two-layer architecture: 1. Access layer (OLTs), 2. Aggregation (BNGs).](network.png)
>Figure above depicts the high-level network architecture for fiber broadband service. It is a typical two-layer architecture: 1. Access layer (OLTs), 2. Aggregation (BNGs).

Fiber customers are served by Optical Line Terminals (OLTs). Broadband Network Gateways (BNGs) aggregate OLTs to make sure transport network resources are efficiently utilized. The theory behind the aggregation layer is that statistically not all customers will use broadband service at the same time, hence allowing service providers to take advantage of statistical multiplexing gains.
</br></br>Network performance metrics must be collected continuously to know how the network is performing and to identify anomalies, and to determine root causes for the problems, preferably before customers’ service is affected. 
</br></br>In this network architecture, a customer is identified as follows (network identifier):
![image](object.png)
- Shelf Name: OLT CLLI
- PONx: PON port on the OLT
- ONTx: Customer on that PON
</br></br>Every subscriber data set must be associated OLT, PON, so that questions related to those can be answered. 
## Problem Statement
Network performance metrics are being collected for fiber broadband services. From time to time, customer services are degraded and require service repairs. This could be because of many factors such as equipment malfunction, weather events, physical impacts on fiber. Proactively detecting service degradation and resolving those issues are preferred for an excellent broadband service. Predicting service repair requests from network performance metrics is the challenge.  
</br></br>**Participants are expected to develop a predictive model to predict if customer fiber service is in need of service repair.**
## Data Explanation
Time series of performance measurements for a month are provided as training and test data. Training data and test data do not overlap. Data duration for training data is one month. The data duration of the test data is one month. There are ten thousand customers in the training data. There are ten thousand customers in the test data. Customers in training and test data are not necessarily the same. 
Service repair requests are happening in the second half of the month. 
## Model Evaluation Criteria
A model is to predict if a customer service needs a service repair in the second half of the month, i.e., 16th or later. If a customer service needs more than one service repair, the label is till 1.
Each model will be evaluated based on:
- accuracy
- comprehensive exploratory data analysis,
- insights uncovered from the data,
- innovative approach,
- inspection of final executed notebook.

## Scoring
For accuracy validation, a csv file as shown below must be emailed to milad.mostavi@ftr.com. The csv file should include all customers in the test data.

|Customer |Service_Repair |
|---------|:---------------:|
|1232131|1|
|2343556|0
|3487534|0
|9562949|1
|1252712|0

<mark>Cautionary Note</mark>
<br>This is a hard problem. If your model is no better than flipping a coin, **_do not get discouraged_**. How you approach the problem, how you analyze the data are also very important.