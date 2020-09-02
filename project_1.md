# Project One

### Deliverable
The image below has a heatmap of Loas showing the population and population density within each province labeled.
Red represents a high population and yellow the lower, which can also be seen visually with the numerical values of popoulation density.
Next to the map is a barplot showing the percentage of total population in Laos each province makes up.
Again, red represents a higher percent of the total population.

These plots were made by using the ggplot() package in R.
Using the aggregated raster from the previous assignmnent, area was created manually, using the units() package, to then calculate population density for each province.
The values of population density were then added as additional labels to the heatmap for ADM1.
For the barplot, the provinces were rearranged from highest to lowest population and labeled by finding the percent of total population.

![](lao.png)

### Stretch 1 (in progress)
This is a barplot with a visual representation of district populations within the provinces of Laos.
However, I still need to figure out how to change the colours of the boxes so that they are significant to population and don't clash with the cooresponding ADM2 map before I join them.

![](adm2_bplt.png)