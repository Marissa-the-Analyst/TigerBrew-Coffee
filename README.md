# TigerBrew-Coffee
An exploratory data analysis with a dashboard displaying analytics of a coffee vending machine's sales in Excel
To view the data dashboard online, [click here](https://1drv.ms/x/s!AvVMeJdoMRZIb0uG9JQRrZlEitM?e=IpBTMW)

### Scope of Work ###
**Deliverables**
- A clean dataset of sales from March to July 17th.
- A dashboard detailing sales, popular sales hours, and customer insights

**Goal**

The goal of this project was to identify customer purchasing behaviors. Knowing customer purchasing behaviors provides opportunity to use the dashboard for the following use cases:
- Stocking needs/scheduling
- Repeat customer-base
- Customer payment methods
- Sales by month

### Data Set Transformations ###

| Data issue  | Solution |
| ------------- | ------------- |
| No day of the week attribute  | Used date attribute and created day of week column  |
| Datetime was in a unusable format for excel  | Created a time attribute using datetime|
| No time range attribute for usable insights | Created a time-range attribute from time|
| No way to view how many customers are repeats | Used unique card #s to create repeat customer attribute |

**Data Opportunities**

A few data opportunities that TigerBrew would have benefitted from collecting are: <br>
**Location data** <br> 
Knowing the exact location of the vending machine would allow the analysis to dive into customer purchasing behavior based on weather. This is data would also provide insight into potential drivers of traffic near the vending machine such as:
- is it indoors/outdoors
- is it in a rural/urban location
- is it near naturally high traffic areas or do customers have to go out of their way to purchase?
- are there surroundings like benches, rain covers, or other appealing items that make a customer more likely to purchase our coffee?
- Would an additional vending machine be benefical based on these factors? <br>

**Profit data**
- is the vending machine turning a profit?
- what items are our highest ROI?

**Finished Product**
To view the data dashboard online, [click here](https://1drv.ms/x/s!AvVMeJdoMRZIb0uG9JQRrZlEitM?e=IpBTMW)

**Reflection**
This data was fairly clean and the [data author](https://www.kaggle.com/datasets/ihelon/coffee-sales) did well to collect it and keep it in such high quality. While there are opportunities to answer more business questions, the current dataset was wonderful practice for me!
