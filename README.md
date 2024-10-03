# Module19-Challenge-CryptoClustering
Data Analytics Boot Camp - Module 19 - CryptoClustering \
Unsupervised Learning Challenge

---

# Results

Cryptocurrencies K-Means Clustering - results summary :
- The best value for 'k' was 4, for the 'Scaled Original' data.
- The 3 PCA variables explained 89.5% of the total variance.
- The best value of 'k' was 4 for the 'Scaled PCA' data.
    - The best value of 'k' did not differ, which further suggests the PCA version represents the original data well.
- Elbow curves were the same for both the 'Scaled Original' and 'Scaled PCA' cases.
- Scatter plots of the Clustering results showed each Crypto Coin is assigned to the same cluster number in either plot, and the respective clusters have the same number of points in them, so there is no impact of using fewer features to cluster the data using K-Means in this case.

Refer to the `Crypto_Clustering.ipynb` Jupyter Notebook for more details.

# References

The following references were used in the development of the solution for this Challenge.

## hvplot
- Composing Plots https://holoviz.org/tutorial/Composing_Plots.html

## Unsupervised Learning
- Class notes/student activity files for 'Unsupervised Learning', Monash University 'Data Analytics Boot Camp' including Jupyter Notebooks were used as as references and implementation guides.
