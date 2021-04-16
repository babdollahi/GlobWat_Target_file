# GlobWat_Target_file
A target file has been generated from one of the GlobWat models sample files
(prc01wb.asc). The file can be found at:
http://www.fao.org/geonetwork/srv/en/metadata.show?currTab=simple&id=52366

To convert this file from ASCII format to NetCDF format, use the GDAL translator 
by entering the following command into the terminal:

gdal translate -of netCDF ASCII prc01wb.asc globwat_target_grid.nc
