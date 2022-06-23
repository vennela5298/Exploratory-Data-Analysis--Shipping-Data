# Exploratory-Data-Analysis--Shipping-Data

Performed exploratory data analysis on the shipping data of an e-commerce website. Compared the shipping costs that incurred during Quarter 2 in 2017 and 2018.
Came up with the following insights

I used Python and its libraries to analyze and gather insights from the UPS shipment data for both  2017 and 2018 year. I also used Excel to preprocess the data before loading it into Jupyter Notebook. Despite having a contract with UPS for better pricing in 2018, the percentage of revenue was still on the rise. Upon performing some Exploratory Data Analysis on both datasets, I have uncovered the following important trends/insights-

●	The first thing I noticed after reading the data is that 2 variables/columns (‘Package Dimensions’,’ Detail Keyed Dim’) have more than 80 percent missing values. Both these fields are important parameters for the generation of the net amount, and the lack of this data will hinder the ability to gauge accurate insights. Due to the significant number of missing values, I did not consider these columns for my analysis.
●	The analysis of the ‘Charge Description’ column yielded some interesting insights.

 
Fuel Surcharge seems to be the most frequently occurring charge during both the years. However, Shipping Charge Correction Over Maximum Size has the highest average net amount and the value increased significantly in 2018. Notably, the top 4 highest incurring charges per transaction come under the correction class of charges in 2018.

●	I created a new column ‘diff’ on excel which contains the difference between the ‘Entered Weight’ and ‘Billed Weight’. This column can be significant because it sheds light on the factors behind the size and weight correction charges.  
   2017                                                                                        2018

The average diff weight reduced slightly in 2018. Therefore, the difference in weights may not be a huge contributing factor to the correction charges.

Key Takeaways

Surcharges and corrections charges lead to higher shipping costs. From the above insights, it is observed that fuel surcharge is the most frequently occurring and correction charges contribute the most to the net shipping costs. Despite getting better pricing, the correction charges remained to be high and even increased significantly from 2017. 

While Fuel surcharge is a factor that is beyond the control of the company, Correction charges are something that can definitely be avoided. “Correction over Maximum Size’ has the highest average cost thereby making package dimensions an important factor. By making sure the package dimensions for each shipment are collected and stored, it will be easier to identify the root cause of the correction surcharges.

Although the average next-day early air commercial charge reduced from 2017 to 2018, the other next-day early air charges have increased. Air transportation charges, therefore,  are also one of the contributing factors to the increased costs.

Upon further analysis, It was discerned that there was a similar trend for Zones and Transaction Date on net amount or number of transactions for both the years.
( Refer to Python notebooks for in-depth EDA)

Areas of Opportunity

To avoid the correction charges, emphasis should be given to the packaging. Although the product weight cannot be changed, the type of packaging is manageable. Choosing a pack size big enough to hold the products but snug enough to maintain the dimension to a minimum would avoid inflating the shipping costs.
In addition to this, stocking various packing materials with different sizes for appropriate selection and choosing lightweight fillers to lessen the weight of the entire package can help as well.

Instead of relying on a single carrier for the shipping, adopting a multi-carrier policy might help. The services of other carriers offering lower correction charges or surcharges can be availed and is an area worth exploring.

