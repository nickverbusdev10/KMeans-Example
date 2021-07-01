# KMeans-Example

This code will reduce the number of colors in a picture down to the k clusters requested.

As the number of clusters increase so too does the computational complexity

for k > 50 (also known here as n_clusters > 50) on a casual personal computer I recommend reducing the number of iteration by adding KMeans(n_clusters = x_1, max_iter = x_2) where the max_iter default is 300

ram usage will be high as k increases, be prepared in the larger cases (for me when I ran k = 100) up to 10 GB of ram

you can use your own picture but as the resolution increases the complexity increases so be aware.

to read more about algorithm  https://arxiv.org/abs/0904.1113

