# iris_clust
* dat=iris
* str(dat)
* table(complete.cases(dat))
* data<-scale(iris[,-c(5)])
* pmatrix=scale(dat[-c(5)])
* library(NbClust)
* res.nb<-NbClust(pmatrix,min.nc = 2,max.nc =10,method ="complete" )

## Among all indices:                                                
* 2 proposed 2 as the best number of clusters 
* 18 proposed 3 as the best number of clusters 
* 3 proposed 10 as the best number of clusters 
                   ***** Conclusion *****                            
 * According to the majority rule, the best number of clusters is  3
