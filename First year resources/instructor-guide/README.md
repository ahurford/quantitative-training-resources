The key is the `site` setting in `index.Rmd`. If you want to build the book in RStudio, just click the `Build Book` button in the `Build` pane, otherwise call the function in R:

```r
bookdown::render_book('index.Rmd', 'all')
```
