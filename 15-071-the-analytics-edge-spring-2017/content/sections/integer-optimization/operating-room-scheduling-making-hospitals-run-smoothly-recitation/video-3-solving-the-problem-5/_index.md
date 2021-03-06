---
course_id: 15-071-the-analytics-edge-spring-2017
layout: course_section
parent_title: '9.4 Operating Room Scheduling: Making Hospitals Run Smoothly  (Recitation)'
title: '9.4 Operating Room Scheduling: Making Hospitals Run Smoothly  (Recitation)'
type: course
uid: 162e5921904a950780e7596c005168c3

---

*   [<Video 2: An Optimization Model]({{< baseurl >}}/sections/integer-optimization/operating-room-scheduling-making-hospitals-run-smoothly-recitation/video-2-an-optimization-model)
*   [9.4.1Welcome to Recitation 9]({{< baseurl >}}/sections/integer-optimization/operating-room-scheduling-making-hospitals-run-smoothly-recitation)
*   [9.4.2Video 1: The Problem]({{< baseurl >}}/sections/integer-optimization/operating-room-scheduling-making-hospitals-run-smoothly-recitation/video-1-the-problem)
*   [9.4.3Video 2: An Optimization Model]({{< baseurl >}}/sections/integer-optimization/operating-room-scheduling-making-hospitals-run-smoothly-recitation/video-2-an-optimization-model)
*   [9.4.4Video 3: Solving the Problem]({{< baseurl >}}/sections/integer-optimization/operating-room-scheduling-making-hospitals-run-smoothly-recitation/video-3-solving-the-problem-5)
*   [9.4.5Video 4: The Solution]({{< baseurl >}}/sections/integer-optimization/operating-room-scheduling-making-hospitals-run-smoothly-recitation/video-4-the-solution)
*   [\>Video 4: The Solution]({{< baseurl >}}/sections/integer-optimization/operating-room-scheduling-making-hospitals-run-smoothly-recitation/video-4-the-solution)

Video 3: Solving the Problem
----------------------------

In this video, we'll be using the spreadsheet Recitation\_ORscheduling. If you are using LibreOffice or OpenOffice, please download and open the file [ORscheduling (ODS)](/coursemedia/15-071-the-analytics-edge-spring-2017/0b29d789102df82347256ff5f1e8a2e5_ORscheduling.ods). If you are using Microsoft Excel, please download and open the file [ORscheduling (XLSX)](/coursemedia/15-071-the-analytics-edge-spring-2017/c2d77b4a52ea41b7fbbda781bfb50ed0_ORscheduling.xlsx). The following spreadsheets have the completed model as it is at the end of the video: [ORscheduling\_Complete (ODS)](/coursemedia/15-071-the-analytics-edge-spring-2017/f9d0e9bcadbcf7fab487085230efbceb_ORscheduling_Complete.ods) and [ORscheduling\_Complete (XLSX)](/coursemedia/15-071-the-analytics-edge-spring-2017/d0646520c0ac9a08bcbefcfc16e416ee_ORscheduling_Complete.xlsx).

If you are using Excel, remember that you can indicate that the decision variables should be integer by adding an additional constraint, like we did in the Sports Scheduling lecture. Also, make sure to set a time limit by going into Options, and then in the Solving Limits section, setting Max Time to 100. The solver will probably give you the following message after 100 seconds: "The maximum time limit was reached; continue anyway?" Go ahead and select Stop, and then select Okay. Even though the solver was not able to prove that this solution is the optimal one, you should see an objective function value of 4.46. If you don't set a time limit, it might take Excel over 10 minutes to settle on the optimal solution!

Also, you might get a different solution than the one Angie gets in the following video. There are _multiple optimal solutions_ to this problem, so your solution might be another feasible solution with the optimal objective function value. You'll see in the next video how the constraints can be adjusted to find the optimal solution that better fits the problem. 

{{< youtube ayrdDJPAD5M >}}

*   [BackVideo 2: An Optimization Model]({{< baseurl >}}/sections/integer-optimization/operating-room-scheduling-making-hospitals-run-smoothly-recitation/video-2-an-optimization-model)
*   [ContinueVideo 4: The Solution]({{< baseurl >}}/sections/integer-optimization/operating-room-scheduling-making-hospitals-run-smoothly-recitation/video-4-the-solution)