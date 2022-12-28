# Mapping Dynamic Human Sentiments of Heat Exposure with Location-Based Social Media Data

This github repo is attached to the manuscript Mapping Dynamic Human Sentiments of Heat Exposure with Location-Based Social Media Data. This study aims to explore the possibility to used location-based social media data to map people’s exposure to heat by analyzing nearreal-time social media Twitter.


1. Clone this repo to your local desktop

2. Install required Python library

2. Data Retrieval

  a. If you want to retrieve the full dataset:

    i. Contact corresponding author

  b. You can also use the sample data: https://doi.org/10.6084/m9.figshare.21780065
    
    i. Download the dataset and unzip it
    
    ii. Rename the data_sample to data
    
    iii. Change corresponding code in the notebook for path and don't run data collection part of the code

4. Use the notebook provided for near real-time analysis of your own/reproduce the result in the manuscript

Notebook description:

1. Chicago_HE_Twitter.ipny -> Used to generate city level heat exposure with real-time twitter data

2. National_HE_Twitter.ipny -> Used to generate national-level heat exposure with real-time twitter data

3. data_collection.ipny -> Use API to retrieve United State Census Bureau ACS data for socioeconomic data

4. analysis.ipny -> post-analysis of national scale heat exposure map

Folder description:

1. Census_track -> Chicago Census Track level shapefile

2. data_explore -> Notebook for prelimery exploration of twiiter data

3. geo/data20000.txt -> heat dictionary

4. geo -> chicago border shapefile

5. output_2021091312 -> the output in the case study in the manuscript, reproduce this with exact same date & time

6. US -> US county shapefile
