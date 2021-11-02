# sanjay_data
library(dslabs)
library(tidyverse)
data("murders")
head(murders)
murders %>% ggplot(aes(region, total))+geom_boxplot()
