# Manjiri-Portfolio
Public portfolio for the Telling Stories with Data class at CMU

# About Me
My name is Manjiri. I am a 2nd year Healthcare Policy and Management Master's student at the Heinz College. My pronouns are she/her/hers. I am passionate about health equity and equal access to quality healthcare. I hope to leverage my skills as a biomedical engineer and a policy analyst to tackle problems in the field of healthcare innovation and health services delivery. 

# What I hope to learn
I have encountered many situations in the past where I was unable to convey the importance of an issue or a program using data to my audience. My frustration of "how do you not see what the data is showing you" made realize that the fault was mine and not theirs. I hope to learn different data visualization techniques to better convey the story the data is telling. 

# Portfolio

## OECD Data Visualizations 
[Link to Page](/OECD_viz.md)

## Critique by Design 
For this exercise, I considered a visualization from the [Million Hearts webpage](https://millionhearts.hhs.gov/data-reports/data.html)
The particular data visualization is related to the Medicare Reporting Coverage. The source of the data is from this link: https://www.cdc.gov/mmwr/preview/mmwrhtml/mm6416a3.htm

To give a bit of a background, The Million Hearts program is an initiative led by Centers for Disease Control and Prevention (CDC) and Centers for Medicare and Medicaid Services (CMS) to prevent heart attacks and strokes. One of their priorities is to increase the % of patients who have their blood pressure under control. Another initiative is to incentivize healthcare providers (clinics/ hospitals) to use Electronic Health Records to report a blood pressure health quality metric (NQF 0018). 

In order to obtain more surveillance data, the program encourages providers participating in the CMS EHR Incentive Program to report their patients' hypertensive condition through the NQF 0018 quality metric. The quality metric reporting is optional so the providers are not required to do it. This particular visualization shows that number of Medicare providers reporting the quality metric has increased over time allowing the Million Hearts team to record an increasing number of hypertensive patients. However, it also shows that the % of providers reporting the quality metric remains the same. The reason why the Medicare Reporting Coverage has increased is not because Million Hearts has encouraged existing providers to report their numbers but because in general the number of providers participating in the CMS EHR Incentive Program has increased. 

I thought that the visualization that showed a clear upward trend was a bit misguiding. It showed a false sense of progress when in fact the reporting of data has occured just because more providers are now reporting through a different unrelated EHR Incentive Program. I wanted to try different ways to show the visualization without confusing the user yet reporting the data correctly. Following are a few ways I tried to figure out a way to recreate the visualization:

<inster image>

I first implemented a pie chart in tableau and tried to show to a few users. They only realized what I was trying to show after I explained it to them which was obviously not a good sign. I changed it then to a stacked bar graph. This was an improvement but it left out an important aspect that the number of reported hypertensive patients is increasing. I also did not want to combine the way they had done it because the line chart points were seemingly at randome places within the bar chart (At a first glance). 

I finally decided to show two separate graphs: 

1) Indicating that the number of hypertensive patients being reported is higher because the number of Medicare providers reporting them have increased. 

2) However, the number of Medicare providers reporting has increased not because existing providers in the program have started reporting but because new providers were added to another program linked to the Million Hearts program.





