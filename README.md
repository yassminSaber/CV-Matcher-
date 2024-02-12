# CV Matcher 

This project Match you with the best fit job oppertunity based on your CV.
It contaains several stages (Data Collecting, Data Analysis, Applying algorithms)

## Data Collecting
- Web scraping techniques were used to to collect data from Wuzzuf website. The scraped data contains features such as Job Title, Company Name, Job Location, Job Description,and Job Requirements.

## Data Storage
- The scraped data was stored in a csv format, and in a database.

## Data Analysis
- Extract insights such as
  
1. Most common job title:
jobs title and number of each job valid:
  Customer Service     120
  Accountant            81
  Web Developer         57
  Civil Engineer        56
  Software Engineer     25
  Flutter Developer      2

<img src = "https://github.com/yassminSaber/CV-Matcher-/blob/main/most-common-job-title.png" width=700 hight =200/>
<img src = "https://github.com/yassminSaber/CV-Matcher-/blob/main/most-common-job-title2.png" width=700 hight =200/>

2. The preferred qualifications or skills mentioned in job descriptions

   
<img src = "https://github.com/yassminSaber/CV-Matcher-/blob/main/skills%20frequency.png" width=700 hight =200/>
<img src = "https://github.com/yassminSaber/CV-Matcher-/blob/main/skills%20frequency2.png" width=700 hight =200/>
   
   
3. The geographic distribution of job opportunities.

<img src = "https://github.com/yassminSaber/CV-Matcher-/blob/main/job-location-distribution.png" width=700 hight =200/>

## Applying the Algorithm 

TF-idf (term frequency-inverse document frequency) Matching algorithm 
