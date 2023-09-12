# Power-BI-CRM-RFM-Dashboard
The data, content, and final delivery I shared on GitHub utilize mock-up data due to confidentiality. This work sample aims to demonstrate my analytical skills, problem-solving approach, and the lessons I learned from the case.

### Table of contents
* [1. Introduction](#1)
* [2. Specifications](#2)
* [3. RFM Dashboard Proof of Concept](#3)
* [4. Dataset](#4)
* [5. Model Simulation](#5)
* [6. Results](#6)
    * [Proof of Concept Dadhboard Design](#6.1)
    * [Dashboard Highlights](#6.2)
    * [Lesson Learned](#6.3)

<a id="1"></a>
### 1. Introduction
XYZ Bank is a prominent financial institution with over 1000 branches spread across Canada. The bank's management aims to gain insights into customer loyalty and their sales contributions through RFM methodology-based segmentation. They seek a robust, long-term production solution to assist the Business-CRM Services department in enhancing profitability and increasing customer loyalty. This solution will involve conducting an analysis using the recency, frequency, and monetary (RFM) methodology to segment customers, allowing for targeted Campaign Planning & Design based on the results.

<a id="2"></a>
### 2. Specifications
**Name:** XYZ CRM RFM Analysis Dashboard BRD, Dashboard design spec, data model<br />
**Description:** XYZ Customer contribution base on RFM methodology to identify target customers for future campaign planning and implementation.<br />
**Language(s):** English<br />
**Owners/Requester:** XYZ management<br />
**Audience:** Business – CRM Department<br />
**Security Parameters:** ALL Executives

<a id="3"></a>
### 3. RFM Dashboard Lifecycle
<img width="805" alt="238653169-83047e77-a0b1-4bf5-95cc-ed5a4f3e461a" src="https://github.com/hilxwang/Power-BI-CRM-RFM-Dashboard/assets/96967687/537bd4ce-65ee-404c-9a93-4bab72c41f0b">


<a id="4"></a>
### 4. Dataset
The analysis incorporates five datasets, comprising of three source data and two data mart data. Besides, to identify the target customers and their sales contribution by segment, the analysis will exclude transactions related to transfers, taxes, bills and utilities, mortgage and rent. <br />
<br />

#### Source Data:
**BusinessCase_Accts:** This dataset contains comprehensive information about accounts, including branch number, type, open date, ID, balance, currency, and customer ID.<br />
<br />
**BusinessCase_Custs:** This dataset provides customer-related details such as ID, gender, birth date, work activity, occupation, total income, habitation status, and school attendance.<br />
<br />
**BusinessCase_Tx:** This dataset plays a significant role throughout the analysis and includes information on transaction descriptions, currency amounts, origination date-time, customer ID, merchant ID, account ID, and category tags. The transactions occurred between March 1, 2018, and November 1, 2018. <br />
<br />
#### Target Data:
**RFM SCORE:** This dataset represents the filtered and calculated values derived from the original transaction data using the RFM methodology. It includes columns for customer ID, recent purchase date, monetary value, and frequency.<br />
<br />
**Segmentations:** This dataset is designed to assign names and descriptions to each segment based on different R-F-M scores. It provides information on the R-F-M score, segment name, description, and sorting. 

<a id="5"></a>
### 5. Model Simulation
<img width="996" alt="238670958-6b6bc064-ef9e-4ec8-ac07-ea052b01ade8" src="https://github.com/hilxwang/Power-BI-CRM-RFM-Dashboard/assets/96967687/b0ed62c0-29e5-4771-8cf1-4c3d34f6d054">


<a id="6"></a>
### 6. Results
<a id="6.1"></a>
### Proof of Concept Dadhboard Design:
![CRM-FRM](https://github.com/hilxwang/Power-BI-CRM-RFM-Dashboard/assets/96967687/06fdc46f-463f-464b-8230-56e21264de6c)

<a id="6.2"></a>
### The dashboard highlights two essential components: <br />

**Matrix:** Positioned in the left corner of the dashboard, the matrix serves as a valuable tool for the marketing team, providing tailored support in executing effective campaigns.<br />
<br />
**R-F-M Score:** By expanding the R-F-M (Recency-Frequency-Monetary) column, the marketing team gains access to customer names and email addresses. This enables them to implement targeted campaigns, ensuring personalized communication with specific customers.<br />
<br />
<a id="6.3"></a>
### Lesson learned: <br />
The key lesson learned from the case is the importance of customer segmentation and targeted marketing startegies. By utilizing RFM methodology and analyzing customer data, the company was able to identify different customer segments based on their recency, frequency, and monetary value. This segmentation allowed for personalized and targeted campaign planning, resulting in improved profitability and increased customer loyalty. The case study demonstrates the significance of leveraging data-driven insights to enhance marketing effectiveness and drive business growth.
