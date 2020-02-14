## ML1000-1
York University. ML1000 - Machine Learning in Business Context. Assignment #1 - Classification Problem

## Project Structure

* Project presentation document: **telco_customer_churn**.  
* **data** folder contains the project data sets and trained model file. 
* **source** folder contains the script that generates the report.
* **rsconnect** folder includes the shiny app deployment files.

To run the project code:

* set the working directory to *./source*
* open *main.Rmd*. Please make sure that you install all required packages; they are listed at the beginning of the script. It is assumed that all R Markdown dependencies are satisfied, including the libraries that do conversion to the *PDF* format. Execute the script.


## Shiny App

URL: [Telco customer churn Analysis](https://li-ketao.shinyapps.io/customer-churn/)

To run the application locally, just execute:
```r
rmarkdown::run("customer_churn.rmd")
```
