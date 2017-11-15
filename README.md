# project_data
Historical Weather Data from NOAA for US West Coast

Data obtained from: NOAA National Centers for Environmental Information (https://www.ncdc.noaa.gov/cdo-web/search)
Format/Element (Value) Definitions:  "STATION","NAME","LATITUDE","LONGITUDE","ELEVATION","DATE","TAVG","TMAX","TMIN","TOBS"

"STATION"
  STATION (17 characters) is the station identification code. Please see
  ftp://ftp.ncdc.noaa.gov/pub/data/normals/1981-2010/station-inventories/
  for a complete list of stations and their metadata.

"NAME"
  STATION_NAME (max 50 characters) is the name of the station (usually city/airport name)

"LATITUDE"
  latitude (decimated degrees w/northern hemisphere values > 0, southern hemisphere values < 0)

"LONGITUDE"
  longitude (decimated degrees w/western hemisphere values < 0, eastern hemisphere values > 0)

"ELEVATION"
  elevation above mean sea level (thousandths of meters)

"DATE"
  DATE is the year of the record (4 digits) followed by month (2 digits) and day (2 digits)

"TAVG"
  Average Temperature

"TMAX"
  Maximum temperature

"TMIN"
  Minimum temperature

"TOBS"
  Temperature at the time of observation
