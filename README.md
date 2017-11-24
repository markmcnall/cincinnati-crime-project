# cincinnati-crime-project
Analyzing crime of Cincinnati between 2010-2017. A project I picked up to practice and improve my skills with python, pandas, etc.

## Scope and Implementation

The original goal was to map every reported crime in the dataset onto a map and create a composite heatmap / animated heatmap that shows changes in crime, as well as other misc. charts and graphs to explore changes and trends with crime in Cincinnati.

The bulk of the data munging was done in an IPython/Jupyter notebook, with some on-the-fly quick analysis done in Python's interpreter. The map I will try to create with Google's fusiontables to streamline making the heatmap, and additional analysis will be done with matplotlib.

If you would like the run this code yourself, you should only need Python 3 (I'm running 3.6.2), a few packages (pandas, datetime, numpy, matplotlib) as well as Jupyter notebook. 

## Data

The data was taken from the City of Cincinnati's Open Data Portal, downloaded as a .csv file with ~247,000 lines. Since my initial download on 9 November 2017, the dataset has been replaced online by a new format, the Police Data Initiative (PDI) Crime Incidents located [here] (https://data.cincinnati-oh.gov/Safer-Streets/PDI-Police-Data-Initiative-Crime-Incidents/k59e-2pvf). I will continue to use the original downloaded file as to not have to rewrite parts of code, and is included in the repo's /data folder.

At a future time, I would like to update the code to work with the new format to update maps. The dataset has an entirely different format, so this isn't the top priority.

## Suggestions

Anyone who sees any errors, as well as ways to improve my code in any way feel free to let me know! It's my first real project with pandas so I'm sure there's lots to be improved on.
