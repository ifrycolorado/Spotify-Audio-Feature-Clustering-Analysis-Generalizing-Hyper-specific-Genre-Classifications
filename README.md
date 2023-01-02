# Spotify-Audio-Feature-Clustering-Analysis-Generalizing-Hyper-specific-Genre-Classifications
A collection of code and writing about research done on Spotify's genre clustering tendencies. 


As one of the world’s top music streaming services, Spotify’s data infrastructure is immense and
thoroughly engineered. Spotify’s data backend boasts the ability to classify songs with an extreme
degree of precision, assigning anywhere from 3 to 10 different genres to a single track. However, this
hyper-specificity can hinder the communication of a track’s genre to an average music listener.

My research utilizes K-Means Clustering on an open-source dataset that cross-references the Billboard
Hot 100 charts from 1958-2020 to Spotify’s audio features. By leveraging Principal Component Analysis
on a set of Spotify audio features, I reduce 1042 unique genres into k = 3 and k = 10 genre clusters.
Each cluster is defined by a relatively distinct accumulation of genres, and the cluster centers indicate
the general archetypal song for that genre cluster.
