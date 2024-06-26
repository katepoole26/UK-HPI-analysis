# UK-HPI-analysis

## Project Overview
This repository features analysis and D3 data visualization implementation of a UK monthly house price index (HPI) dataset.

## Datasets
* [UK HPI Data](https://www.gov.uk/government/statistical-data-sets/uk-house-price-index-data-downloads-december-2022)
* [UK Population Data](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/estimatesofthepopulationforenglandandwales)

## Tools
* Python
* Javascript
* D3
* CSS
* HTML

## Conclusions
#### Exploratory research question: Analyze the affect that population size has on housing prices in the UK. Are there any detectable trends?
Traditionally, home prices tend to become more expensive as population increases. Of course there are exceptions to this statement, however anecdotally I have witnessed this phenomenon in action in my home time as it has grown in both population size and price over my lifetime. This exploratory research question attempts to characterize this notion with data to understand the magnitude at which housing prices grow in relation to population.

#### Implementation: 
The resulting D3 data visualization resulting from analysis includes 2 components: (1) a bar chart featuring years 1995 through 2022 on the x-axis and the UK population size in millions on the y-axis, and (2) a line graph detailing the average UK home price by year. The visualization blends two chart types – a bar chart and a line graph – distributed over the same x-axis of year with individual y-axis. Because the data share the same x-axis, the two charts are vertically aligned. This choice improves aesthetics and reduce chart clutter, but more importantly it indicates to a viewer that the two charts are designed to be analyzed in tandem. The viewer is meant to appreciate the significant difference in annual increase between the datasets, which is emphasized by this intentional alignment. Additionally, the charts are the exact same dimensions to ensure their co-analysis. The charts are differentiated by distinct colors – orange for the population bar chart and blue for the pound (£) value line graph. The color selection underscores the y-variable independence between the two datasets despite their shared x-axis.

Both charts have direct text labeling each annual value and pop-ups labeling annual percentage changes. These labels were included in the charts because of the decision to exclude the y-axes ticks, but also because some of the annual changes are quite small. The text labels offer a greater precision to discern differences year over year that might have otherwise been overlooked and provides a measure to visualize the disproportionate magnitude change between the population and HPI datasets.
