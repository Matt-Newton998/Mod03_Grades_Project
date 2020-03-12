# Student Grades - Module 3 Project:

### Data Set:

UW Madison Courses and Grades 2006-2017
Courses, grades, instructors, and subjects at UW Madison since 2006

The objectives:

1.	Do STEM fields have a statistically significant difference in the number of A's earned when compared to the humanities?
2.	Does your teacher have a statistically significant correlation with the number on A's earned in a course?
3.	Which subject has a significant difference in the number of A’s earned when compared to other subjects.
4.	Does the day of the week have a statistically significant correlation with the number of A's earned in a course?

Brake Down by question:

***

# 1.	Do STEM fields have a statistically significant difference in the number of A's earned when compared to the humanities?

<b>Method:</b>
Extract STEM & Humanities subjects. Then conduct one sample t-test on each. Then a two sample t-test on both to compare.

Random Sample are taken as to convert distributions to Normal, using CLT.

<b>Observations:</b>

Both STEM & Humanities had significantly more A’s than the sample population. As the P-values were extremely small.

Similarly, when comparing against each other. It was found that the STEM had significantly more A’s per class achieved than humanities.

The power showed by the analysis equated to 1.0 which would suggest an error in the analysis. As the would say there is 100% no chance of a type 2 error.  Which is impossible.

A Mann-Whitney U test was conducted as the analysis of skewness showed the non-normal nature of the distributions. The result still gave an extremely high statistic when compared to the critical statistic. Still confirming a significance.

***


# 2.	Does your teacher have a statistically significant correlation with the number on A's earned in a course?

<b>Method:</b>
When observing the number of teachers there were over 18,000 teachers (instructors) in the data set. Therefore, 2 teachers were selected, of which one sample Z-test were conducted, due to the knowledge of the total population mean.

Thena two sample welch t-test to compare both, due to the different sample sizes.

Teacher 1: 	Donald Yandow
Teacher 2:	Ida Balderrama-Trudell


<b>Observations:</b>
Difficult as on two teacher were able to be selected. However if we wish to analysis a particular teacher we could. 


 ***

# 3.	Which subject has a significant difference in the number of A’s earned when compared to other subjects.

<b>Method & Observations:</b>

Initial we looked at the percentage A’s obtained for each subject over the total population.
From this the highest two, both with 100% A’s: Ophthalmology and Visual Sciences & Molecular Biology. The lowest being Botany & Biology with 24.5% and 27.5% respectively.

The total number of students taking the courses must be considered as Botany (1,621,174) has 4369 times more grades given than Ophthalmology and Visual Sciences (371).

Using a Tuckey’s HSD to compare all 192 subjects all together, which found;

Therapeutic Science (Department of Kinesiology) & Interdisciplinary Courses (Engineering)

Had statistically the most significance of achieving an A.

***

# 4.	Does the day of the week have a statistically significant correlation with the number of A's earned in a course?

<b>Method:</b>
The first objective was to work out the total number of A’s given for each day.

Mon: 	401317
Tues: 	376194
Wed: 	409313
Thurs:	354897
Fri:	273262
Sat:	47543
Sun:	385

From this it was chosen to exclude Sat & Sun, as there are not enough data point when compared to the other days of the week. Once again a one sample t test was used as the population mean is known.

A Tuckey’s HSD comparison was attempted. However, its failed due to lectures being held on multiple days. So could result in lectures being compared against themselves, which would skew the results towards no difference between the days.

<b>Observations:</b>

The one sample t-test showed that the there is a significant difference for all the day of the week. This is most likely due the large values pulling the mean of each of the days higher than the overall population. The skewness of all the population were highly positive.

Pop-Mean:	7.276
Mon: 		11.951
Tues: 		13.764
Wed: 		12.981
Thurs:		14.114
Fri:		12.247


***

## Conclusions:

The main issue is that the populations of each class could not be normalised which emphasised the effect of the large outlier values that pull the statically mean, make the results significant. This is apparent especially when comparing between subjects.  The unknown number of students participating in each class is frustrating as we are unable to normalize the result. Nullify the majority of statistical tests.

Additionally, even between subjects as grades between, for example, lectures and seminars are difficult to compare.

The data set does not provide the total number of students per class only the grades achieved. so cannot account for the number of other faliures. Or for the year of each course.
So courses only running for one year will have far less students or for instance the weighting between course which were fully lecture to ones that are fully course work.
