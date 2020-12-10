# OLE VARIABLES

# variables

## 1. adt 
Name: Absolute dynamic topography  <br />
Units: meters  <br />
Description: The absolute dynamic topography is the sea surface height above geoid; the adt is obtained as follows: adt=sla+mdt where mdt is the mean dynamic topography  <br />
Calculation notes: NA  <br />
Time-series:  1993-2020 <br />
NC title: Merged all satellites Global Ocean Gridded SSALTO/DUACS Sea Surface Height L4 product and derived variables  <br />
Source: SSALTO/DUACS via CMEMS  <br />

## 2. adt_sd
Name: Standard deviation of absolute dynamic topography  <br />
Units: meters  <br />
Description: The absolute dynamic topography is the sea surface height above geoid; the adt is obtained as follows: adt=sla+mdt where mdt is the mean dynamic topography  <br />
Calculation notes: Standard deviation calculated using a .75 x .75 roving window <br />
Time-series: 1993-2020 <br />
NC title: Merged all satellites Global Ocean Gridded SSALTO/DUACS Sea Surface Height L4 product and derived variables  <br />
Source: SSALTO/DUACS via CMEMS  <br />

## 3. sla
Name: Sea level anomaly <br />
Units: meters  <br />
Description: The sea level anomaly is the sea surface height above mean sea surface; it is referenced to the [1993, 2012] period  <br />
Calculation notes: NA <br />
Time-series: 1993-2020 <br />
NC title: Merged all satellites Global Ocean Gridded SSALTO/DUACS Sea Surface Height L4 product and derived variables  <br />
Source: SSALTO/DUACS via CMEMS  <br />

## 4. sla_sd
Name: Standard deviation of sea level anomaly <br />
Units: meters  <br />
Description: The sea level anomaly is the sea surface height above mean sea surface; it is referenced to the [1993, 2012] period  <br />
Calculation notes: Standard deviation calculated using a .75 x .75 roving window <br />
Time-series: 1993-2020 <br />
NC title: Merged all satellites Global Ocean Gridded SSALTO/DUACS Sea Surface Height L4 product and derived variables  <br />
Source: SSALTO/DUACS via CMEMS  <br />

## 5. eke
Name: Eddy kinetic energy <br />
Units: log m2s-2  <br />
Description: Logged EKE derived from ugosa and vgosa  <br />
Calculation notes: eke=1/2*(ugosa^2+vgosa^2) ; l.eke=log10(eke + .001)   <br />
Time-series: 1993-2020 <br />
NC title: Merged all satellites Global Ocean Gridded SSALTO/DUACS Sea Surface Height L4 product and derived variables  <br />
Source: SSALTO/DUACS via CMEMS  <br />

## 6. mld
Name: Mixed layer depth <br />
Units: meters  <br />
Description: Density ocean mixed layer thickness; ocean_mixed_layer_thickness_defined_by_sigma_theta  <br />
Calculation notes: NA <br />
Time-series: 1993-2020 <br />
NC title: Daily mean fields from Global Ocean Physics Analysis and Forecast updated Daily <br />
Source: MERCATOR GLORYS12V1 via CMEMS <br />

## 7. l.chl
Name: Chlorophyll-a concentration <br />
Units: log milligram m-3  <br />
Description: NA  <br />
Calculation notes: log10 <br />
Time-series: 1997-2020 <br />
NC title: dataset-oc-glo-bio-multi-l4-chl_interpolated_4km_daily-rep <br />
Source: GlobColour via CMEMS <br />

## 8. sst
Name: Sea surface temperature <br />
Units: Degrees celcius  <br />
Description: <br />
Calculation notes: Converted from kelvin to celcius <br />
Time-series: 1981-2020 <br />
NC title: Global SST & Sea Ice Analysis, L4 OSTIA, 0.05 deg daily (METOFFICE-GLO-SST-L4-REP-OBS-SST-V2) <br />
Source: GHRSST via CMEMS <br />

## 9. sst_sd
Name: Standard deviation of sea surface temperature <br />
Units: Degrees celcius  <br />
Description: Standard deviation calculated using a .75 x .75 roving window <br />
Calculation notes: Converted from kelvin to celcius <br />
Time-series: 1981-2020 <br />
NC title: Global SST & Sea Ice Analysis, L4 OSTIA, 0.05 deg daily (METOFFICE-GLO-SST-L4-REP-OBS-SST-V2) <br />
Source: GHRSST via CMEMS <br />

## 10. wave
Name: Spectral significant wave height (Hm0)  <br />
Units: meters  <br />
Description: NA  <br />
Calculation notes: Daily wave calculated as the mean across 8 3hr rasters  <br />
Time-series: 1993-2020 <br />
NC title: Mean fields from global wave model MFWAM of Meteo-France with ECMWF forcing  <br />
Source: METEO-FRANCE via CMEMS  <br />

## 11. wind
Name: Wind
Units: m s-1 (?)  <br />
Description: NA  <br />
Calculation notes: For each 6 hourly raster: r=sqrt(eastward_wind^2+northward_wind^2) ; then derived rasters are averaged to create a daily field  <br />
Time-series: 1992-2020 <br />
NC title: Global Ocean - Wind Analysis - Blended Sensors - 6 hourly - Reprocessed  <br />
Source: Ifremer/Cersat via CMEMS  <br />

## 12. PPuper200m
Name: Primary productivity <br />
Units: milligrams of Carbon per cubic meter per day  <br />
Description: net_primary_production_of_biomass_expressed_as_carbon_per_unit_volume_in_sea_water  <br />
Calculation notes: Mean primary productivity in the upper 200m (1:31 depth levels) of the water column <br />
Time-series: 1992-2020 <br />
NC title: Daily mean fields for product GLOBAL_REANALYSIS_BIO_001_029  <br />
Source: MERCATOR FREEBIORYS2V4 via CMEMS  <br />

## 13. oxycline
Name: Oxycline  <br />
Units: meters (?) <br />
Description: Depth of the 3.5 ml/l oxycline <br />
Calculation notes: Ask Barb. NA values are still -99  <br />
Time-series: 1992-2020 <br />
NC title: Daily mean fields for product GLOBAL_REANALYSIS_BIO_001_029  <br />
Source: MERCATOR FREEBIORYS2V4 via CMEMS  <br />

## 14. oxy200m
Name: Dissolved Oxygen <br />
Units: mmol m-3  <br />
Description: mole_concentration_of_dissolved_molecular_oxygen_in_sea_watery  <br />
Calculation notes: Oxygen concentration at 200m (depth level 31) <br />
Time-series: 1992-2020 <br />
NC title: Daily mean fields for product GLOBAL_REANALYSIS_BIO_001_029  <br />
Source: MERCATOR FREEBIORYS2V4 via CMEMS  <br />

## 15. bathy
Name: Bathymetry <br />
Units: meters  <br />
Description: Seafloor depth <br />
Calculation notes: NA <br />
Time-series: NA <br />
NC title: NA  <br />
Source: ETOPO1 <br />

## 16. bathy_sd
Name: Standard deviation of bathymetry <br />
Units: meters  <br />
Description: Seafloor complexity (rugosity) <br />
Calculation notes: Standard deviation calculated using a .75 x .75 roving window  <br />
Time-series: NA <br />
NC title: NA  <br />
Source: ETOPO1 <br />

## 17. dist_eez
Name: Distance to nearest EEZ <br />
Units: meters  <br />
Description: NA  <br />
Calculation notes: EEZ shapefile version: World_EEZ_v10_20180221 <br />
Time-series: NA <br />
NC title: NA  <br />
Source: marinergions.org <br />

## 18. dist_nta
Name: Distance to nearest NTA <br />
Units: meters  <br />
Description: NA  <br />
Calculation notes: NTA defined as marine protected areas in which all or a portion is designated NTA <br />
Time-series: NA <br />
NC title: NA  <br />
Source: World Database on Protected Areas <br />

## 19. dist_shore
Name: Distance to shore <br />
Units: meters  <br />
Description: NA  <br />
Calculation notes: shoreline acquired from data(wrld_simpl) (pkg maptools) <br />
Time-series: NA <br />
NC title: NA  <br />
Source: slightly modified version of Bjoern Sandvik's improved version of world\_borders.zip - TM\_WORLD\_BORDERS\_SIMPL-0.2.zip dataset from the Mapping Hacks geodata site <br />
