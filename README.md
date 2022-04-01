# Hypothesis-Testing

## Problem Statement

Autolib electric car-sharing service company to investigate a claim about the blue cars from the provided Autolib dataset. The goal of this project is to identify some areas and periods of interest via sampling method, then perform hypothesis testing with regards to the claim that we will have made. We shall be interested in the question, "Is the number of Bluecars taken in area postal codes 75015 different than in postal code 75017 ? 

## Research Context
Autolib was a French electric car sharing service that operated from 2011 until 2018. There were three types of electric cars offered by the company: blue cars, Utilib cars, and Utilib 1.4 cars. Blue automobiles were the most popular. These automobiles were accessible in a variety of cities and postal codes across France, and renters could pick them up at one station and return them to a station closer to their destination. The dataset employed in this analysis enables us to comprehend the company's diverse electric car usage trends. Between January 2018 and June 2018, the accessible data includes usage information for various postal codes.
For this project, I decided to focus on  z-score to test hypotheses. A representative sample from each postal region was chosen for the analysis. The hypothesis was also tested at a 95 percent confidence level.
Null Hypothesis: The number of Blue cars taken from postal code 75015 is the same as in postal code 75017 during weekdays.
(μ1=μ2)
Alternative Hypothesis: The number of Blue cars taken from postal code 75015 is not the same as in postal code 75017 during weekdays.
(μ1≠μ2)

## Data Description

The dataset used in the study covers records of electric car usage in France from January to June 2018. This information was obtained from opendataparis.com. The dataset includes information such as postal code, day of the week, and total automobiles returned or picked up for blue cars, Utilib cars, and Utilib 1.4 cars. Given the null and alternative hypotheses above, the number of blue automobiles picked up is the key variable of interest. This exact attribute is accessible in the dataset for separate postal codes for each day of the week from January 1, 2018 to June 19, 2018.
In the original dataset, there were 13 attributes. The dataset is attached on the repository.
