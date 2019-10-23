library(plotly)
library(dplyr)


career <- read.csv("~/Desktop/Career_Statics/career.csv")
table(career$公司名稱)
typeof(table(career$公司名稱))

career %>% plot_ly(x = .$公司名稱, type = "histogram")
career %>% plot_ly(labels = .$行業別, type = "pie")
career %>% plot_ly(x = .$英語能力, type = "histogram")
career %>% plot_ly(x = .$最低薪資, type = "histogram")


library(qcc)
data <- c(20,26,8,14,12)
names(data) <- c("A", "B", "C", "D", "E")
pareto.chart(data, las=1)
