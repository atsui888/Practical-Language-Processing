# Practical-Language-Processing
<b>Boosting Customer Satisfaction via Practical Language Processing on Bank Call Centre Customer Dialog Data</b><br> 
Masters of Technology in Artificial Intelligence (National University of Singapore - ISS)<br> 
Practice Module 4 <br>

<h1>Overview</h1>
Over the last few years, the bank has been executing its strategy of customer centricity and it has been rewarded with excellent financial results and industry accolades. To monitor the 
success of this strategy, the bank utilises 3rd party agencies and internal staff to track customer satisfaction levels. <br><br>

The 3rd party agencies claim to have highly effective proprietary methods which the bank does not have access to. Within the bank, the categorization and tabulation of customer satisfaction 
levels is performed manually, with results documented on Excel spreadsheets. This laborious process is error-prone and hinders the generation of timely customer satisfaction updates, 
typically limited to a quarterly frequency. <br>

Hence, management would like to try using Practical Language Processing (PLP) techniques on customer dialog data to: 
- Automate the manual process of monitoring customer satisfaction levels. 
- Identify areas where the bank is doing well or not, with system recommended prioritisation.
- Validate the accuracy of the existing customer satisfaction monitoring services.
- <br>
By implementing this PLP Analysis System, the bank will be able to take a data-driven approach 
to gain deep insights into their customer interactions, allowing them to proactively address 
emerging issues and adapt quickly to changing customer needs and expectations. 

The system identifies topics from customer dialog, identifies the product and usage areas the bank is doing well (or not), and prioritises them based on a relevant importance metric so that the bank can make a data-driven decision on intervention initiatives. In addition to that, from analysis of customer dialog, the application also provides bank wide metrics like Net Promoter Score (NPS) and Customer Satisfaction Ratio (CSAT) for the bank to have an overall sense of their standing in their customers' eyes.
<br><br>

<h1>Design</h1>
<h2>Solution - Automated Customer Dialog Analysis System for Insights</h2>

![01 PLP Automated Topic Sentiment Solution Blueprint drawio](https://github.com/user-attachments/assets/b09e0531-6e01-4bd6-9574-ad270fadf71f)

From Example Dialog like this ... <br>
![image](https://github.com/user-attachments/assets/2df0919d-2be2-4274-ae5f-ab34c5e201a0)
<br>
the Dialog Analysis Application uses 4 different techniques to 
- Identify key customer topics
- Ranks each topic by customer sentiment and relevant importance metrics
- Calculates the bank's overall NPS and CSAT scores. 



<h2>Model Training Pipeline</h2>

![02 Model Training Flow drawio](https://github.com/user-attachments/assets/11c7b045-6d90-495c-89a6-9571e095516a)



<h2>Dashboard</h2>

![image](https://github.com/user-attachments/assets/c989101b-6c13-4ef4-a05e-f990a67c6dd3)

![image](https://github.com/user-attachments/assets/3a1e5174-fa5e-4740-ab1c-b92ae79e9bd7)

![image](https://github.com/user-attachments/assets/a9d9f108-0867-4002-9c09-f23bf016837c)


<br>
<h2>System Architecture - MVP</h2>
  ![03 PLP Technical Architecture_MVP drawio](https://github.com/user-attachments/assets/49d5ae64-45ad-459f-92f5-372e40232d7b)


<br>
<br>
