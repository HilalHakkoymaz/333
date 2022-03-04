# 333
test
# HOMEWORK 3
## Q.2 Stroop, standing up or sitting down
### Fit an appropriate model to Stroop standing data

```{r, fig.height = 3}
tibble(x = seq(-3, 3, 0.01),  y= dnorm(x)) %>% ggplot(aes(x, y)) + geom_path() + theme_bw() +
  scale_x_continuous(breaks = NULL)
```
