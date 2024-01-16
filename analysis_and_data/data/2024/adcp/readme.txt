This folder contains 2024 processed ADCP data, see https://github.com/GHOpenonic/equatorial-pacific-turbulent-mixing for the processing code. Contact me at openonic@uw.edu if you have any questions.

adcp_data_2024 contains pre-processed data. 2024_os75nb_cleaned.nc contains the fully post-processed and cleaned ADCP data. 

Access it in python with this code:

# Load ADCP Data
datadir = 'xxx' # insert path to where you saved it
filepathadcp = datadir+'/2024_os75nb_cleaned.nc' # full filepath
ADCP_all = xr.open_dataset(filepathadcp, decode_times=False) # open dataset

For more code like how to plot etc. see the link above to my GitHub.

os75nb.nc contains the post-processed, uncleaned ADCP data.

the 2024_os75nb_postproc.txt contains documentation on post-processing 
