# Analyze-marketing-traffic

1. Object:
Optimiza the bidding by identifying the top traffic sources and measuring the conversion rates.

2. Dataset
![image](https://user-images.githubusercontent.com/129491801/232585262-51f509e3-c488-41b8-bdac-18281fcb522a.png)


3. Technics
MySQL Workbench 

4.Steps

1)Soure of website sessions breakdown by utm_source, campaign and referring domain
![image](https://user-images.githubusercontent.com/129491801/232586744-9af7d3ec-bdc5-4bd4-b04c-718c4333dd52.png)

Findings:gsearch nonbrand is the major traffic source,dive deep to explore the potential optimization opportunities

2)gsearch nonbrand conversion rate(CVR) from session to order
![image](https://user-images.githubusercontent.com/129491801/232587186-3ed52d13-0757-49d1-a6dd-8a40d1ba67d3.png)
Finding: the conversion rate is 2.8%, since the conversion rate is lower than the setting thershold, so the company decided to bid-down on gsearch nonbrand.

3)Trend analysis: since bid down on budget, analyzing the traffic trend by week to see if the bid down caused the traffic volume to drop
![image](https://user-images.githubusercontent.com/129491801/232588109-d3e69274-2596-44df-a68b-78d9841445f7.png)

4)Tgsearch device-level performance: pull conversion rates from session to order, by device type
![image](https://user-images.githubusercontent.com/129491801/232588413-c8565fa3-9a29-4977-8d0f-82f1198df97e.png)

5)Trend analysis by week on the device type

![image](https://user-images.githubusercontent.com/129491801/232588622-3b00fcaa-8d27-4456-9a3d-c4c603d015a0.png)

