# Topsis - Technique for Order Preference by Similarity to Ideal Solution
## Algorithm Steps

1.  Computing normalised alternative matrix. (Alternative matrix divided by calculated norm of each column).
2.  Computing weighted normalised alternative matrix. (Alternative matrix multiplied by eigenvector).
3.  Calculating the ideal solution. (An hypothetical alternative that maximises benefits and minimises costs the most).
4.  Calculating the anti-ideal solution. (An hypothetical alternative that minimises benefits and maximises costs the most).
5.  For each alternative in the weighted normalised alternative matrix, calculate the euclidean distance to the ideal and anti-ideal solution.
6.  Calculate a performance score for each alternative. (Distance to the anti-ideal solution divided by the sum of the distance of the ideal and anti-ideal solution).
7.  Rank in descending order performance scores for each alternative.
8.  Return the top-one.
