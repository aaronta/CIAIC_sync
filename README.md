# CIAIC_sync

## Syncing XNAT

XNAT is only synced in one direction

- xnat_Carle2Illinois.txt - studies collecting data at Carle
- xnat_Illinois2Carle.txt - studies collecting data at Illinois/BIC

## Syncing data folders

The initial data folder on bic-data will be created using the ITS webtool and manually synced with Carle.  All future syncs will be dependent on data collection and processing.

### Root file locations:

**Carle:** //chresearchcifs/researhdata

**Illinois:** ITS Isilon

File structure follows the naming of the file, left institution sends to(2) right institution and separated by a comma

- data_Carle2Illinois.txt - studies collecting data and/or performing analysis at Carle
- data_Illinois2Carle.txt - studies collecting data and/or performing analysis at Illinois
