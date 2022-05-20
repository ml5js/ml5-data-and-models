## Gaussian 2D Clusters

Each CSV contains a set of 2-dimensional x, y points to use as input data for a clustering model, such as `KMeans` or `DBSCAN`.  All values are normalized to the range `[0, 1]`.

`2-clusters.csv`, `3-clusters.csv`, and `4-clusters.csv` contain points which are distributed around 2, 3, or 4 cluster centers using a Gaussian distribution. 

`circle.csv` and `moon.csv` contain points which create abnormally shaped clusters. `circle.csv` creates a "bullseye" of two concentric circles while `moon.csv` creates two interlocking "crescent moon" parabolas.

The `metadata.json` file contains the filename and cluster count "k" for each dataset.
