
# Gradient Descent#

  

This repository contains the code for implementing Gradient Descent algorithm in R.

**Files**

  

(1) gradient_descent.R: This file contains the implementation of Gradient Descent algorithm in R.
  

**Usage**

  

To use the Gradient Descent algorithm in R, you can simply source the gradient_descent.R file in your R script.

  



  
<code>
source("gradient_descent.R")
</code>
  

#  Example usage

```
g <- function(w0, w1) {

return(
2 + w0 + w1 + 3*w0*w1 + 7.5*w0^2 + 1.25*w1^2
)

}

  g_prime <- function(w0, w1) {

return(

rbind(c(

1 + 5*w0 + 3*w1,

1 + 3*w0 + 2.5*w1

))

)

}
```
  

**Contributions**

  

Contributions to this repository are welcome. If you find a bug or have a suggestion for improvement, please create an issue or submit a pull request.

**License**

 

This repository is licensed under the MIT License. See the LICENSE file for more details.
