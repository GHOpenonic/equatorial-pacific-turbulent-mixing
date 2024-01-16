This folder contains 2023 processed CTD data, see https://github.com/GHOpenonic/equatorial-pacific-turbulent-mixing for the processing code. Contact me at openonic@uw.edu if you have any questions.

D, P, S, T files correspond to density, pressure, salinity, and temperature files. They are organized by cast ID and depth.

Linearly interpolated values can be found within the subfolder 'interpolated dataframes.' These files, D_int etc. are organized by distance from 5 North along 180 in kilometers and depth. lat_df stores a NxN grid of latitudes with the same shape as D_int etc. 