# UCAR unidata

Includes both NetCDF and UDUNITS.

 - netcdf 4.7.3
 - hdf5 1.10.5
 - udunits 2.2.27

Built using https://github.com/r-windows/rtools-packages

## DAP support in NetCDF

Only the Win64 built has DAP support enabled in NetCDF.
The 32bit version would crash when built with DAP so we ship the version without DAP.
