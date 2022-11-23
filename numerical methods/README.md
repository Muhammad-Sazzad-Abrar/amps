## Fitting a curve to 9 points using Lagrange interpolating polynomial  
Suppose we wish to find the curve that goes through 9 points. The 9 points are shown below.  


![](https://raw.githubusercontent.com/yakeen15/amps/main/numerical%20methods/points.PNG)
  
To find this graph which would join all these points, we could use [Lagrange interpolating polynomial](https://en.wikipedia.org/wiki/Lagrange_polynomial#:~:text=In%20numerical%20analysis%2C%20the%20Lagrange,a%20given%20set%20of%20data.). Using the lagrange.cpp file, we could enter any number of points less than 100, in order to get the coefficients of Lagrange interpolating polynomial, which we could then feed into our python plotting scripts located [here](https://github.com/yakeen15/amps/tree/main/plotting%20and%20graphs) in order to plot the points and the polynomial joining them.