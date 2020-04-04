COVis: covid-19 Visualizations
================

(Source code: <https://github.com/b-lev/covid19-vis>)

# Main plot

Results below include up to 2020-04-03 for MA
\[<a href="https://github.com/b-lev/massachusetts-covid19-report-archive">src</a>\],
2020-04-03 for countries
\[<a href="https://github.com/CSSEGISandData/COVID-19">src</a>\], and
2020-04-03 for US states
\[<a href="https://covidtracking.com">src</a>\].

Related site:
<a href=https://www.wmasscovid.com>https://www.wmasscovid.com</a>.

Below is the most important plot. We want to be like S. Korea or lower.
This is a comparison of growth per capita, where “day 0” is approx
0.004% of the country’s population. This is a log scale, and so
exponential/viral growth is a straight line. The dashed grey lines show
epidemic growth when the fraction of infected population doubles every 2
days, or 3 days, etc.  
![](covid19-vis_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->

## Massachusetts Data

MA data from
<https://github.com/b-lev/massachusetts-covid19-report-archive>.

![](covid19-vis_files/figure-gfm/MA.fit-1.png)<!-- -->![](covid19-vis_files/figure-gfm/MA.fit-2.png)<!-- -->

Death rate in MA.

![](covid19-vis_files/figure-gfm/ma.death-1.png)<!-- -->

The cumulative fraction of MA covid patients that are hospitalized.

![](covid19-vis_files/figure-gfm/ma-hosp-1.png)<!-- -->

MA is performing an inadequate number of tests per day.

![](covid19-vis_files/figure-gfm/ma-testing-1.png)<!-- -->

![](covid19-vis_files/figure-gfm/age-1.png)<!-- -->

![](covid19-vis_files/figure-gfm/death-demo-1.png)<!-- -->

![](covid19-vis_files/figure-gfm/counties-1.png)<!-- -->![](covid19-vis_files/figure-gfm/counties-2.png)<!-- -->

# US States

Deaths in the US.

![](covid19-vis_files/figure-gfm/us.deaths-1.png)<!-- -->

(Based on <https://covidtracking.com/api/states/daily.csv>.)

![](covid19-vis_files/figure-gfm/states-1.png)<!-- -->

# US Testing Statistics

Testing in each state. Sometimes, health care workers are tested, to be
sure they are not infected. That is one explanation for why some states
show many negatives. (Based on
<https://covidtracking.com/api/states/daily.csv>.)

![](covid19-vis_files/figure-gfm/testing-1.png)<!-- -->

This plots show how long it is taking each state to test its population,
on a per capita basis. (I’m assuming, optimistically, that the test had
not be given to the same person twice.)

![](covid19-vis_files/figure-gfm/testing2-1.png)<!-- -->

# World data

This plot shows the spread of the virus over time across the world. We
want the number of active cases to drop to zero, the deaths to stay as
low as possible, obviously, and the recovered cases to climb high.
Confirmed is a cumulative count of everyone that has tested positive.

![](covid19-vis_files/figure-gfm/world-1.png)<!-- -->

Here’s another view of the same data.

![](covid19-vis_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

These plots show how the numbers have grown over time in each country.
All countries want to hit the bent curve that China has reported
achieving.

![](covid19-vis_files/figure-gfm/world2-1.png)<!-- -->

# World Fatality Rates

Here is a plot of the fatility rate. It’s really hard to tell whether
this analysis makes sense given the unreliablity of the data overall.
FWIW:

![](covid19-vis_files/figure-gfm/fatality-1.png)<!-- -->

Thanks to JHU for the data
(<https://github.com/CSSEGISandData/COVID-19>). Results are only as good
as the data, which is only as good as the amount of testing done.

I hereby disclaim any and all representations and warranties with
respect to this data, including accuracy, fitness for use, and
merchantability. Reliance for medical guidance or use in commerce is
strictly prohibited.
