# helloJavaWorld
Tutorial from https://cran.r-project.org/web/packages/helloJavaWorld/vignettes/helloJavaWorld.pdf. 

The package we will create in this tutorial, the helloJavaWorld package, will invoke a very simple Java class, the HelloJava-
World class, from inside an R function of the package, the helloJavaWorld
function. The objective is to help other people to make available Java algo-
rithms to the R world, be it to compare results, or for their own sake.

To download the R library and corresponding CoreNLP java library, run the following in R:

```
devtools::install_github("anavaldi/helloJavaWorld")
```

Then, in order to run the package, the following code initializes rJava correctly (if run from the same directory as the above):

```
library(rJava)
library(helloJavaWorld)
```

And demonstrate it by simply calling:

```
helloJavaWorld()
[1] "Hello Java World!"
```

