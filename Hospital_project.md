<img src="Hospital_Visuals/Hospital Project banner 2.jpg?raw=true"/>

# Streamline procedures & Maximize hospital capacity

## Introduction 

We analyzed data from **101,766 patients across a span of 10 years, gathered from 130 hospitals.**

Did you know that the average cost of a hospital stay in the US is $2,873 per day? When patients stay longer than necessary, it can prevent new patients from receiving the care they need. That's why **we're exploring using ways to open up more beds** and reduce unnecessary costs for patients who could be recovering at home.
<br><br>
*The origin of the data can be found [here]([https://finances.worldbank.org/Loans-and-Credits/IDA-Statement-Of-Credits-and-Grants-Historical-Dat/tdwh-3krx](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008))* <br><br>
<img src="Hospital_Visuals/Intro about data.jpg?raw=true"/><br>
<img src="Hospital_Visuals/Averages-combined.jpg?raw=true"/> <br>


## Great Questions  

- What are six success stories of patients coming to the emergency? 
- Are Patients staying at the hospital less than a week on average?  
- What medical specialties are doing the most procedures? 
- Is there any special treatment for a certain race? 
- Does more lab procedures correlate to more days in the hospital? 
- Can we make a summary of patients with the most medication?
  
## Key Insights 

- There are success stories means we have examples to look into.  
 - The average stay overall is 4.40 days and would cost $12,641 if the patient was responsible for the full amount. 
 - Cardiology and Cardiology surgery are the most common procedures by far.  
 - From the data, all races are treated the same for lab procedures.  
 - In the vast majority of cases, more procedures equals more days in hospital.  
 - The summary shows even with 9 medications not always readmitted. 


## The Data 
**Creating room for incoming patients in hospitals is of utmost importance** and there are **two approaches** to achieve this goal.

1. Building more rooms and. Adding more beds.  
2. Promptly discharging patients. 

When it comes to patient care, efficiency is important, but it's equally important to ensure that patients aren't readmitted less than 30 days after being discharged. This requires a careful balance between prompt discharge and thorough follow-up care to prevent any unnecessary readmissions.

let's start things out with a positive note and look at six success stories that happened inside the emergency unit. <br>
<img src="Hospital_Visuals/Success stories-Combined_no added text.jpg?raw=true"/>
Knowing specifically what contributed to making these success stories happen would be good data to collect. **You can imagine how much of an impact this has on opening up beds.** 

Next, we are trying to see if the avg stay in the hospital was less than 7 days is easiest with a histogram.  
<img src="Hospital_Visuals/Histogram combined.jpg?raw=true"/>
SQL is not the best with this graph so we made one in Tableau as well. **It's clear that most patients are discharged before 7 days.** The avg is 4.40 days. 

let's have a look at what the busiest sector of the hospital is. 
<img src="Hospital_Visuals/num_precedures-combined.jpg?raw=true"/>
It looks like **cardiology really is the biggest piece of the puzzle in this case,** and making sure they have enough resources to be as efficient as possible will be important. 

A very touchy, but also very important piece of the puzzle is whether race is causing any special treatment good or bad.  
 <img src="Hospital_Visuals/avg lab vs race-Results-Combined.jpg?raw=true"/>
luckily from the data we have it does not appear that race is getting special treatment. 

Next, we're looking at how much of a correlation lab procedures have to the number of days a patient is in the hospital. 
 <img src="Hospital_Visuals/more procedures-Combined.jpg?raw=true"/>
 You can see in the inquiry that there's **definitely a correlation** between the number of lab procedures and the days a patient is in the hospital. which means that **reducing the number of procedures or improving their efficiency of them will also free up beds.** 

The very **last** thing we're going to do is make a **summary of each patient** and see what stands out. 
 <img src="Hospital_Visuals/Patient summary-combined.jpg?raw=true"/>
 What I take away from this summary is that **even with a lot of medication prescribed. In many cases, the patient is not readmitted.**

## Key Insights 
- There are success stories means we have examples to look into.  
- The average stay overall is 4.40 days and would cost $12,641 if the patient was responsible for the full amount. 
- Cardiology and Cardiology surgery are the most common procedures by far.  
- From the data, all races are treated the same for lab procedures.  
- In the vast majority of cases, more procedures equals more days in hospital.  
- The summary shows even with 9 medications not always readmitted.
- 
## Recommendations 
- Here are some things to focus on. these pieces would make the biggest impact 
- Finding out more data on what led to the success stories so we can learn from them and improve other departments by freeing up beds quickly. 
- Confirm that the cardiology sector is running as efficiently as possible because it will have the biggest impact. Why? 
- Let's look at ways to reduce the number of procedures. Also improve efficiency because that will lead to fewer days in the hospital. 
  *The goal here is to streamline procedures and maximize hospital capacity.*

If you enjoy reading this article, let's connect on LinkedIn 
check out some other articles that I have done. 
Thank you so much for taking the time to have a look at this project. 
 



 






