#### Project Name
Real Estate Sales  - State of Connecticut

### What is the problem you want to solve?

Predict the real estate prices for the year 2014 by examining the connecticut real estate prices data for the years 2011,2012,2013.

#### Who is the Client and why do you care about the problem?

The real estate market in the United States has rebounded significantly from the housing crash of the late-2000s, with low interest rates and limited inventory creating an ideal environment for sellers in some parts of the country. Buyers, on the other hand, often face escalating real estate prices, bidding wars and prolonged search periods as they enter an increasingly competitive market. However Economically, Connecticut has been one of the slowest states in the nation to recover from the economic shock of the 2008 recession.  

From the article below, I would like to highlight the following :
President and CEO of Connecticut REALTORS Michael Barbaro says that Connecticut’s housing market is “defying the laws of economics,” in an interview. “We have low inventory and flat prices. Normally, with low inventory we should have high prices.” he said.
http://www.yankeeinstitute.org/2018/04/connecticut-home-value-growth-slowest-in-the-nation-struggles-under-shadow-of-2008-recession/

#### Data

The data and references(to name a few , more to come later) can be obtained from the below:

https://catalog.data.gov/dataset?publisher=data.ct.gov&organization=state-of-connecticut

The following are the csv files from the above data link for the years 2011, 2012, 2013.  
1. Real estate sales by Town  
2. Crime data  
3. Conveyance tax data  
4. Fire Department incidents data  

### About the data  
The Office of Policy and Management maintains a listing of all real estate sales with a sales price of $2,000 or greater that occur between October 1 and September 30 of each year. The file has name of town, property address, date of sale, property type (residential, apartment, commercial, industrial or vacant land), sales price, and property assessment.  

##### 1. Real_Estate_Sales_By_Town_for_2011__2012__2013__2014 (2).csv  
For each sale record, the file includes:  
Name - Name of the town  
SerialNbr -  
ListYear -Year  
Date Recorded - Observation recorded date  
AssessedValue - Market value  
SalePrice - Actual Sale Price  
AdditionalRemarks --  
SaleRatio - AssessedValue/SalePrice  
NonUseCode -   
ResidentialType - Type of the residential (values in some of the rows include : vacant, residential, commercial,industrial, Apartments,condo family,single family, two family.Some observations have values 0,1,2,3).  
ResidentialUnits - No. of units  
Address - Property Address  
Location - Geolocation (Latitude and longitude information)  

#### Note: The description for the columns SerialNbr, AdditionalRemarks, NonUseCode, ResidentialType, Residentialunits are not clear in the data site. Have requested the dataset owner for additional information.

### Approach

1.	Extract the data 
2. The Crime data, conveyance tax data, Fire department incidents data for the years 2011 - 2013 will to be combined and used for predicting the real estate prices for the year 2014.
3.	Check for missing values and clean the data.
4.	Create visualizations and models to show and predict the real estate prices
5.	Provide conclusions and insights and their level of importance

### Deliverables

Python Code
Powerpoint Presentation
