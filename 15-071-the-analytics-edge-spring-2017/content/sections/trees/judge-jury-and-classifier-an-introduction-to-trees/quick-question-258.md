---
course_id: 15-071-the-analytics-edge-spring-2017
layout: course_section
parent_title: '4.2 Judge, Jury, and Classifier: An Introduction to Trees '
title: '4.2 Judge, Jury, and Classifier: An Introduction to Trees '
type: course
uid: 076a36ddc951926fd5c99ccb41e476d9

---

*   [<Video 2: CART]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-2-cart)
*   [4.2.1Video 1: The Supreme Court]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees)
*   [4.2.2Quick Question]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-253)
*   [4.2.3Video 2: CART]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-2-cart)
*   [4.2.4Quick Question]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-258)
*   [4.2.5Video 3: Splitting and Predictions]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-3-splitting-and-predictions)
*   [4.2.6Quick Question]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-267)
*   [4.2.7Video 4: CART in R]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-4-cart-in-r)
*   [4.2.8Quick Question]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-281)
*   [4.2.9Video 5: Random Forests]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-5-random-forests)
*   [4.2.10Quick Question]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-297)
*   [4.2.11Video 6: Cross-Validation]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-6-cross-validation)
*   [4.2.12Quick Question]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-306)
*   [4.2.13Video 7: The Model v. The Experts]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-7-the-model-v-the-experts)
*   [\>Video 3: Splitting and Predictions]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-3-splitting-and-predictions)

Quick Question
--------------

Suppose that you have the following CART tree:

![Example of a cart tree.](/coursemedia/15-071-the-analytics-edge-spring-2017/b2eea6fba57db424a4844f679aee4bc9_QQ2_SupremeCourt.png)

How many splits are in this tree?

Exercise 1

&nbsp;Numerical Response&nbsp;

For which data observations should we predict "Red", according to this tree? Select all that apply.

Exercise 2

&nbsp;If X is less than 60, and Y is any value.&nbsp;

&nbsp;If X is greater than or equal to 60, and Y is greater than or equal to 20.&nbsp;

&nbsp;If X is greater than or equal to 85, and Y is less than 20.&nbsp;

&nbsp;If X is greater than or equal to 60 and less than 85, and Y is less than 20.&nbsp;

Explanation

This tree has three splits. The first split says to predict "Red" if X is less than 60, regardless of the value of Y. Otherwise, we move to the second split. The second split says to check the value of Y - if it is greater than or equal to 20, predict "Gray". Otherwise, we move to the third split. This split checks the value of X again. If X is less than 85 (and greater than or equal to 60 by the first split) and Y is less than 20, then we predict "Red". Otherwise, we predict "Gray".

CheckShow Answer

*   [BackVideo 2: CART]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-2-cart)
*   [ContinueVideo 3: Splitting and Predictions]({{< baseurl >}}/sections/trees/judge-jury-and-classifier-an-introduction-to-trees/video-3-splitting-and-predictions)