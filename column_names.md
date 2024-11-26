# Columns
1: **Place_ID** X Date => A unique identifier combining the place ID and date.
2: **Date** => The date of the observation.
3: **Place_ID** => A unique identifier for the city or location.
4: **target** - The PM2.5 particulate matter concentration (the main prediction target) => **tiny particles are a significant component of air pollution and are small enough to penetrate deep into the lungs and even enter the bloodstream, measured in micrograms per cubic meter (μg/m3) of air.**
5: **target_min** - The minimum observed PM2.5 concentration for the day.
6: **target_max** - The maximum observed PM2.5 concentration for the day.
7: **target_variance** - The variance in PM2.5 concentration for the day.
8: **target_count** - The count of observations used to compute PM2.5 metrics.
9: **precipitable_water_entire_atmosphere** - Total column water vapor content in the atmosphere => **quantifies the depth of water that would result if all the water vapor in the column were condensed and precipitated, expressed in mm**
#DROP 10: **relative_humidity_2m_above_ground** - Relative humidity percentage at 2 meters above ground.
11: **specific_humidity_2m_above_ground** - Specific humidity (moisture content) at 2 meters above ground.
12: **temperature_2m_above_ground** - Air temperature at 2 meters above ground (in **Kelvin**).
13: **u_component_of_wind_10m_above_ground** - Horizontal wind component (west-east) at 10 meters above ground=> Positive values of the u-component indicate wind moving from the west to the east (blowing eastward). Negative values indicate wind moving from the east to the west (blowing westward)
14: **v_component_of_wind_10m_above_ground** - Vertical wind component (south-north) at 10 meters above ground. Positive values of the v-component indicate wind moving from the south to the north (blowing northward).Negative values indicate wind moving from the north to the south (blowing southward).
### Measurement of the various atmospheric components and polluants
15: **L3_NO2_NO2_column_number_density** - Total NO2 column density in the atmosphere.
16: **L3_NO2_NO2_slant_column_number_density** - Slant NO2 column density (accounts for sensor angle).
#DROP 17: **L3_NO2_absorbing_aerosol_index** - Index measuring absorbing aerosols affecting NO2 detection.
18: **L3_NO2_cloud_fraction** - Fraction of cloud cover in NO2 observations.
#DROP19: **L3_NO2_sensor_altitude** - Altitude of the NO2 sensor.
#DROP20: **L3_NO2_sensor_azimuth_angle** - Sensor azimuth angle for NO2 detection.
#DROP21: **L3_NO2_sensor_zenith_angle** - Sensor zenith angle for NO2 detection.
#DROP22: **L3_NO2_solar_azimuth_angle** - Solar azimuth angle during NO2 observations.
#DROP23: **L3_NO2_solar_zenith_angle** - Solar zenith angle during NO2 observations.
24: **L3_NO2_stratospheric_NO2_column_number_density** - Stratospheric NO2 column density.
#Drop25: **L3_NO2_tropopause_pressure** - Atmospheric pressure at the tropopause (boundary between troposphere and stratosphere).
26: **L3_NO2_tropospheric_NO2_column_number_density** - Tropospheric NO2 column density.
27: **L3_O3_O3_column_number_density** - Total O3 column density in the atmosphere.
#Drop28: **L3_O3_O3_effective_temperature** - Effective temperature for ozone measurement.
29: **L3_O3_cloud_fraction** - Fraction of cloud cover in O3 observations.
#Drop30: **L3_O3_sensor_azimuth_angle** - Sensor azimuth angle for O3 detection.
#Drop31: **L3_O3_sensor_zenith_angle** - Sensor zenith angle for O3 detection.
#Drop32: **L3_O3_solar_azimuth_angle** - Solar azimuth angle during O3 observations.
#Drop33: **L3_O3_solar_zenith_angle** - Solar zenith angle during O3 observations.
34: **L3_CO_CO_column_number_density** - Total CO column density in the atmosphere.
35: **L3_CO_H2O_column_number_density** - Water vapor column density from CO measurements.
#Drop36: **L3_CO_cloud_height** - Cloud height during CO measurements.
#Drop37: **L3_CO_sensor_altitude** - Altitude of the CO sensor.
#Drop38: **L3_CO_sensor_azimuth_angle** - Sensor azimuth angle for CO detection.
#Drop39: **L3_CO_sensor_zenith_angle** - Sensor zenith angle for CO detection.
#Drop40: **L3_CO_solar_azimuth_angle** - Solar azimuth angle during CO observations.
#Drop41: **L3_CO_solar_zenith_angle** - Solar zenith angle during CO observations.
42: **L3_HCHO_HCHO_slant_column_number_density** - Slant column density of formaldehyde (HCHO).
43: **L3_HCHO_cloud_fraction** - Fraction of cloud cover in HCHO observations.
#Drop44: **L3_HCHO_sensor_azimuth_angle** - Sensor azimuth angle for HCHO detection.
#Drop45: **L3_HCHO_sensor_zenith_angle** - Sensor zenith angle for HCHO detection.
#Drop46: **L3_HCHO_solar_azimuth_angle** - Solar azimuth angle during HCHO observations.
#Drop47: **L3_HCHO_solar_zenith_angle**- Solar zenith angle during HCHO observations.
48: **L3_HCHO_tropospheric_HCHO_column_number_density** - Tropospheric column density of HCHO.
49: **L3_HCHO_tropospheric_HCHO_column_number_density_amf** - Tropospheric HCHO density adjusted by the air mass factor (AMF).
#Drop50: **L3_CLOUD_cloud_base_height** - Base height of clouds in the observation area.
#Drop51: **L3_CLOUD_cloud_base_pressure** - Pressure at the cloud base.
52: **L3_CLOUD_cloud_fractiom** - Fraction of cloud cover.
53: **L3_CLOUD_cloud_optical_depth** - Optical depth of clouds (related to transparency).
#Drop54: **L3_CLOUD_cloud_top_height** - Height of the top of clouds in the observation area.
#Drop55: **L3_CLOUD_cloud_top_pressure** - Pressure at the cloud top.
#Drop56: **L3_CLOUD_sensor_azimuth_angle** - Sensor azimuth angle for cloud observations.
#Drop57: **L3_CLOUD_sensor_zenith_angle** - Sensor zenith angle for cloud observations.
#Drop58: **L3_CLOUD_solar_azimuth_angle** - Solar azimuth angle during cloud observations.
#Drop59: **L3_CLOUD_solar_zenith_angle** - Solar zenith angle during cloud observations.
#60: **L3_CLOUD_surface_albedo** - Surface albedo (reflectivity) observed in the cloud area.
#Drop61: **L3_AER_AI_absorbing_aerosol_index** - Index measuring absorbing aerosols in the atmosphere.
#Drop62: **L3_AER_AI_sensor_altitude** - Altitude of the aerosol index sensor.
#Drop63: **L3_AER_AI_sensor_azimuth_angle** - Sensor azimuth angle for aerosol index detection.
#Drop64: **L3_AER_AI_sensor_zenith_angle**- Sensor zenith angle for aerosol index detection.
#Drop65: **L3_AER_AI_solar_azimuth_angle** - Solar azimuth angle during aerosol index observations.
#Drop66: **L3_AER_AI_solar_zenith_angle**- Solar zenith angle during aerosol index observations.
67: **L3_SO2_SO2_column_number_density**- Total SO2 column density in the atmosphere.
68: **L3_SO2_SO2_column_number_density_amf** - SO2 column density adjusted by the air mass factor (AMF).
69: **L3_SO2_SO2_slant_column_number_density**- Slant column density of SO2.
#Drop70: **L3_SO2_absorbing_aerosol_index** - Index measuring absorbing aerosols affecting SO2 detection.
71: **L3_SO2_cloud_fraction** - Fraction of cloud cover in SO2 observations.
#Drop72: **L3_SO2_sensor_azimuth_angle** - Sensor azimuth angle for SO2 detection.
#Drop73: **L3_SO2_sensor_zenith_angle** - Sensor zenith angle for SO2 detection.
#Drop74: **L3_SO2_solar_azimuth_angle** - Solar azimuth angle during SO2 observations.
#Drop75: **L3_SO2_solar_zenith_angle** - Solar zenith angle during SO2 observations.
#Drop76: **L3_CH4_CH4_column_volume_mixing_ratio_dry_air** - Methane (CH4) volume mixing ratio in dry air.
#Drop77: **L3_CH4_aerosol_height** - Aerosol height during CH4 observations.
#Drop78: **L3_CH4_aerosol_optical_depth** - Optical depth of aerosols in CH4 measurements.
#Drop79: **L3_CH4_sensor_azimuth_angle** - Sensor azimuth angle for CH4 detection.
#Drop80: **L3_CH4_sensor_zenith_angle** - Sensor zenith angle for CH4 detection.
#Drop81: **L3_CH4_solar_azimuth_angle** - Solar azimuth angle during CH4 observations.
#Drop82: **L3_CH4_solar_zenith_angle** - Solar zenith angle during CH4 observations.