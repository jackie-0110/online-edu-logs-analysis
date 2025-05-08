# online-edu-logs-analysis
Clustering and regression analysis on RIIID education logs to identify student difficulties.
___

### Abstract
The purpose of this material is to accurately make predictions on student performance to
tailor their education to their ability. Riiid is the source company, an AI EdTech company
based in South Korea. Enabling higher efficiency in education improves student
outcomes, which in turn opens doors for social mobility. Meeting students with support
for exactly where they're struggling is an efficient use of both the student and educators
time. This is important to educators, students, parents, and nearly everyone with a stake
in education.


K-Means Clustering as well as a regularized least squares model was implemented. The
k-means clustering revealed performance groups by capturing variation in accuracy,
standard deviation, and number of attempts. The regularized least squares yielded with
$\lambda=0.01$ achieved ~80.7\% accuracy and 100\% precision in predicting student success. Feature engineering was required on the original data to include metrics
such as mean accuracy, consistency trends, and effectiveness to train the model. These
findings suggest that predictive modeling with performance-based clustering can support
the development of personalized education strategies, since educators can reliably
determine whether a student needs help or falls within a performance group that is classified as intervention needing.

### Methodology 
___
Analaysis was implemented entirely within Julia. Libraries included were DataFrames.jl, Statistics.jl, LinearAlgebra.jl, Clustering.jl, CSV.jl, Random.jl, and PlotlyJS.jl for visualization.