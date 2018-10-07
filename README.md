## An Analytical Detective

Crime is an international concern, but it is documented and handled in very different ways in different countries. In the United States, violent crimes and property crimes are recorded by the Federal Bureau of Investigation (FBI).  Additionally, each city documents crime, and some cities release data regarding crime rates. The city of Chicago, Illinois releases crime data from 2001 onward online.

Chicago is the third most populous city in the United States, with a population of over 2.7 million people.

There are two main types of crimes: violent crimes, and property crimes. In this problem, we'll focus on one specific type of property crime, called "motor vehicle theft" (sometimes referred to as grand theft auto). This is the act of stealing, or attempting to steal, a car. In this problem, we'll use some basic data analysis in R to understand the motor vehicle thefts in Chicago. 

Dataset: **mvtWeek1.csv**

Here is a list of descriptions of the variables:

* ID: a unique identifier for each observation
* Date: the date the crime occurred
* LocationDescription: the location where the crime occurred
* Arrest: whether or not an arrest was made for the crime (TRUE if an arrest was made, and FALSE if an arrest was not made)
* Domestic: whether or not the crime was a domestic crime, meaning that it was committed against a family member (TRUE if it was domestic, and FALSE if it was not domestic)
* Beat: the area, or "beat" in which the crime occurred. This is the smallest regional division defined by the Chicago police department.
* District: the police district in which the crime occured. Each district is composed of many beats, and are defined by the Chicago Police Department.
* CommunityArea: the community area in which the crime occurred. Since the 1920s, Chicago has been divided into what are called "community areas", of which there are now 77. The community areas were devised in an attempt to create socially homogeneous regions.
* Year: the year in which the crime occurred.
* Latitude: the latitude of the location at which the crime occurred.
* Longitude: the longitude of the location at which the crime occurred.



## Stock Dynamics

A stock market is where buyers and sellers trade shares of a company, and is one of the most popular ways for individuals and companies to invest money. The size of the world stock market  is now estimated to be in the trillions. The largest stock market in the world is the New York Stock Exchange (NYSE), located in New York City. About 2,800 companies are listed on the NYSE. In this problem, we'll look at the monthly stock prices of five of these companies: IBM, General Electric (GE), Procter and Gamble, Coca Cola, and Boeing. The data used in this problem comes from Infochimps.

Call the data frames "IBM", "GE", "ProcterGamble", "CocaCola", and "Boeing", respectively. Each data frame has two variables, described as follows:

* Date: the date of the stock price, always given as the first of the month.
* StockPrice: the average stock price of the company in the given month.
In this problem, we'll take a look at how the stock dynamics of these companies have changed over time.


## Demographics and Employment in the United States

In the wake of the Great Recession of 2009, there has been a good deal of focus on employment statistics, one of the most important metrics policymakers use to gauge the overall strength of the economy. In the United States, the government measures unemployment using the Current Population Survey (CPS), which collects demographic and employment information from a wide range of Americans each month. 

The observations in the dataset represent people surveyed in the September 2013 CPS who actually completed a survey. While the full dataset has 385 variables, in this exercise we will use a more compact version of the dataset, CPSData.csv, which has the following variables:

* PeopleInHousehold: The number of people in the interviewee's household.
* Region: The census region where the interviewee lives.
* State: The state where the interviewee lives.
* MetroAreaCode: A code that identifies the metropolitan area in which the interviewee lives (missing if the interviewee does not live in a metropolitan area). The mapping from codes to names of metropolitan areas is provided in the file MetroAreaCodes.csv.
* Age: The age, in years, of the interviewee. 80 represents people aged 80-84, and 85 represents people aged 85 and higher.
* Married: The marriage status of the interviewee.
* Sex: The sex of the interviewee.
* Education: The maximum level of education obtained by the interviewee.
* Race: The race of the interviewee.
* Hispanic: Whether the interviewee is of Hispanic ethnicity.
* CountryOfBirthCode: A code identifying the country of birth of the interviewee. The mapping from codes to names of countries is provided in the file CountryCodes.csv.
* Citizenship: The United States citizenship status of the interviewee.
* EmploymentStatus: The status of employment of the interviewee.
* Industry: The industry of employment of the interviewee (only available if they are employed).

Source: The Analytics Edge
