# workspace
this text is entered in Rstudio
hahaha

library(dplyr)
crops_data <- read.table("/Users/tsuyu/Downloads/workspace/field_crops_1.csv", sep=",", header = TRUE)

crops_data$`Commodity` %>% 
  unique()     