For this exercise, I considered a visualization from the Million Hearts webpage The particular data visualization is related to the Medicare Reporting Coverage. The source of the data is from this link: https://www.cdc.gov/mmwr/preview/mmwrhtml/mm6416a3.htm

To give a bit of a background, The Million Hearts program is an initiative led by Centers for Disease Control and Prevention (CDC) and Centers for Medicare and Medicaid Services (CMS) to prevent heart attacks and strokes. One of their priorities is to increase the % of patients who have their blood pressure under control. Another initiative is to incentivize healthcare providers (clinics/ hospitals) to use Electronic Health Records to report a blood pressure health quality metric (NQF 0018).

In order to obtain more surveillance data, the program encourages providers participating in the CMS EHR Incentive Program to report their patients' hypertensive condition through the NQF 0018 quality metric. The quality metric reporting is optional so the providers are not required to do it. This particular visualization shows that number of Medicare providers reporting the quality metric has increased over time allowing the Million Hearts team to record an increasing number of hypertensive patients. However, it also shows that the % of providers reporting the quality metric remains the same. The reason why the Medicare Reporting Coverage has increased is not because Million Hearts has encouraged existing providers to report their numbers but because in general the number of providers participating in the CMS EHR Incentive Program has increased.

I thought that the visualization that showed a clear upward trend was a bit misguiding. It showed a false sense of progress when in fact the reporting of data has occured just because more providers are now reporting through a different unrelated EHR Incentive Program. I wanted to try different ways to show the visualization without confusing the user yet reporting the data correctly. Following are a few ways I tried to figure out a way to recreate the visualization:

![IMG_20200202_233803](https://user-images.githubusercontent.com/30089420/74115663-4099b880-4b7e-11ea-864c-695deaa9221a.jpg)

I first implemented a pie chart in tableau and tried to show to a few users. They only realized what I was trying to show after I explained it to them which was obviously not a good sign. I changed it then to a stacked bar graph. This was an improvement but it left out an important aspect that the number of reported hypertensive patients is increasing. I also did not want to combine the way they had done it because the line chart points were seemingly at randome places within the bar chart (At a first glance).

I finally decided to show two separate graphs:

Indicating that the number of hypertensive patients being reported is higher because the number of Medicare providers reporting them have increased.

<img width="1063" alt="blah" src="https://user-images.githubusercontent.com/30089420/74115689-5d35f080-4b7e-11ea-8881-8f9782de2cba.png">

However, the number of Medicare providers reporting has increased not because existing providers in the program have started reporting but because new providers were added to another program linked to the Million Hearts program.

<img width="1064" alt="Screen Shot 2020-02-02 at 11 48 25 PM" src="https://user-images.githubusercontent.com/30089420/74115704-6a52df80-4b7e-11ea-80b5-1d49a41b46c8.png">
