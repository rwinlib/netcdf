# UCAR unidata

Includes both NetCDF and UDUNITS.

 - netcdf 4.4.1.1
 - hdf5 1.8.16
 - udunits 2.2.25

All built using stock msys2 tools. 

## DAP support in NetCDF

Only the Win64 built has DAP support enabled in NetCDF.
The 32bit version would crash when built with DAP so we ship the version without DAP.
