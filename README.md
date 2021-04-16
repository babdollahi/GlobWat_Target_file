# GlobWat_Target_file
A target file has been generated from one of the GlobWat models sample files
(prc01wb.asc) for regridding ERA5 and ERA-Interim datasets. 
The ASCII file can be found at:
http://www.fao.org/geonetwork/srv/en/metadata.show?currTab=simple&id=52366

You can either download the generated target file from this repository or
use the GDAL translator to convert the file from ASCII format to NetCDF format 
by entering the following command into the terminal:

gdal translate -of netCDF ASCII prc01wb.asc globwat_target_grid.nc
