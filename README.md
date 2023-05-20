# Covid-19_India_Analysis_PowerBi

Problem Statement - Analysis of COVID-19 Cases in India
Using the Dataset following questions were attempted

1. Which state has the highest number of active COVID-19 cases as recorded on 31 July 2020?
    Maharashtra
    
2. Use a Treemap to determine the percentage of deaths, cured and active cases out of the total confirmed cases in Maharashtra.
    Cured: 54.34; Active: 41.79; Deaths: 3.8
    
3. which of the following states has the least positivity rate as recorded on 31 July 2020?
    Himachal Pradesh
    
4. Choose the correct order of the top three mortality rates observed for the given states as recorded on 15 July 2020.
    Gujarat > Maharashtra > Madhya Pradesh 
    
5. Between 10 July 2020 and 20 July 2020, which state had the second highest spike in the number of confirmed cases?
    Tamil Nadu

6. Which of the following DAX formulas gives a calculated summary table for the number of testing labs available by State and Type of Lab.
    State Testing Labs = SUMMARIZE(ICMRTestingLabs, ICMRTestingLabs[state], ICMRTestingLabs[type], "No.of Labs", CALCULATE(DISTINCTCOUNT(ICMRTestingLabs[address])))
    
7. which of the following types of testing labs constitutes a major percentage of the available types among all the states?
    Government laboratory
    
8. Slicer but not a page-level filter is used in a scenario where the data in only a few visualizations is to be filtered while others remain the same.
    True

9. In which level of filters in Power BI is Top N accessible?
    Visual level
