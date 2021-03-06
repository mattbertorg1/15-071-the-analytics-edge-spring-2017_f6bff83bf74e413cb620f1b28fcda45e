---
course_id: 15-071-the-analytics-edge-spring-2017
layout: course_section
parent_title: '6.2 Recommendations Worth a Million: An Introduction to Clustering '
title: '6.2 Recommendations Worth a Million: An Introduction to Clustering '
type: course
uid: 4d3cfab69136623b888a5451d2fad159

---

*   [<Video 7: Hierarchical Clustering in R]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-7-hierarchical-clustering-in-r)
*   [6.2.1Video 1: Introduction to Netflix]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering)
*   [6.2.2Quick Question]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/quick-question-433)
*   [6.2.3Video 2: Recommendation Systems]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-2-recommendation-systems)
*   [6.2.4Quick Question]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/quick-question-438)
*   [6.2.5Video 3: Movie Data and Clustering]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-3-movie-data-and-clustering)
*   [6.2.6Quick Question]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/quick-question-446)
*   [6.2.7Video 4: Computing Distances]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-4-computing-distances)
*   [6.2.8Quick Question]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/quick-question-451)
*   [6.2.9Video 5: Hierarchical Clustering]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-5-hierarchical-clustering)
*   [6.2.10Quick Question]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/quick-question-458)
*   [6.2.11Video 6: Getting the Data]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-6-getting-the-data)
*   [6.2.12Quick Question]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/quick-question-466)
*   [6.2.13Video 7: Hierarchical Clustering in R]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-7-hierarchical-clustering-in-r)
*   [6.2.14Quick Question]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/quick-question-476)
*   [6.2.15Video 8: The Analytics Edge of Recommendation Systems]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-8-the-analytics-edge-of-recommendation-systems)
*   [\>Video 8: The Analytics Edge of Recommendation Systems]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-8-the-analytics-edge-of-recommendation-systems)

Quick Question
--------------

Run the cutree function again to create the cluster groups, but this time pick k = 2 clusters. It turns out that the algorithm groups all of the movies that only belong to one specific genre in one cluster (cluster 2), and puts all of the other movies in the other cluster (cluster 1). What is the genre that all of the movies in cluster 2 belong to?

Exercise 1

&nbsp;Action&nbsp;

&nbsp;Adventure&nbsp;

&nbsp;Animation&nbsp;

&nbsp;Children's&nbsp;

&nbsp;Comedy&nbsp;

&nbsp;Crime&nbsp;

&nbsp;Documentary&nbsp;

&nbsp;Drama&nbsp;

&nbsp;Fantasy&nbsp;

&nbsp;Film Noir&nbsp;

&nbsp;Horror&nbsp;

&nbsp;Musical&nbsp;

&nbsp;Mystery&nbsp;

&nbsp;Romance&nbsp;

&nbsp;Sci-Fi&nbsp;

&nbsp;Thriller&nbsp;

&nbsp;War&nbsp;

&nbsp;Western&nbsp;

Explanation

You can redo the cluster grouping with just two clusters by running the following command:

clusterGroups = cutree(clusterMovies, k = 2)

Then, by using the tapply function just like we did in the video, you can see the average value in each genre and cluster. It turns out that all of the movies in the second cluster belong to the drama genre.

Alternatively, you can use colMeans or lapply as explained below Video 7.

CheckShow Answer

*   [BackVideo 7: Hierarchical Clustering in R]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-7-hierarchical-clustering-in-r)
*   [ContinueVideo 8: The Analytics Edge of Recommendation Systems]({{< baseurl >}}/sections/clustering/recommendations-worth-a-million-an-introduction-to-clustering/video-8-the-analytics-edge-of-recommendation-systems)