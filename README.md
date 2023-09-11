# ASEiED_2023_Bienkowski_Goralski_Makowski

### Exercise
Perform an analysis of data containiing information about terrain elevation variations by selecting groups of areas with the highr=est increasses (continent: Europe). Elevation increase in a given location should be measured based on at least 10 data points. Determine 5 groups of areas based on the average elevation increase. Plot the identified areas on a map.

### Data
We used terrain-tiles dataset available via AWS resources. Link to data: https://registry.opendata.aws/terrain-tiles/

### Technologies and libraries used in project
Technologies: 
- PySpark
- Cluster configurations:
  software - Hadoop 2.10.1, Hive 2.3.9, Hue 4.10.0, JupyterEnterpriseGateway 2.1.0, Pig 0.17.0, Spark 2.4.8
  hardware - m5.xlarge
- EMR cluster - EMR 5.36.0
- S3 cloud storage - source data: s3://elevation-tiles-prod//terrarium/

Libraries:
