# nrr95p dataset

A dataset containing information about daily standardised precipitation exceeding fixed percentiles (95) for Europe based on ERA5 [Extreme precipitation risk indicators for Europe and European cities from 1950 to 2019](https://cds.climate.copernicus.eu/cdsapp#!/dataset/sis-european-risk-extreme-precipitation-indicators?tab=overview).

In particular, it provides a directory for each year with daily images representing the nrr95p value, as well as one ore more directories for each year of gifs representing the evolution of this information over 10 days.

One could also use the provided notebook to extract information about a missing year in the same format downloading the NetCDF file using the [form](https://cds.climate.copernicus.eu/cdsapp#!/dataset/sis-european-risk-extreme-precipitation-indicators?tab=form) provided by ERA5 specifying:
 - Spatial coverage: Europe
 - Variable: Standardised precipitation exceeding fixed percentiles
 - City: -
 - Product type: ERA5
 - Temporal aggregation: Daily
 - Percentile: 95th
 - Return period: -
 - Period:
   - Single year: \<the desired year\>
   - Climatology: -
 - Format: Zip file (.zip)

and then extracting and moving the NetCDF file in the same directory of the notebook.

The aim is to provide a simple dataset for experimenting with video prediction on climate data, especially for extreme events.

## Examples

Images representing the nrr95p value over Europe over the first 10 days of 2019:

![nrr95p_2019_0](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_0.png?raw=true)
![nrr95p_2019_1](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_1.png?raw=true)
![nrr95p_2019_2](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_2.png?raw=true)
![nrr95p_2019_3](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_3.png?raw=true)
![nrr95p_2019_4](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_4.png?raw=true)
![nrr95p_2019_5](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_5.png?raw=true)
![nrr95p_2019_6](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_6.png?raw=true)
![nrr95p_2019_7](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_7.png?raw=true)
![nrr95p_2019_8](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_8.png?raw=true)
![nrr95p_2019_9](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_9.png?raw=true)

Gif spanning over the same first 10 days of 2019:

![nrr95p_2019_0_to_9](https://github.com/alberto-paparella/nrr95p/blob/main/images/nrr95p_2019_0_to_9.gif?raw=true)
