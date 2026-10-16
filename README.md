# Introduction
Welcome, non-profit organization! This file is one that is made to help provide advice that is backed by data on what countries could use your community-protection and climate-support efforts. 

# Analysis
**What does each column actually hold, and what data type is it?**

The dataset holds 6 distinct columns. Columns 1-2 are **country** and **iso_code**. The **country** column provides the name of the country, and the **iso_code** provides the respective iso code. Both are strings because the data values are in text form. Columns 3-5 are **year** (provides year data was collected), **population** (amount of people in the country), and **gdp** (the gdp of the country). All 3 of these are integers because the data values are written as whole numbers. Column 6 is for **co2** (the amount of co2 in the country), which is a float because the data values for it have numbers with decimals.

**Is this dataset structured or unstructured?**

This dataset is structured because there are columns and rows in order with data types that are consistent for each column - there are not multiple data types in each column.

**Is there anything about the data — missing values, suspicious rows — that should make someone cautious before using it to decide which communities need support?**

There are several missing values that can play a huge role in deciding what countries require priority in the non-profit efforts. For example, **population** is missing a data value for **Africa (GCP)**. Without a data value for **population**, there is a level of uncertainty as to how many people would benefit from contributions, as opposed to a country with potentially far more people and a higher sense of urgency for support.

**What's one specific question you'd ask the data's source before trusting it enough to act on?**

Are all of the data values that are missing left blank, or is there an inconsistency of how missing data values are represented? The implications of missing data values that we are not aware of can be consequential, as there could be more key data, such as **population**, that is not being properly accounted for.

**What's something about energy and emissions you're personally curious to explore in this data?**

Is there a relationship between a country's **gdp** and the **co2** value it has? If there is a pattern of countries that have a higher **gdp** also have a lower **co2** number, is this sufficient enough for us to base a simple foundation as to where we should prioritize providing support?

# Sources & License
**Github Repository**

Pablo Rosado, Data on CO2 and Greenhouse Gas Emissions by *Our World in Data*, GitHub (2026)

**Co2 Source**

Hannah Ritchie, Pablo Rosado, and Max Roser (2023) - “CO₂ and Greenhouse Gas Emissions” Published online at OurWorldinData.org. Retrieved from: 'https://ourworldindata.org/co2-and-greenhouse-gas-emissions' [Online Resource]

**Population Source**

Edouard Mathieu and Lucas Rodés-Guirao (2022) - “What are the sources for Our World in Data's population estimates?” Published online at OurWorldinData.org. Retrieved from: 'https://archive.ourworldindata.org/20260910-004756/population-sources.html' [Online Resource] (archived on September 10, 2026).

**License**

https://creativecommons.org/licenses/by/4.0/
