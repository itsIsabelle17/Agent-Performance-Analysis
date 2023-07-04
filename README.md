# Analyzing Agent Response Attitude in Customer E-commerce Journeys: A Data-driven Approach for Enhanced Customer Satisfaction  

### Project Overview  

The objective of this project was to analyze the response attitude of Agents throughout the customer's E-commerce site journey, starting from their initial interaction to the point of product ordering. The project employed a systematic approach, involving the creation of a dataset through the collection and organization of actual data while assuming the role of dummy customers. The dataset served as the foundation for conducting an in-depth analysis, culminating in the creation of a comprehensive dashboard for result visualization.  

### Data Collection and Organization  

To ensure the accuracy and reliability of the analysis, we adopted a data-driven approach. As dummy customers, we actively engaged with the E-commerce site, simulating realistic interactions. Through this process, we systematically collected relevant data points at various stages of the customer journey. These data points were carefully organized and structured to create a comprehensive dataset, which formed the basis of our subsequent analysis.  

### Thorough Analysis and Insights  

Leveraging the meticulously prepared dataset, we performed a rigorous analysis to gain valuable insights into the Agent's response attitude. Our analysis encompassed various dimensions, including the timeliness, effectiveness, and customer-centricity of the Agent's interactions. By scrutinizing the dataset, we identified patterns, trends, and areas of improvement, enabling us to draw meaningful conclusions and make informed recommendations.  

### Result Visualization through a Dashboard  

To facilitate a comprehensive understanding of the findings, we employed data visualization techniques. Through the utilization of advanced tools and technologies, we created an intuitive and user-friendly dashboard. This dashboard presented the analysis results in a visually appealing and easily interpretable format, allowing stakeholders to grasp the key insights at a glance. By visually representing the data, the dashboard served as a powerful communication tool for conveying complex information effectively.  
(The uploaded image file in this repository displays only a portion of the entire dashboard, and for security reasons, other dashboards are not provided.)  

### Conclusion  

The project successfully analyzed the Agent's response attitude throughout the customer's E-commerce site journey, employing a data-driven approach. By assuming the role of dummy customers and collecting actual data, we created a comprehensive dataset that served as the foundation for a thorough analysis. Through the utilization of a well-designed dashboard, we effectively visualized the results, enabling stakeholders to comprehend the findings and make informed decisions. The project's outcomes provide valuable insights into the Agent's performance, offering opportunities for enhancement and improvement in customer satisfaction.  
<br>

## Detailed Project Description  

In this section, we will outline the customer journey from ordering to product delivery, dividing it into two distinct phases: the Pre-Purchase Phase and the Purchase Phase. The Pre-Purchase Phase involves customer inquiries about products and services of interest to the agent before placing an order. On the other hand, the Purchase Phase encompasses customer queries related to ordering, delivery, and post-order support until the product is received. The analysis included a total of 28 dummy customers, each purchasing different products, such as mobile phones, tablets, watches, laptops, monitors, TVs, projectors, refrigerators, ranges, washers, dryers, dishwashers, and other electrical appliances.


### Customer Journey Analysis: Purchase Stage  

* Introduction:  
During the Pre-Purchase Phase, customers were further categorized into two groups: call evaluation and chat evaluation. Each customer interacted with 14 different agents to assess their performance. Throughout the phone calls and chat sessions, customers asked five questions related to their product of interest, evaluating the agent's proficiency as they progressed through the journey until the problem was resolved.

* Evaluation Criteria:  
The table below outlines the evaluation criteria utilized during the Purchase Stage.  
  * Call:
| Name | Modeling Role | Measurement Level| Description|
| ---- | ------------- | ---------------- | ---------- |
|**ID**| ID | int | unique row indentifier |
| **LIMIT_BAL** | input | float | amount of previously awarded credit |
| **SEX** | demographic information | int | 1 = male; 2 = female
| **RACE** | demographic information | int | 1 = hispanic; 2 = black; 3 = white; 4 = asian |
| **EDUCATION** | demographic information | int | 1 = graduate school; 2 = university; 3 = high school; 4 = others |
| **MARRIAGE** | demographic information | int | 1 = married; 2 = single; 3 = others |
| **AGE** | demographic information | int | age in years |
| **PAY_0, PAY_2 - PAY_6** | inputs | int | history of past payment; PAY_0 = the repayment status in September, 2005; PAY_2 = the repayment status in August, 2005; ...; PAY_6 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; ...; 8 = payment delay for eight months; 9 = payment delay for nine months and above |
| **BILL_AMT1 - BILL_AMT6** | inputs | float | amount of bill statement; BILL_AMNT1 = amount of bill statement in September, 2005; BILL_AMT2 = amount of bill statement in August, 2005; ...; BILL_AMT6 = amount of bill statement in April, 2005 |
| **PAY_AMT1 - PAY_AMT6** | inputs | float | amount of previous payment; PAY_AMT1 = amount paid in September, 2005; PAY_AMT2 = amount paid in August, 2005; ...; PAY_AMT6 = amount paid in April, 2005 |
| **DELINQ_NEXT**| target | int | whether a customer's next payment is delinquent (late), 1 = late; 0 = on-time |


