---
course_id: 15-071-the-analytics-edge-spring-2017
layout: course_section
parent_title: '1.3 Working with Data: An Introduction to R '
title: '1.3 Working with Data: An Introduction to R '
type: course
uid: 85a26423d9d75842c382af54b0eaaadd

---

*   [<Video 5: Data Analysis - Summary Statistics and Scatterplots]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-5-data-analysis-summary-statistics-and-scatterplots)
*   [1.3.1Download and Install R]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r)
*   [1.3.2Video 1: Why R?]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-1-why-r)
*   [1.3.3Quick Question]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/quick-question)
*   [1.3.4Video 2: Getting Started in R]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-2-getting-started-in-r)
*   [1.3.5Quick Question]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/quick-question-4)
*   [1.3.6Video 3: Vectors and Data Frames]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-3-vectors-and-data-frames)
*   [1.3.7Quick Question]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/quick-question-9)
*   [1.3.8Video 4: Loading Data Files]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-4-loading-data-files)
*   [1.3.9Quick Question]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/quick-question-20)
*   [1.3.10Video 5: Data Analysis - Summary Statistics and Scatterplots]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-5-data-analysis-summary-statistics-and-scatterplots)
*   [1.3.11Quick Question]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/quick-question-28)
*   [1.3.12Video 6: Data Analysis - Plots and Summary Tables]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-6-data-analysis-plots-and-summary-tables)
*   [1.3.13Quick Question]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/quick-question-40)
*   [1.3.14Video 7: Saving with Script Files]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-7-saving-with-script-files)
*   [\>Video 6: Data Analysis - Plots and Summary Tables]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-6-data-analysis-plots-and-summary-tables)

Quick Question
--------------

Please answer the following questions using the entire data frame WHO (and not one of the subsets we have created in R).

What is the mean value of the "Over60" variable?

Exercise 1

&nbsp;Numerical Response&nbsp;

Explanation

You can compute this value by either typing mean(WHO$Over60) in your R console, or by typing summary(WHO$Over60) in your R console. The output is 11.16.

Which country has the smallest percentage of the population over 60?

Exercise 2

&nbsp;Japan&nbsp;

&nbsp;United Arab Emirates (UAE)&nbsp;

&nbsp;Sierra Leone&nbsp;

&nbsp;Cuba&nbsp;

&nbsp;Luxembourg&nbsp;

&nbsp;Mali&nbsp;

Explanation

To get this value, you should type which.min(WHO$Over60) in your R console. The output is 183. Then, to see the name of the 183rd country in your data frame, type WHO$Country\[183\] in your R console. The output is United Arab Emirates.

Which country has the largest literacy rate?

Exercise 3

&nbsp;Japan&nbsp;

&nbsp;United Arab Emirates (UAE)&nbsp;

&nbsp;Sierra Leone&nbsp;

&nbsp;Cuba&nbsp;

&nbsp;Luxembourg&nbsp;

&nbsp;Mali&nbsp;

Explanation

To get this value, you should type which.max(WHO$LiteracyRate) in your R console. The output is 44. Then, to see the name of the 44th country in your data frame, type WHO$Country\[44\] in your R console. The output is Cuba.

CheckShow Answer

*   [BackVideo 5: Data Analysis - Summary Statistics and Scatterplots]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-5-data-analysis-summary-statistics-and-scatterplots)
*   [ContinueVideo 6: Data Analysis - Plots and Summary Tables]({{< baseurl >}}/sections/an-introduction-to-analytics/working-with-data-an-introduction-to-r/video-6-data-analysis-plots-and-summary-tables)