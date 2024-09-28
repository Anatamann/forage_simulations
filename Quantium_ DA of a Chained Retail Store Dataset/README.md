# DA of a Retail Chain Store
*Summary*: The stakeholders of a Retail Chain Store have requested an Analysis of the sales data of multiple stores. They want the sales trends and customer profiling for the "Chips" category specifically. They also want to analyze the results of the trials that they implemented in some of the stores.

## Deliverables
1. Analyzing the sales data and Customer profiling for the chips category of the stores.
2. Analysis of the trial stores.

## Executive Summary
*Analysis represents the Dataset of 1 year*
1. December Month clocks the highest sales of Chips with around 21% increase in average monthly spending and quantity sold compared to other months.
2. Kettle, Smiths & Doritos are the most sold Chips brands and out of 21 Chips Brands these 3 Brands contribute to ~33% of total revenue in the chips category.
3. "Mainstream_ Young Singles and Couples" customer segment is the primary shoppers comprising of ~11% of total customer counts  of the chips category.
4. "Old families" and "Young families" customer segments have a high average buying basket size (chips per segment) i.e., "9.6" & "9.2" respectively while the segment average is "6.8".
5. Control stores were identified for the respective trial stores to analyze the success of the trials and the analysis backs it up as a successful trial.

### Resources
*Three datasets in total, two in csv format and one in xlsx format*
1. QVI_data
2. QVI_purchase_behaviour
3. QVI_transaction_data

QVI_transaction_data consists of 2,64,873 transaction data over a year of duration.<br>
QVI_purchase_behavior comprises the customer details of the store.<br>
QVI_data comprises the merged data of QVI_transaction_data & QVI_purchase_behavior. 

### Analysis Steps
*The complete analysis was carried out using Python's Pandas dataframe library in ipyNotebook environment*

1. Data Cleaning
2. Data Modeling
3. Insights and Visualization for customer profiling in the chips category.
4. Hypothesis building and testing for finding the control stores for our trial stores.
5. Insights and Visualizations for the trial store results.
6. Final presentation to the client.

### Insights and Suggestions
1. A seasonal trend with 21% increase in chips sales in December month.
2. Budget and Mainstream customers spend more than the premium customers on chips.
3. Mainstream-Young Singles / Couples and Mainstream-Retirees comprise 20% of total customers and 16% of the total sales.
4. Mainstream-Young Singles / Couples segment customers have a higher affinity towards brands like Tyrrells & Twisties.
5. Young Families and Old Families have high basket sizes in comparision to the other segments contributing to 34.5% of total sales.

*Placing Tyrrells & Twisties chips brands where the Young Singles/Couples visit the most can increase sales per customer of the segment.*<br>
*Young Families & Old Families tend to buy more chips so the store can run special combo offers for more revenue opportunities.*<br>
*Store can run pre-promotions for the preparation of December month.*

6. Store-233 is the control store of the trial Store-77 and the trial was a success with ~33.4% avg. sales increase during the trial period.
7. Store-155 is the control store of the trial Store-86 and the trial was a success for 1 month of the trial period with 30% increase in sales but falls in the remaining months similar to the control store.
8. Store-237 is the control store of the trial Store-88 and the trial was a success with ~23% avg. sales increase during the trial period.

*The trial was significantly successful in Store-77 and Store-88 and we suggest implementing the trial period layouts for the store. We would like further monitoring and clarification for Store-86 and its trial methods.*

### Example Insights
<img src="ScreenShots/Control Stores.JPG"><br>
<img src="ScreenShots/Target Customer affinity.JPG">
