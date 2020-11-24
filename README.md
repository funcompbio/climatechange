# Project climate change - FCB 2020

## Summary

In this project you should analyse data to attempt answering the following questions:

> Has there been a change in the Earth's surface temperature over the last 50 years?

> Could the change in Earth's surface temperature be driven by changes in the atmospheric CO2 concentration?

> Which countries are the main CO2 emitters?

> Can you find examples of countries that are reducing their CO2 footprint? And increasing it?

## Data

You should use the following two datasets:

1. The CSV file [temperature_per_country.csv](temperature_per_country.csv) downloaded from
[here](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data)
and produced by [The Berkeley Earth Surface Temperature Study](https://berkeleyearth.org),
which combines 1.6 billion temperature reports.

2. The CSV file [carbon_per_country.csv](carbon_per_country.csv) downloaded from
[here](https://datahub.io/core/co2-fossil-by-nation) and produced by the
[Carbon Dioxide Information Analysis Center](https://cdiac.ess-dive.lbl.gov),
containing CO2 emissions from fossil fuels since 1751.

## Deliverables

The GitHub repo for this project should contain, at least, the following files:

  * `index.Rmd`: R Markdown script with the R code doing the analysis of the data
    and the corresponding text explaining those analysis steps.
  * `index.html`: Resulting HTML output from processing (_knitting_) the file
    `index.Rmd`.
  * The CSV files employed during the analysis.

The analysis of the data described in the HTML file should contain the following
sections:

  * **Abstract:** Summary of the question and the findings (max. 200 words).
  * **Introduction:** Description of the question and the data employed to answer it.
    Description of any steps taken, if any, previous to this R Markdown document,
    to prepare the data that is being analyzed.
  * **Results:** R code intertwined with text, descriping the analysis steps and the
    display items with the results, which should consist, **at least**, of one table
    and one plot.
  * **Conclusions:** summary of the findings, limitations of the study, ways in which
    this type of study could be improved in the future.
  * **References:** bibliographic references.

## Methodology

The analysis of the data should be carried out at least using R, but you can also
use shell or Python scripts to transform or prepare the data for the analysis with
R. If those prior steps using shell or Python scripts are included, they should be
described in the introduction section of the R Markdown document and, ideally,
made readily reproducible using a Makefile.

## Evaluation rubric

The rubric to evaluate this project consists of the following items:

* Does the GitHub repo contain at least the analysed CSV files along with the
  `index.Rmd` file and the resulting `index.html`?

* Does the R Markdown file `index.Rmd` run the analysis without errors and
  generates the expected `index.html` file?

* Does the analysis described in the resulting `index.html` file conform to
  the requested sectioning.

* Does the introduction explain clearly what is the question addressed, the
  data employed and the number of observations and variables involved?

* Do the plots show some meaningful summary of the data? Are axes in plots
  labeled in plain language and large enough to read?

* Does the GitHub repo include a _Makefile_ that automatizes the entire analysis
  pipeline and generation of the final report in the `index.html` file?
