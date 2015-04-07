# shinyOfBagging
基于shiny的Bagging，使用到了`shiny`、`RWeaka`、`shinyAce`、`rmarkdown`、`ggplot2`、`gridExtra`、`knitr`等`R`package，使用方法为：
```R
if(!require(shiny)) {
  install.packages(pkgs = 'shiny',quiet = TRUE)
  require(shiny)
}
if(!require(RWeaka)) {
  install.packages(pkgs = 'RWeaka',quiet = TRUE)
  require(RWeaka)
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
runGitHub(username = 'guanlongtianzi',repo = 'shinyOfBagging') 
```
