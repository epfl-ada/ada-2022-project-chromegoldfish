# Datasets

The current external datasets are sourced from Google Trends. Google Trends has yearly, geo-location, and key-based trends that are publicly available for use. In this repository you will find our external datasets that will be used in our analysis.

- ``` ./datasets/figures``` -this folder contains all the figures generated from our notebooks. Note that some figures were not used in our data story but are there.
- ```./datasets/new organizations ``` - this folder contains news organizations datasets which contains the names of different media platforms from different users.
- ```./timeseries ``` - This folder contains the ```.zip``` files of the specific topics we looked at in the time series analysis generated from ```src/timeseries_graphs.ipnyb```notebook.
- ```./wiki_events.csv``` - Contains a cleaner version of the wiki_events data files that we used in our ```src/data-explore.ipynb``` notebook. Also generated in the ```src/extract_wiki_events.ipynb``` notebook. 
- ```./wiki_events.xml``` -Contains the raw version of the wiki_events data files. This file is required to generated a preprocessed ```.csv``` version in the ```src/extract_wiki_events.ipynb``` notebook. 
