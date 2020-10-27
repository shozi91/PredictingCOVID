# PredictingCOVID
How do you predict the trends of a pandemic? In this project we attempt to gather key metrics that will serve as safeguards for how well the country will perform in this worldwide disease.


SUMMARY OF FINDINGS
1. MEDIAN AGE VS CONFIRMED CASES PER 100,000
This figure plots the Median age against the number of confirmed cases per 100,000 people. Our observations are:
-	We can see a medium positive correlation between the two factors as shown by the r-squared values. 
-	The higher the median age in a given country, the greater the likelihood of contracting COVID-19
-	p-value less than 0.05 null hypothesis rejected
2. MEDIAN AGE VS COVID-19 MORTALITY RATE (%)
	This plots the Median age against the Mortality Rate for Covid-19. Our observations are:
-	We can see a mild negative correlation between the two factors
-	The higher the median age, the lower the mortality rate
-	 the mild correlation is shown by the r-squared value for the plotted regression line
-	p-value less than 0.05 null hypothesis rejected
3. HOSPITAL BEDS PER 1000 PEOPLE VS MORTALITY RATE
This plots the Hospital Beds Per 1000 people against the Mortality Rate for Covid-19. Our observations are:
-	We can see a medium negative correlation between the two factors
-	The higher the number of Hospital Beds Per 1000 People, the higher the likelihood of survival
-	the medium correlation is shown by the r-squared value for the plotted regression line
-	p-value less than 0.05 null hypothesis rejected
4. HEALTH EXPENDITURE PER CAPITA VS MORTALITY RATE
This plots the Health Expenditure per Capita against the Mortality Rate for Covid-19. Our observations are:
-	We can see a mild negative correlation between the two factors
-	The higher the Health Expenditure per Capita, the lower the likelihood of survival
-	the mild correlation is shown by the r-squared value for the plotted regression line
-	p-value less than 0.05 null hypothesis rejected

In this project we have examined, the median age, the healthcare expenditure per capita and hospital beds per 1000 people and their correlation to the number of confirmed coronavirus cases and the number of deaths. It seems that that the there is a stronger correlation between quality of healthcare (as judged by the number of hospital beds and health care expenditure) and the survival rate from the virus than there is between median age and mortality.
Possible sources of bias or skewed data:
-	older populations may be more likely to seek diagnoses than younger, therefore leading to a underreporting for countries with lower median age
-	the pandemic is ongoing, so countries that got it earlier may be more prepared than countries that are getting it now leading to higher mortality rates for those that were less prepared and experienced
-	ventilator count maybe a more influential factor than overall healthcare expenditure
-	there is overall less COVID data for countries with fewer cases as of now

