# Network_Sci_Final
Repository for final project in Network Science


Data is from PushShift dump files available through Accademic Torrents:
     https://academictorrents.com/details/ba051999301b109eab37d16f027b3f49ade2de13


The entire workflow for this project proceeded as follows:

init_env_read_Zstd: 

This file initializes the program, imports all neccessary libraries, and creates function to read the Zstd files.  
**Note some imported libraries are needed for subsequent files and are not included in those files

# get_csvs:
Calls function to read zst and saves desired info as CSV

csv_remove_tages:

This file removes the tags from the CSV files so that will match between columns


filter_subs:
optional function that allows user to filter nodes belonging to a particular subreddit. 


SIRS SPREAD
Simulates SIR spread
