---
course_id: 15-071-the-analytics-edge-spring-2017
layout: course_section
parent_title: '4.3 Keeping an Eye on Healthcare Costs: The D2Hawkeye Story '
title: '4.3 Keeping an Eye on Healthcare Costs: The D2Hawkeye Story '
type: course
uid: c679795eed4f1bd8079e7f008721cf38

---

*   [<Video 4: Error Measures]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-4-error-measures)
*   [4.3.1Video 1: The Story of D2Hawkeye]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story)
*   [4.3.2Quick Question]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-311)
*   [4.3.3Video 2: Claims Data]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-2-claims-data)
*   [4.3.4Quick Question]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-316)
*   [4.3.5Video 3: The Variables]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-3-the-variables)
*   [4.3.6Quick Question]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-321)
*   [4.3.7Video 4: Error Measures]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-4-error-measures)
*   [4.3.8Quick Question]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-326)
*   [4.3.9Video 5: CART to Predict Cost]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-5-cart-to-predict-cost)
*   [4.3.10Quick Question]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-337)
*   [4.3.11Video 6: Claims Data in R]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-6-claims-data-in-r)
*   [4.3.12Quick Question]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-342)
*   [4.3.13Video 7: Baseline Method and Penalty Matrix]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-7-baseline-method-and-penalty-matrix)
*   [4.3.14Quick Question]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-349)
*   [4.3.15Video 8: Predicting Healthcare Cost in R]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-8-predicting-healthcare-cost-in-r)
*   [4.3.16Quick Question]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-357)
*   [4.3.17Video 9: Results]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-9-results)
*   [\>Video 5: CART to Predict Cost]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-5-cart-to-predict-cost)

Quick Question
--------------

The image below shows the penalty error matrix that we discussed in the previous video.

![](/coursemedia/15-071-the-analytics-edge-spring-2017/2d20a1e450f8bd62006bf8e20477eb64_QQ4_PenaltyError.png)

We can interpret this matrix as follows. Suppose the actual outcome for an observation is 3, and we predict 2. We find 3 on the top of the matrix, and go down to the second row (since we forecasted 2). The penalty error for this mistake is 2. If for another observation we predict (forecast) 4, but the actual outcome is 1, that is a penalty error of 3.

What is the worst mistake we can make, according to the penalty error matrix?

Exercise 1

&nbsp;We predict 5 (very high cost), but the actual outcome is 1 (very low cost).&nbsp;

&nbsp;We predict 1 (very low cost), but the actual outcome is 5 (very high cost).&nbsp;

Explanation

The highest cost is 8, which occurs when the forecast is 1 (very low cost), but the actual cost is 5 (very high cost). It would be much worse for us to ignore an actual high cost observation than to accidentally predict high cost for someone who turns out to be low cost.

What are the "best" types of mistakes we can make, according to the penalty error matrix?

Exercise 2

&nbsp;Mistakes where we predict one cost bucket HIGHER than the actual outcome.&nbsp;

&nbsp;Mistakes where we predict one cost bucket LOWER than the actual outcome.&nbsp;

Explanation

We are happier with mistakes where we predict one cost bucket higher than the actual outcome, since this just means we are being a little overly cautious.

CheckShow Answer

*   [BackVideo 4: Error Measures]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-4-error-measures)
*   [ContinueVideo 5: CART to Predict Cost]({{< baseurl >}}/sections/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-5-cart-to-predict-cost)