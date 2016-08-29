# Functions and Data Structures

### Question 1

```
my.display<-function(x){
....
return(summary(x))
}
```

....could be replaced by `cat("Summary of input: \n")`

### Question 2

```
my.display(my.data)
```
What is the median of the data as shown by the my.display() function? 
*Sol: simply run the codes from question 1*

### Question 3

```
my.display(my.data,display=TRUE,type="hist")
```

*Bar chart, x, Frequency, Histogram of X*

### Question 4

```
my.display(my.data,display=TRUE,type="hist",prob=TRUE)
```

*Bar chart, x, Density, Histogram of X*

### Question 5

```
my.display(my.data,display=TRUE,type="density")
```
*Line chart, N = 200 Bandwidth = 0.309, Density, density.default(x=x)*

### Question 6

```
my.display(my.data,display=TRUE)
```
*No chart is displayed, instead "Please specify type as either hist or density" is printed*
