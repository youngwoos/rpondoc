# rpondoc

`rmarkdown` 문서를 `Knit`했을 때 알 수 없는 문제가 발생할 경우 `rpondoc` 패키지를 설치한 후 `install_pandoc()`을 실행하세요. 

```
# install.packages("remotes")
remotes::install_github("https://github.com/youngwoos/rpondoc")

library(rpondoc)
install_pandoc()
```


Source from link below
<https://github.com/rstudio/rstudio/issues/4072#issuecomment-473406177>
