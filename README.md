# iris_clust
## dat=iris
str(dat)
table(complete.cases(dat))
data<-scale(iris[,-c(5)])
pmatrix=scale(dat[-c(5)])
library(NbClust)
res.nb<-NbClust(pmatrix,min.nc = 2,max.nc =10,method ="complete" )
