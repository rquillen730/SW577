#  DRAWING CORRELATIONS BETWEEN UNEMPLOYMENT, PER CAPITA PERSONAL INCOME, HOSPITAL AVAILABLITY, AND SUICIDE RATES IN THE UNITED STATES.

J. Robert Quillen
6/4/2020

# INTRODUCTION

Over the course of this semester I worked with data from various agencies in order to explore any possible correlations between suicide in the United States and Unemployment, per capita personal income, and hospital availability.  After obtaining this data I worked with a variety of data visualization software in order to present my findings in a variety of ways.  

This portfolio was generated utilizing R Markdown and Tableau software.

# OVERVIEW

In an effort to complete this study, data was collected from a variety of sources, including The Centers for Disease Control (suicide rates), The United States Census Bureau (population), SSTI (PCPI), NCSI (Unemployment), and the American Hospital Directory (Hospital Count). All figures collected, aside from those reflected in historical suicide rates, are representative of historical figures reported in 2010. Suicide rates were collected from 2005 - 2017; for the purpose of statistical analysis, suicide rates for the year 2010 will be utilized in order to remain consistent with other data present in this study.
This exploration aims to explore the connection between suicidality, per capita personal income, unemployment, and hospital availability in an effort to gain insight into ways to lower the overall suicide rate.


# UNITED STATES SUICIDE RATE 

The overall rate of suicide in the United States has been on the rise since 2007, as illustrated below.

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/SR-1.png)

In 2010, State to State suicide rates range from a rate of 8.30 per 100,000 population (New Jersey and New York) to a rate of 25.20 per 100,000 population (Wyoming).

Mean Suicide Rate - 16.45                                                                                                               
Standard Deviation - 4.51                                                                                                               
Median Suicide Rate - 15.7                                                                                                               
Maximum Suicide Rate - 25.2                                                                                                             
Minimum Suicide Rate - 8.3                                                                                                               
Range - 16.9                                                                                                                             

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-6-1.png)

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-5-1.png)

For a look at how each State fairs with regard to their current overall rate of suicide, please reference the bar chart below. (data reflective of 2010 figures)

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-7-1.png)

# UNEMPLOYMENT AND SUICIDE IN THE UNITED STATES - 2010

In 2010, the average unemployment rate in the United States was 8.542 with a low of 3.80 (North Dakota) and high of 14.90 (Nevada). In an effort to explore if unemployment rates potentially influenced rates of suicide, a bivariate correlation was determined using the Pearson method. Ultimately statistical analysis revealed a weak negative correlation of -0.1309806 between rates of suicide in the United States and unemployment.

Mean Unemployment - 8.54                                                                                                
Standard Deviation - 2.12                                                                                                  
Median Unemployment - 8.55                                                                                                
Minimum Unemployment - 3.8                                                                                                
Maximum Unemployment - 14.9                                                                                                 
Range - 11.1                                                                                                   

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-10-1.png)

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-9-1.png)

The correlation between unemployment and rate of suicide is weak and negative: -0.1309806.

# PCPI AND SUICIDE IN THE UNITED STATES - 2010

The average per capita personal income in the United States in 2010 was 39,440 with a low of 30,783 (Mississippi) and high of 57,347 (Connecticut). In an effort to explore if PCPI potentially influenced rates of suicide, a bivariate correlation was determined using the Pearson method. Ultimately statistical analysis revealed a moderate negative correlation of -0.465929 between rates of suicide in the United States and PCPI.

Mean PCPI - 39439.74                                                                                                               
Standard Deviation - 5912.88                                                                                                       
Median PCPI - 38702.5                                                                                                             
Minimum PCPI - 30783                                                                                                               
Maximum PCPI - 57347                                                                                                               
Range - 26564                                                                                                                     

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-14-1.png)

1[](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-13-1.png)

# HOSPITAL COUNT AND SUICIDE IN THE UNITED STATES - 2010

The number of hospitals per state range from 7 (Vermont) to 365 (Texas) with a mean of 76 hospitals per state. In an effort to explore if hospitals per state potentially influenced rates of suicide, a bivariate correlation was determined using the Pearson method. Ultimately statistical analysis revealed a moderate negative correlation of -0.3903531 between rates of suicide in the United States and hospital count.

Mean Hospital Count - 76.86                                                                                                            
Standard Deviation - 74.93                                                                                                      
Median Hospital Count - 59                                                                                                             
Minimum Hospital Count - 7                                                                                                           
Maximum Hospital Count - 365                                                                                                           
Range - 358    

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-18-1.png)

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-17-1.png)

# CORRELATIONS BETWEEN UNEMPLOYMENT, PER CAPITA PERSONAL INCOME, HOSPITAL AVAILABLITY, AND SUICIDE RATES IN THE UNITED STATES.

After completing all statistical analysis, I was able to utilize of the RStudio software to compile a comprehensive table displaying the different correlations between all variables analyzed.  The tables below display more information than was covered in the above-mentioned material, much of which will be utilized for continued analysis and study.

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-22-1.png)

![](https://github.com/rquillen730/SW577/blob/master/Drawing-Correlations-Between-Unemployment%2C-Per-Capita-Personal-Income%2C-Hospital-Availability%2C-and-Suicide-Rates-in-the-United-States_files/figure-gfm/unnamed-chunk-23-1.png)

# MAPPING THE DATA

After compiling  all of the data and running the statistical analysis I was then able to utilize another software program, Tableau, to map all of my finds in a density map illustrated below.  Tableau offers the ability to make interactive maps, and in the interactive version of the map presented below, you are able to click on each State and instantly receive information regarding suicide rate, PCPI, hospital count, unemployment rate, and overall population (captured in the second image below).  Additionally, again operating within the interactive format of the mapping software, you are able to compare different states to one another, group states into regions for comparison, and generate your own geographic constraints in order to draw comparisons in a whole new way.

![](https://github.com/rquillen730/SW577/blob/master/Tableau%20Map%201.jpg)

![](https://github.com/rquillen730/SW577/blob/master/Tableau%20Map%202.jpg)


