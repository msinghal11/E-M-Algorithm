# E-M-Algorithm


The purpose of the EM Algorithm is to estimate the unknown parameter of the proportion of DNA sequences truly from a species of interest.

__Formula.ipynb__:Uses Markdown to desribe the formulation under investigation.

__emalg.ipynb__: An in-construction version of the algorithm composed of deninput0(),numinput0(),deniter(),numiter(),completealg(), and dummy() functions. The most updated version of algorithm is in our dummy() function, which currently takes in an initial probability vector of length k (containing pre-determined probabilities for k different species) and works with test data. The input matrix is in the format of the test data.

__emalgdraft.ipynb__: A very condensed version of emalg with three functions: numinput0(), deninput0(), deniter(), numiter(), completealg(). This version, although condensed, lacks the ability to take in an initial probability vector,or use test data. 

__Stochastic_Matrix.ipynb__: Generates a matrix of probability vectors whose rows sum to 1.

__Test_Data.ipynb__: Generates a stochastic matrix with particular values of elements row-wise. Each row has "n" entries , and the entry with index of the true observation gets value 1-e. Every other index has equal probability e/n-1, where e = error rate. The #of rows represent the # of different sequence reads we are comparing. The # of columns represent the # of species.

__Working goals__:<br>Implement code in pandas to reduce amount of for loops and to condense code.   
            Add error messages for invalid arguments for "completealg" function.
            
