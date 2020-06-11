# SW577


Drawing Correlations Between Unemployment, Per Capita Personal Income, Hospital Availability, and Suicide Rates in the United States

J. Robert Quillen
6/4/2020

Introduction

Overview

In an effort to complete this study, data was collected from a variety of sources, including The Centers for Disease Control (suicide rates), The United States Census Bureau (population), SSTI (PCPI), NCSI (Unemployment), and the American Hospital Directory (Hospital Count). All figures collected, aside from those reflected in historical suicide rates, are representitive of historical figures reported in 2010. Suicide rates were collected from 2005 - 2017; for the purpose of statistical analysis, suicide rates for the year 2010 will be utilized in order to remain consistant with other data present in this study.
This exploration aims to explore the connection between suicidality, per capita personal income, unemployment, and hospital availablity in an effort to gain insight into ways to lower the overal suicide rate.


United States Suicide Rate

The overall rate of suicide in the United States has been on the rise since 2007, as illustrated below.

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/SR-1.png)

In 2010, State to State suicide rates range from a rate of 8.30 per 100,000 population (New Jersey and New York) to a rate of 25.20 per 100,000 population (Wyoming).

##    vars  n  mean   sd median trimmed  mad min  max range skew kurtosis   se
## X1    1 50 16.45 4.51   15.7   16.32 5.19 8.3 25.2  16.9 0.17    -0.77 0.64

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-6-1.png)

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-5-1.png)

For a look at how each State fairs with regard to their current overall rate of suicide, please reference the bar chart below. (data reflective of 2010 figures)

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-7-1.png)

In 2010, the average unemployment rate in the United States was 8.542 with a low of 3.80 (North Dakota) and high of 14.90 (Nevada). In an effort to explore if unemployment rates potentially influenced rates of suicide, a bivariate correlation was determined using the Pearson method. Ultimately statistical analysis revealed a weak negative correlation of -0.1309806 between rates of suicide in the United States and unemployment.

##    vars  n mean   sd median trimmed mad min  max range skew kurtosis  se
## X1    1 50 8.54 2.12   8.55    8.52 1.7 3.8 14.9  11.1 0.21     0.49 0.3





Mapping Suicide, Unemployment, PCPI, Hopsital Count, and Total Population

![](https://raw.githubusercontent.com/rquillen730/SW577/master/Tableau%20Map.jpg)


