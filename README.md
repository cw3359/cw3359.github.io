**Title:** NYC Crime Overview

**Group:** K

**Members:** Chen Wang
([cw3359\@columbia.edu](mailto:cw3359@columbia.edu){.email}), Meilin
Yuan ([my2722\@columbia.edu](mailto:my2722@columbia.edu){.email}),
Zhuohan Wang
([zw2818\@columbia.edu](mailto:zw2818@columbia.edu){.email}), Sifan
(Carol) Liu ([sl4974\@columbia.edu](mailto:sl4974@columbia.edu){.email})

**Abstract**

The crime situation deserves public attention because it can directly
affect people's safety. In this project, we will explore as deeply as we
can the changes in the crime situation in the five boroughs of New York
City (New York, Bronx, Queens, Brooklyn, and Staten Island). It's an
efficient way to reflect the changes in the level of Safety in New York,
even the security situation in the social security aspect as time goes
on. We plan to collect the data on each borough's criminal cases and the
odds of different types of crimes occurring in each county to get a more
accurate result for this research. After the process of visualization,
we will conclude the following questions:

-   The most dangerous and safest borough in New York City from multiple
    perspectives.

    -   The total number of crime cases.

    -   The overall trend of the crime situation.

    -   Adjusted the level of danger by population and area.

    -   Total number of certain types of crime.

        -   Rape.

        -   Robbery.

        -   Murder.

-   Does the outbreak of COVID-19 make the crime situation in New York
    City improve?

    -   Does females' risk of being victimized higher than males in the
        specific type of crime?

    -   Which area has the highest and lowest density of crime situation
        in New York City?

        -   Harassment.

-   As time goes by, which type of crime has been most effectively
    improved and which has improved the least?

    -   The most dangerous and safest time in New York City.

    -   The growth rate of the crime situation in New York City.

        -   Before and after COVID-19.

**Technology**

-   ggplot2, ggmap, plotly, leaflet

**Data Description: There are four datasets we used in this project.**

-   **Dataset 1:**
    <https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i>

    -   This dataset is from NYC Open Data with more than 7 million
        rows.

    -   This dataset shows the detailed information of the crime
        situation in New York up to 2021. It contains multiple variables
        including County, Agency, Year, crime type of each case, as well
        as the coordinate of each case of crime.

-   **Dataset 2:**
    <https://www.kaggle.com/new-york-state/new-york-state-index-crimes>

    -   The dataset is from kaggle.com and the file that we are going to
        use is "index crimes by county and agency beginning 1990.csv".

    -   This dataset shows the detailed information of the crime
        situation in New York from 1990 to 2018. It contains multiple
        variables including County, Agency, Year, as well as the count
        of each type of crime.

-   **Dataset 3:**
    <https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-Year-To-Date-/5uac-w243>

    -   This dataset is from NYC Open Data.

    -   This dataset shows the detailed information of the crime
        situation in New York up to 2021. It contains multiple variables
        including County, Agency, Year, as well as the coordinate of
        each case of crime.

-   **Dataset 4:**
    <https://data.cityofnewyork.us/City-Government/Projected-Population-2010-2040-Summary/ph5g-sr3v>

    -   This Dataset is from NYC Open Data.

    -   This Dataset contains the information of changes of population
        in New York City.

**Visualization**

-   **Website**

    -   We would use either rmdformat output as a single interactive
        platform to publish graphs onto a newly built, partially
        interactive website.

-   **Maps**

    -   We would use leaflet to illustrate the differences (in various
        aspects such as precent of specific type to crime) across the
        five boroughs of NYC. We would use either the depth of color or
        a heat map to indicate different levels of those aspects.
