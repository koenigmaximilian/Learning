# Learning

A micro library containing the most common machine learning tools
written in Haskell.

The name of the package can be interpreted in two ways:

1. Either as "Learning" in "Machine Learning".
2. Or "Learning" meaning that examples* are written
in literate style and can be used to discover ML techniques.

*) Work in progress


## Getting Started

Use [Stack](http://haskellstack.org).

     $ git clone https://github.com/masterdezign/Learning.git && cd Learning
     $ stack build --install-ghc

### Demo 1: principal components analysis (PCA)

Launch the [PCA demo](https://github.com/masterdezign/Learning/blob/master/app/MainPCA.lhs)

     $ stack exec learning-pca

### Demo 2: advanced principal components analysis (PCA)

Launch the advanced [PCA demo](https://github.com/masterdezign/Learning/blob/master/app/MainPCA2.lhs)

     $ stack exec learning-pca-advanced
