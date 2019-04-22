# What Defines Good Coffee?


## Project Overview

Typically coffee is described in qualitative terms such as "tasty" or "disgusting." However, I was interested to see if there was a more quantified measure in which we can evaluate coffee quality.

The coffee quality database created by James LeDoux by webscraping The Coffee Quality Institute in January 2018, consisting of 1312 data points, was used in this project. All 1312 data points were arabica coffee samples submitted by producers around the world. After cleaning, 1179 data points remained for analysis. Temperature data was also obtained from the World Bank and merged into the dataset. Information on the standards of coffee grading and quality from the Specialty Coffee Association and the Coffee Quality Institute Q Grading System was also used in the analysis of the results.

#### <u>Key Questions For This Project</u>:
* Can we quantitatively evaluate coffee quality? If yes, how can it be measured?
* What factors contribute to the evaluation of coffee quality?
* What are the factors that weigh the most in the evaluation?


## Coffee Standards

In order to interpret the results from the analysis, I wanted to first understand the established standards used to define coffee quality. The estabished standards for grading coffee as defined by the Specialty Coffee Association are:

* 350g sample of green coffee are used for testing
* 3 certified Q graders contributed to the final score given to each sample
* Graded on different parameters such as: Aroma, Flavor, Aftertaste, Acidity, Balance, Number of Defects
* Cupping Evaluation
* Amount of Category 1 Defects
    * To qualify as specialty grade coffee, there should be 0 Category 1 defects.
* Amount of Category 2 Defects
    * To qualify as specialty grade coffee, there should be 5 or less Category 2 defects

More information can be found on the Speciality Coffee Association's <a href: https://sca.coffee/research/coffee-standards>website</a>.


## Data Collection and Analysis

Data from the Coffee Quality Database was first cleaning by removing columns with all null values such as: ICO Number, and Cupping Procedure and Descriptors. Afterwards, columns with null values were reviewed. 