# GIB tutorial
Simple tutorial implementing a gaussian information bottleneck based on the great paper from Gal Chechik, Amir Globerson, Naftali Tishby, and Yair Weiss (JMLR 2005).
Starting from a joint Gaussian (X,Y), the problem is to find a linear projection A that compresses a variable X while preserving as much information as possible about Y. 
The tradeoff between compression and preservation is given by a parameter $\beta$. More details about the implementation and some examples are available in the notebook, while I refer the reader to the original paper for mathematical proofs: https://www.jmlr.org/papers/volume6/chechik05a/chechik05a.pdf
