# 333
test
# HOMEWORK 3
## Q.2 Stroop, standing up or sitting down
### Fit an appropriate model to Stroop standing data

Let`s see the data!

```{r Stroop, warning = FALSE, message = FALSE, fig.height = 2, fig.width = 2}
library(tidyverse)
stroop_standing_data <- read_csv("R_homework/Homework_3/stroop_standing_data.csv")
view(stroop_standing_data)
str(stroop_standing_data)
df <- stroop_standing_data
```
