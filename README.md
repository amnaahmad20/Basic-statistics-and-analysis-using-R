# Basic Statistics and Analysis using R

Implementation of basic stats and descriptive analytics on S&P 500 and BTC-USD dataset.

## Setup Instructions

### Installing R

#### For macOS and Linux:
```bash
brew install r
```
#### For Windows:
Go to the [CRAN website](https://cran.r-project.org/) and follow the instructions.

## Cloning the Repository
```bash
git clone <repository_url>
```
## Running in Google Colab

1. Open Google Colab.
2. Upload all the files there.
3. Change runtime to R.
4. You can run all the code.

## Converting to R Markdown

```R
library(rmarkdown)
rmarkdown::convert_ipynb('/content/notebook_name.ipynb')
```
## Converting to HTML
```R
render("/content/R_analysis.Rmd")
```
## Running in R Studio/Local Environment

**Convert to HTML:**

   ```bash
   Rscript -e "rmarkdown::render('Updated_R_analysis_Optimized.Rmd')"
```
Alternatively, open .Rmd file in R Studio and click on the "Knit" option (make sure to select Rmd to HTML).
## Using Cloud R Studio

You can also use cloud R Studio and follow the same steps for R Studio. [Posit Cloud](https://posit.cloud/) is one such option.

