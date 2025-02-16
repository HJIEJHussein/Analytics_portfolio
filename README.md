# Magi Ndogo water crisis analysis

## Table of contents

- [Project Overview](#project-overview)
- [Data source](#data-source)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)

### Project Overview

This project aims to analyse data gathered about the average time it takes the population of Magi Ndogo to obtain water from the different 
water sources as well as the data about the microbiological nd chemical status about those water sources
The Goal of this project is to privide an action plan we will carry on in order to provide clean water to the population and with a reduced 
average time for Queuing 

### Data source 

The primary dataset used for this analysis is the script 1 of the "md_water_services.mwb" file, containing the database of the project [https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Md_water_services.mwb]

### Tools

- SQL Server : Data analysis
- Power BI : Creating Reports

### Exploratory Data Analysis

- What is the type of most of the water sources : Urban or rural ?
- What is the type of the water source that is the most used by the population of Magi Ndogo ?
- What percentage of the population has water piped directly into their households? and How many of them face non_fonctionnal systems due to issues with pipes, pumps and reservoirs ?
- How many people use wells and how many of them are polluted ?
- What is the average time for water ? On what days is the average time the shortest or the longest ? and on which hours ?

### Data Analysis

- Used MySQL Worbench software to code and respond to those questions,check the "md_water_services.mwb" file [https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Md_water_services.mwb]


### Findings

-  Most water sources are rural in Maji Ndogo.
-  43% of our people are using shared taps. 2000 people often share one tap.
-  31% of our population has water infrastructure in their homes, but within that group,
-  45% face non-functional systems due to issues with pipes, pumps, and reservoirs. Towns like Amina, the rural parts of Amanzi, and a couple
   of towns across Akatsi and Hawassa have broken infrastructure.
-  18% of our people are using wells of which, but within that, only 28% are clean. These are mostly in Hawassa, Kilimani and Akatsi.
-  Our citizens often face long wait times for water, averaging more than 120 minutes:
-  Queues are very long on Saturdays.
-  Queues are longer in the mornings and evenings.
-  Wednesdays and Sundays have the shortest queues.

### Recommendations 

- If communities are using rivers, we will dispatch trucks to those regions to provide water temporarily in the short term, while we send out
crews to drill for wells, providing a more permanent solution. Sokoto is the first province we will target.
- If communities are using wells, we will install filters to purify the water. For chemically polluted wells, we can install reverse osmosis (RO)
filters, and for wells with biological contamination, we can install UV filters that kill microorganisms - but we should install RO filters too. In
the long term, we must figure out why these sources are polluted.
-  For shared taps, in the short term, we can send additional water tankers to the busiest taps, on the busiest days. We can use the queue time
pivot table we made to send tankers at the busiest times. Meanwhile, we can start the work on installing extra taps where they are needed.
According to UN standards, the maximum acceptable wait time for water is 30 minutes. With this in mind, our aim is to install taps to get
queue times below 30 min. Towns like Bello, Abidjan and Zuri have a lot of people using shared taps, so we will send out teams to those
towns first.
-  Shared taps with short queue times (< 30 min) represent a logistical challenge to further reduce waiting times. The most effective solution,
installing taps in homes, is resource-intensive and better suited as a long-term goal.
-  Addressing broken infrastructure offers a significant impact even with just a single intervention. It is expensive to fix, but so many people can
benefit from repairing one facility. For example, fixing a reservoir or pipe that multiple taps are connected to. We identified towns like Amina,
Lusaka, Zuri, Djenne and rural parts of Amanzi seem to be good places to start.

