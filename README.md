# GDP-and-Urban-Population-Analysis

This project used libraries such Pandas, NumPy, Seaborn and Matplotlib to explore the relationship between GDP per capita and the percentage of a country's population living in urban areas.

The World Bank API was used to retrieve data for the two above metrics as well as to extract more information regarding the countries such region and income level.

The project involved data cleaning and preparation. For example, the data extracted using the API on countries' regional location was incomplete and required values to be filled in using a dictionary.

Dataframes were also merged to create one comprehensive source of data using the correct data types.

It was possible to visualise the spread of countries across different regions with respect to GDP and urban population. 

The 7 global regions considered are:

- LAC = Latin America and Caribbean
- MNA = Middle East, North africa, Afghanistan, Pakistan
- SSA = Sub-Saharan Africa
- ECA = Europe and Central Asia
- EAP = East Asia and Pacific
- SAS = South Asia


Additionally, the relationship between countries' income level and position with respect to GDP and urban population was also plotted.

The Pearson correlation coefficient was calculated using NumPy, indicating a moderately postive relation between the two metrics.

- Trend: On average, an increase in GDP per capita result in an increase in the percentage of the urban population.

The data was also modelled using a line of best using Numpy to determine a linear equation describing the data.
