# shinyOfSTBagging
基于Bagging的自学习分类算法，shiny应用，使用到了`shiny`、`DMwR`、`shinyAce`、`rmarkdown`、`ggplot2`、`gridExtra`、`knitr`、`RWeka`等`R`package，使用方法为：
```R
if(!require(shiny)) {
  install.packages(pkgs = 'shiny',quiet = TRUE)
  require(shiny)
}
if(!require(DMwR)) {
  install.packages(pkgs = 'DMwR',quiet = TRUE)
  require(DMwR)
}
if(!require(RWeka)) {
  install.packages(pkgs = 'RWeka',quiet = TRUE)
  require(RWeka)
}
if(!require(shinyAce)) {
  install.packages(pkgs = 'shinyAce',quiet = TRUE)
  require(shinyAce)
}
if(!require(rmarkdown)) {
  install.packages(pkgs = 'rmarkdown',quiet = TRUE)
  require(rmarkdown)
}
if(!require(ggplot2)) {
  install.packages(pkgs = 'ggplot2',quiet = TRUE)
  require(ggplot2)
}
if(!require(gridExtra)) {
  install.packages(pkgs = 'gridExtra',quiet = TRUE)
  require(gridExtra)
}
if(!require(knitr)) {
  install.packages(pkgs = 'knitr',quiet = TRUE)
  require(knitr)
}
if(!require(ROCR)) {
  install.packages(pkgs = 'ROCR',quiet = TRUE)
  require(ROCR)
}
runGitHub(username = 'guanlongtianzi',repo = 'MachineLearningShinyApps',subdir='Self-Traing-Bagging') 
```
