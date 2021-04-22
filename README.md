Simple linear Regrression explained with example

The maths we come across in schooling is the math behind linear Regression 


we all know the slope intercept formula 
 

              y = mx +c 
              


To get the intercept and slope values we calculate thme by calculating the mean of dataset 
we dont usually do it manually but the libraries are going to do for us but the curiosity for behind the model statistics its necesaary for us to learn 
mean_x = sum((x[i]- sum(x)/number of observations )

mean_y =  sum(y)/number of observations ) 

m = sum(x[i]-mean_x)*(sum(y[i] -mean_y) / (sum(x[i] - mean_x)**2

                                where i = ith observation of the data 
																																
c = mean_y = m* (mean_x)

