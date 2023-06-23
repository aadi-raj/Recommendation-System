# Recommendation-System
This will contain all the experiments done for building robust recommendation system.

# Current Progress
CF_KNN file contains recommendation based on collaborative filtering approach. This has its own limitations like it it needs viewer specific data in order to perform well. Content based filtering focuses on the tastes of a single viewer, recommending content that is similar to things the viewer has liked in the past. After gathering data on multiple users' preferences a collaboarative filtering strategy can make recommendations to a viewer based on content that has been liked by other viewers with similar tastes.


In each case, the need for collecting viewer specific data diminishes the effectiveness of these systems until such data can be gathered. This is typically referred to as the 'cold start problem'. Furthermore, if the audience is anonymous, in the sense that it is not possible to identify returning viewers, then it is not possible to generate viewer-specific recommendations using these techniques because the necessary data cannot be acquired. 

Multi-armed bandit algorithms and A/B testing strategies are two potential ways to confront these challenges.
