# Fractal-Analysis-of-a-time-series

Here I did an exploratory fractal analysis of the data that consisit of two signals; Signal 1 and Signal 2 labelled as three classes A, B, C. 
Based on the analysis, I wanted to understand which class of data is more complex and why. Therefore, the analysis also includes a statistical comparison of the 3 classes and the choosen methods.

Fractal analysis is a contemporary method of applying nontraditional mathematics to patterns that defy understanding with traditional Euclidean concepts. Basically, it measures complexity using fractal dimensions. The fractal dimension measures the change in "size" of a fractal set with the changing observational scale, and is not limited by integer values.

There are various methods of fractal analysis; the ones used to analyse this dataset are DFA(Detrended Fluctuation Analysis), Higuchi Fractal Dimension, Katz Fractal Dimension,Hurst Exponent and Permutation Entropy.

Here I found the Hurst exponent to be the most helpful and easier to understand and the one to give the best result for this dataset is Katz FD to a certain extent. Since Higuchi FD and Permutation Entropy is highly sensitive to noise therefore it might not have yielded the best results for this large dataset.
