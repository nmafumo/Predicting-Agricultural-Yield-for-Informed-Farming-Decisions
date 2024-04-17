Data dictionary
1. Geographic features
Field_ID: A unique identifier for each field (BigInt).
Elevation: The elevation of the field above sea level in metres (Float).
Latitude: Geographical latitude of the field in degrees (Float). (DUMMY VARIABLE- the simulation might have created a relationship)
Longitude: Geographical longitude of the field in degrees (Float). (DUMMY VARIABLE- the simulation might have created a relationship)
Location: Province the field is in (Text).
Slope: The slope of the land in the field (Float).
s
2. Weather features
Rainfall: Amount of rainfall in the area in mm (Float).
Min_temperature_C: Average minimum temperature recorded in Celsius (Float).(DUMMY VARIABLE)
Max_temperature_C: Average maximum temperature recorded in Celsius (Float).(DUMMY VARIABLE)
Ave_temps: Average temperature in Celcius (Float).

3. Soil and crop features
Soil_fertility: A measure of soil fertility where 0 is infertile soil, and 1 is very fertile soil (Float).
Soil_type: Type of soil present in the field (Text).
pH: pH level of the soil, which is a measure of how acidic/basic the soil is (Float).

4. Farm management features
Field_ID: Corresponding field identifier (BigInt).
Pollution_level: Level of pollution in the area where 0 is unpolluted and 1 is very polluted (Float).
Plot_size: Size of the plot in the field (Ha) (Float). (DUMMY VARIABLE)
Chosen_crop: Type of crop chosen for cultivation (Text).
Annual_yield: Annual yield from the field (Float). This is the total output of the field. The field size and type of crop will affect the Annual Yield (DUMMY VARIABLE - Removed)

5. Target variable
Standard_yield: Standardised yield expected from the field, normalised per crop (Float). This is independent of field size, or crop type. Multiplying this number by the field size, and average crop yield will give the Annual_Yield.
