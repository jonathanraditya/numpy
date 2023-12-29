# Numpy library implementation

My personal notes of Numpy examples

1. Numpy reshape with negative value `.reshape(-1)` or any variations `.reshape(-1,x,y)`. `-1` is a sign that tells numpy to fit any possible dimension to keep all avaibale original value. The maximum occurence of `-1` during function call is 1. We should state the other dimension with the value of our choice, and we let numpy to fill the missing value to satisfy the dimensionality.
