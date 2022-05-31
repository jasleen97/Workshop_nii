# Workshop_nii


```{R Basics}
hello <- function(){
  print('Hello World')
  }
  hello()
  
  a <- 1
  a
  b <- 10
  b
  a+b 
  
  gene_name <- "tp53"
  genes <- c('A','B','C')
  
  # access elements
  genes [2]
  genes[-3]
  
  double_name ('aa','bb','cc')
  names(genes)<- double_name
  genes
  
  pathway_x <- c('aa','cc')
  genes[pathway_x]
  
  XYZ <- c(xx='XX', yy='YY', zz='ZZ')
  XYZ
  lenght(XYZ)
  updated_XYZ <- c(ww='WW',XYZ)
  
  LG <- c(TRUE,FALSE,TRUE)
  genes[LG]
  genes[!LG]

 dataframe(geneName = c('aa','bb','cc'), geneSymbol = c('A','B','C'), geneExpr =c(10,6,16))
 geneDF <- data.frame(geneName = c('aa','bb','cc'), geneSymbol = c('A','B','C'), geneExpr =c(10,6,16))
 geneDF[2,2]
 geneDF[2,]
 geneDF[2]
 geneDF[,2]
 
 x <- c('a','b','b','c','c')
 factor(x)
 
 geneDF2 <- cbind(geneDF,geneB = c(1,5,7))



```

# Exercise (DAY2)

# 1.Why does this code not work?

1 instead of i the word variable.

The below code work instead:
my_fav_variable <- c('IL6','LINC','OAS1')
my_fav_variable

# 2.Write a R code to create a character vector of your favorite pathway.

JK_ISP_mTOR <- c('IRS1/2','PI3K','Akt','mTOR')
JK_ISP_mTOR

