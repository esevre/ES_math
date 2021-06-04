# Erik's Math Library

# quick look

Everything is in the namespace `ES::math`
There may be sub-namspaces as needed. At some point I hope to add more documentation to this readme.

# Eigen
For matrix based calculations I am using Eigen. At some point I will add more support for more matrix stuff.
At the moment I am more interested in basic ideas than squeezing out every ounce of performance. 
Such HPC updates can come later.

My Eigen code is being used as a submodule from:
[Eigen: https://gitlab.com/libeigen/eigen.git](https://gitlab.com/libeigen/eigen.git)

This submodule has been added to my project with the command
```shell
git submodule add https://gitlab.com/libeigen/eigen.git
```

