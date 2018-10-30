# San Fransisco School Finder Web Application

[Home](index.md)

## Project Description
I created this with four friends at a hackathon; my responsibility was to code the backend as well as develop and program the algorithm that our application performs (which involves a weighted sort).

The goal of the hackathon, which took place in San Fransisco, was to solve a social issue that San Francisco faces. My group and I decided to tackle the issue of the socioeconomic disparity in public schools. There is a form families can complete on which they indicate their preference of schools. However, as we learned, information about these schools and their programs is often difficult to find. As a result, researching the schools can take several hours and is a frustrating process.

We designed a web application that allows families to answer a series of relevant questions (such as, "Where do you live?" or "How important is after-school enrichment?"). The program then runs the results of these questions through an algorithm that performs a weighted sort and lists the schools that correspond with the user's needs, in order of best fit.

<img src="sfschools.png" alt="SF School Finder" width="60%" height="60%"/>

This [link](https://github.com/thaisgm/teamWolverines) will take you to a page where you can download the full project.

## More Details
This project uses node and incorporates the database MongoDB.
The algorithm gives schools " inherent scores" in different categories and multiplies the inherent scores in each of these categories by a "percentage score" in each category. These percentages are determined by how closely the a particular factor (such as "commute" or "academic performance") matches with the user's specific needs. In other words, the "inherent score" is independent of the user, whereas the "percentage score" is based on how well the user matches with the school. Each category's inherent score is multiplied by its percentage score. Then, a all of these categories are added up, and the school receives a "final score."
