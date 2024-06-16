# E-Commerce-Sales-Analysis-An-Excel-Based-Project
## Objectives:
I spearheaded an analysis of e-commerce sales data sourced from Kaggle for the year 2022. Following meticulous data cleaning, I crafted an interactive dashboard using pivot tables to visualize sales performance, customer behavior, and product trends. Through in-depth analysis, I identified key insights, aiding stakeholders in strategic decision-making. I compiled findings into a comprehensive report, offering actionable recommendations for optimizing e-commerce operations and maximizing profitability. 
## Data Source:
The dataset used in this project has been sourced from Kaggle. The dataset had 31000 datapoints.
## Data Cleaning Process:
* After loading the dataset, I started my cleaning process. First, I looked for null or missing value, I checked every column, there was no null values in the dataset.
* Then, I saw in the gender column few records were in like “F” & “M” and few were in “Male” & “Female”. So, I converted all the “M” into “Male” and all “F” into “Female”, using ctrl+H i.e. find and replace method.
* Then I made 2 new extra columns to make my analysis easier,

  i) First, all the purchasing date was in dd-mm-yyyy format, now it was impractical to keep it analyse it like that, so converted each date in month format using =TEXT() function, so that I get to know which month was the highest selling month.

  ii) Then, age of all the buyers for all purchases made were given in the age column, I made a new column "Age-group", I grouped them into young, adult and old category using =IF function. This helped me to know which age group made the most purchase.

## Business Questions:
* Compare the sales and orders using single chart.
* Which month got the highest sales and orders? 					
* Who purchased more: men  or women in 2022? 		
* What are different order statuses in 2022? 			
* List of top 10 states contributing to the sales? 			
*  Relation between age and gender based on number of orders? 	
* Which channel is contributing to maximum sales?
*  Highest selling category?
## Data Visualizations:
![image](https://github.com/daniketdas/E-Commerce-Sales-Analysis-An-Excel-Based-Project/assets/162815966/ac321417-b05e-4848-aae1-65035e49bba3) ![image](https://github.com/daniketdas/E-Commerce-Sales-Analysis-An-Excel-Based-Project/assets/162815966/c71c389c-a563-4005-9eca-284db554e13e) ![image](https://github.com/daniketdas/E-Commerce-Sales-Analysis-An-Excel-Based-Project/assets/162815966/8f510d7f-6c1d-4c10-ac19-fa0358bf39a0) ![image](https://github.com/daniketdas/E-Commerce-Sales-Analysis-An-Excel-Based-Project/assets/162815966/cd6b1c34-e48a-4526-99fb-9a03c7c49a09) ![image](https://github.com/daniketdas/E-Commerce-Sales-Analysis-An-Excel-Based-Project/assets/162815966/c4090eab-5747-445d-b0aa-643a3cd94b10) ![image](https://github.com/daniketdas/E-Commerce-Sales-Analysis-An-Excel-Based-Project/assets/162815966/3ecf4bd8-ee7c-415a-9996-6bf331ef62a1) ![image](https://github.com/daniketdas/E-Commerce-Sales-Analysis-An-Excel-Based-Project/assets/162815966/bf999291-b5bc-4280-a2c1-9c734ff11b7e)
## Sales Insights:
* 1st quarter is the most selling quarter and March is the highest selling month of the year 2022.
* 64% orders were made from women, where adult women have the highest share and that also reflects on the most selling category.
* Most of the orders were delivered(~92%), where Amazon has been the most used channel follwed by Myntra nad Flipkart.
* Maharashthra, Karnataka and Uttar Pradesh are the top 3 states (~35%).
## Recommendation:
* Companies should target adult women(30-49 years) who live in Maharashthra, Karnataka and Uttar Pradesh.
* Companies can run promotions for their products on various platforms specially on Amazon, Myntra and Flipkart.
* Companies can also design various coupons or discounts for their target customers so as to increase their sales.






