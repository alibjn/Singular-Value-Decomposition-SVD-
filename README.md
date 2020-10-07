Singular-Value-Decomposition-SVD-


(SVD) is a linear aljebra method that decomposes a matrix into tree resultant matrices to reduce information redundancy and noise,

A = U . Sigma . V^T

![1_4Vpi3CFxjLsyJ2zZsZfcCw](https://user-images.githubusercontent.com/66758522/95274209-14355980-083d-11eb-92c8-125c61aefac5.png)


Where  


A : The original Matrix , is the real m x n matrix that we wish to decompose.

U : left orthogonal matrix ; holds important ,nonredundant information about observations , is an m x m matrix.

Sigma : diagonal matrix ; contains all of the information about decomposition processes performed during the compression ,(often represented by the uppercase Greek letter Sigma) is an m x n diagonal matrix.

V^T : right orthogonal matrix ;holds important ,nonredundant information on features.

![Singular-value-decomposition-of-A-a-full-rank-r-b-rank-k-approximation](https://user-images.githubusercontent.com/66758522/95275070-70997880-083f-11eb-96b2-5a0010a732a0.png)


The SVD is used widely both in the calculation of other matrix operations, such as matrix inverse, but also as a data reduction method in machine learning. SVD can also be used in least squares linear regression, image compression, and denoising data.

-the advantages of using SVD .
                 
                    -SVD provides optimal representation of image by packing most of the information in few coefficients for a given image.
                    -Data Reduction
                    -Data-Driven -generalization of Fourier Transform (FFT) . 
                     "" The FFT is the most useful  transformations and all of the mathimatics based on sine and cosine expansions , and this technique is the last Generation  of                         computational Science, and engineering   was to use these mathimatical modes 'FFT' to map a system od interest into some new coordinate system where would                         become simple.""
                    - 'Tailord'    to specific problem .
                    - Matrix decomposition
                    - Simple \ Interpretable Linear Algebra
                    - good for "Big Data"
                    - extract  most important features (dominant)
                    - Strongly correlated 
