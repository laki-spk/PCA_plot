# PCA_plot
From RNA expression data and protein abundance data matrix

For this the data sheet should looks like below:

> # Check structure
> head(expr_raw)

               C2        C3      C_H1     C_H2      C_H3        N1        N2        N3      N_H1      N_H2      N_H3
A1bg     0.000000  0.000000  0.000000  0.00000  0.000000  0.000000  0.000000  0.000000  0.000000  0.000000  0.000000
A1cf     0.038348  0.000000  0.000000  0.00000  0.000000  0.000000  0.000000  0.000000  0.000000  0.000000  0.000000
A1i3     0.000000  0.000000  0.000000  0.00000  0.000000  0.000000  0.000000  0.000000  0.000000  0.000000  0.000000
A2m      0.078948  0.000000  0.047064  0.00000  0.000000  0.000000  0.000000  0.000000  0.000000  0.000000  0.000000
A3galt2  9.316925  8.803477 11.778751 11.46591 12.285809  4.806355  3.674184  4.525602  5.333035  5.701357  5.178183
A4galt  15.397491 12.866089 11.208944 10.15715  9.835147 11.571400 10.199619 10.541862 12.152280 10.502377 10.204833


Where samples are in C1.....N_H3 and gene list is in the first column


And if using protein abundance data we should normalized it to the total protein count of the sample first.
File should be saved as a csv file
