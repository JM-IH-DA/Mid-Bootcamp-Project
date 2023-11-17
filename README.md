# Mid-Bootcamp-Project

### Decoding Housing Prices Patterns in Germany

"Predictive Insights and Geospatial Analysis for Incomplete Data"

### Overview

This project focuses on analyzing housing prices in various cities across Germany. It aims to predict and understand housing price patterns using data analysis and geospatial techniques.

### Project Background

Motivation for this project stems from personal interest in real estate and the need to comprehend factors influencing housing prices while searching for a property.

### Objectives

1. Predict average housing prices using diverse features such as population, density, location, and more.
2. Explore correlations between population density and average prices.
3. Investigate whether housing prices are more affected by male or female population groups.
4. Assess the impact of the price index on housing costs.
5. Analyze spatial relationships between city locations and housing prices.

### Methodologies

#### Data Collection

Utilized datasets comprising federal state, district, population, gender distribution, and housing cost data.

Links:

df1// ((https://www.destatis.de/DE/Themen/Laender-Regionen/Regionales/Gemeindeverzeichnis/Administrativ/05-staedte.html)

df2//
As there is no database with this specific data, I have created it with the information found in this official link:
(https://www.destatis.de/DE/Themen/Gesellschaft-Umwelt/Bevoelkerung/Bevoelkerungsstand/Methoden/Erlauterungen/verstaedterung.html)

df3//
I have created a database with the official information found in the pdf below: 
(https://www.bmwsb.bund.de/SharedDocs/downloads/Webs/BMWSB/DE/veroeffentlichungen/wohnen/wohngeld-2023/mietstufen-2023.pdf?__blob=publicationFile&v=6)

df4//
Since I only found data for small groups of important cities or as a general index, I took approx. 50 % of the values from the leading real estate platform in germany called Immowelt in order to balance more the data and will try to predict the others. 
(https://www.immowelt.de/immobilienpreise/deutschland/hauspreise)

df5//
(https://www-genesis.destatis.de/genesis/online?operation=abruftabelleBearbeiten&levelindex=1&levelid=1700134508325&auswahloperation=abruftabelleAuspraegungAuswaehlen&auswahlverzeichnis=ordnungsstruktur&auswahlziel=werteabruf&code=61111-0010&auswahltext=&werteabruf=Werteabruf#abreadcrumb)

df6//
(https://www.destatis.de/DE/Themen/Laender-Regionen/Regionales/Gemeindeverzeichnis/Administrativ/Archiv/GVAuszugQ/AuszugGV3QAktuell.html)

### Data Preprocessing

Handled missing values, cleaned datasets, and engineered features.

### Data Analysis

- Utilized regression models to predict housing prices.
- Conducted correlation analysis and spatial autocorrelation tests.

### Data Visualization

Plotted maps, scatter plots, histograms, and heatmaps to visualize spatial and distributional trends.

## Technologies Used

- Python (Pandas, NumPy, Scikit-learn)
- Geospatial libraries (GeoPandas, Folium)
- Statistical analysis tools (SciPy, PySAL)
- Visualization libraries (Matplotlib, Seaborn)

## Results

- Moderately accurate housing price predictions.
- Identified correlations between population density and housing prices.
- Found significant differences in prices between male and female dominant cities.
- Discovered a negative correlation between housing costs and price index.
- Detected spatial correlations indicating clustering of housing prices.

## Conclusion

The project sheds light on various aspects influencing housing prices, offering insights into spatial relationships and key factors impacting property costs across cities in Germany.

## Tableau presentation link:

[
](https://public.tableau.com/app/profile/jm.ih.da/viz/Book1_17001905343850/Dashboard7)https://public.tableau.com/app/profile/jm.ih.da/viz/Book1_17001905343850/Dashboard7
