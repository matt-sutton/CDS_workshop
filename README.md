CDS Datathon Workshop
================

Let’s run a data-based challenge delivering a product built from
free/open-source tools and publicly available data.

The visualisation should allow users to interact and gain some *insight*
from the data using the tool.

### The Goal

Want to provide something to spark possible collaboration between QUT
researchers based on publicly available data. Looking around QUT Eprints
is a great source!

    Goal: Create a visuallisation of QUT researchers that people can view and interact with to find common coauthors

There are three pages (feel free to read ahead!) these will be linked at
the bottom of each page. These will cover the following necessary
skills:

1.  Getting the data *(Web Scraping)*
2.  Visualising network data *(Visualising)*
3.  Provide something interactive *(Shiny)*.

Example end product: <https://matt-sutton.shinyapps.io/CDSNetwork/>

### Tools we’ll need

R and Rstudio are my preferred software if you work with Python you may
be interested in beautiful soup and pyvis.

Install and load the required packages:

``` r
install.packages("shiny")
install.packages("visNetwork")
install.packages("rvest")
```

You’ll also need the following Chrome Extension
(<https://selectorgadget.com/>). Don’t worry if you can’t get this one
in the session you should be able to create the app without it.

### Important references

To build this tool and tutorial I made use of the excellent tutorials by
SAURAV KAUSHIK \[1\] for web scraping with R, \[4\] for building shiny
apps and \[3\] for visualizing data with a network.

### Next section

Let’s get started with web-scraping [Next section](web_scraping.md)

### References:

1.  SAURAV KAUSHIK, March, 2017:
    <https://www.analyticsvidhya.com/blog/2017/03/beginners-guide-on-web-scraping-in-r-using-rvest-with-hands-on-knowledge/>

2.  DENIS KRYUKOV,September, 2019:
    <https://soshace.com/responsible-web-scraping-gathering-data-ethically-and-legally/>

3.  <https://datastorm-open.github.io/visNetwork/>

4.  <https://shiny.rstudio.com/tutorial/written-tutorial/lesson1/>
