# Credit-Card-Analysis-Using-Power-BI

### Dashboard Link : 

## Project Objectives:
This Power Bi Dashboard's goal is to analyze the dataset and produce a thorough report that the stakeholder may utilize to get understanding.

By levearging the insights provided , stakeholder can identify patterns on credit card usage,enabling them to optimise their feature to potentially increase revenue.


##  About Dataset:

Prior to proceeding with the project, I would like to discuss the following dataset: 

* An American Credit Card Transaction Dataset been used, using information from January 2023 to December 2023.
* Two datasets were supplied by the company for analytical purposes. Excel sheets "Credit_Card.xls" and "Customer.xls" make up the dataset. These datasets include crucial data on credit card transactions and client information.

## Data Descriptons:
### Credit_Card.xls

The data fields of the dataset that was provided are described as follows:

*Client_Num: An individual number that is given to every client or customer.
*Card_Category: The credit card's category, such as Blue, Gold, or Platinum.
*Annual Fees: The credit card's yearly charge.
*Activation_30_Days: A zero-or one-digit indicator indicating if the card was activated within thirty days of being issued.
*Customer_Acq_Cost: The price paid to obtain the client.
*Week_Start_Date: The beginning date of the week that the information relates to.
*Week_Num: The week that the data entry is associated with.
*Qtr: Quarter (Q1, Q2, Q3, Q4) of the year.
*Current_year: The year that the information relates to.
*Credit_Limit: The maximum amount that the credit card is authorized to be charged.
*Total_Revolving_Bal: The credit card's total amount owed.
*Total_Trans_Amt: The total amount of credit card transactions.
*TransVol Total: The total transaction volume made by the credit card.
* Avg_Utilisation_Ratio: Avg Utilisation Ratio of the Credit Card Balance to the credit limit.
* Use Chip: Indicates whether the credit card transaction was done using a chip or not.
* Interest_Earned : Total Interest Earned by the company
* Exp Type: Type of Expeniture associated with the transaction(eg: Travel,Expenditure)  
 
       

 
 Snap of % of customers who preferred business class
 
 ![Snap_Percentage](https://user-images.githubusercontent.com/102996550/174090653-da02feb4-4775-4a95-affb-a211ca985d07.jpg)

 
 - Step 17 : New measure was created to calculate total distance travelled by flights & a card visual was used to represent total distance.
 
 Following DAX expression was written to find total distance,
 
         Total Distance Travelled = SUM(airline_passenger_satisfaction[Flight Distance])
    
 A card visual was used to represent this total distance.
 
 
 ![Snap_3](https://user-images.githubusercontent.com/102996550/174091618-bf770d6c-34c6-44d4-9f5e-49583a6d5f68.jpg)
 
 - Step 18 : The report was then published to Power BI Service.
 
 
![Publish_Message](https://user-images.githubusercontent.com/102996550/174094520-3a845196-97e6-4d44-8760-34a64abc3e77.jpg)

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://user-images.githubusercontent.com/102996550/174096257-11f1aae5-203d-44fc-bfca-25d37faf3237.jpg)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://user-images.githubusercontent.com/102996550/174074051-4f08287a-0568-4fdf-8ac9-6762e0d8fa94.jpg)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Customers = 129880

   Number of satisfied Customers (Male) = 28159 (21.68 %)

   Number of satisfied Customers (Female) = 28269 (21.76 %)

   Number of neutral/unsatisfied customers (Male) = 35822 (27.58 %)

   Number of neutral/unsatisfied customers (Female) = 37630 (28.97 %)


           thus, higher number of customers are neutral/unsatisfied.
           
### [2] Average Ratings

    a) Baggage Handling - 3.63/5
    b) Check-in Service - 3.31/5
    c) Cleanliness - 3.29/5
    d) Ease of online booking - 2.88/5
    e) Food & Drink - 3.21/5
    f) In-flight Entertainment - 3.36/5
    g) In-flight service - 3.64/5
    h) In-flight Wifi service - 2.81/5
    i) Leg room service - 3.37/5
    j) On-board service - 3.38/5
    k) Online boarding - 3.33/5
    l) Seat comfort - 3.44/5
    m) Departure & arrival convenience - 3.22/5
  
  while calculating average rating, null values have been ignored as they were not relevant for some customers. 
  
  These ratings will change if different visual filters will be applied.  
  
  ### [3] Average Delay 
  
      a) Average delay in arrival(minutes) - 15.09
      b) Average delay in departure(minutes) - 14.71
Average delay will change if different visual filters will be applied.

 ### [4] Some other insights
 
 ### Class
 
 1.1) 47.87 % customers travelled by Business class.
 
 1.2) 44.89 % customers travelled by Economy class.
 
 1.3) 7.25 % customers travelled by Economy plus class.
 
         thus, maximum customers travelled by Business class.
 
 ### Age Group
 
 2.1)  21.69 % customers belong to '0-25' age group.
 
 2.2)  52.44 % customers belong to '25-50' age group.
 
 2.3)  25.57 % customers belong to '50-75' age group.
 
 2.4)  0.31 % customers belong to '75-100' age group.
 
         thus, maximum customers belong to '25-50' age group.
         
### Customer Type

3.1) 18.31 % customers have customer type 'First time'.

3.2) 81.69 % customers have customer type 'returning'.
       
       thus, more customers have customer type 'returning'.

### Type of travel

4.1) 69.06 % customers have travel type 'Business'.

4.2) 30.94 % customers have travel type 'Personal'.

        thus, more customers have travel type 'Business'.
