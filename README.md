# Manhattan
# Language: R
# Input: CSV (abundances)
# Output: CSV (dissimilarities)
# Tested with: PluMA 1.1, R 4.0.0
# Dependency: vegan_2.5.6

PluMA plugin to compute dissimilarity between data samples, using Manhattan distance as a metric.
The plugin accepts an input CSV file with rows representing samples and columns community members,
and entry (i, j) contains the abundance of member j in sample i.  It will produce as output a CSV
file with rows and columns representing samples and entry (i, j) the dissimilarity level between
sample i and sample j.


