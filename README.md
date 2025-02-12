# Clustering-Communities-For-Environmental-Justice-In-Canada

### Project Overview:

This repository houses the "Clustering Communities for Environmental Justice in Canada" project, designed to identify and analyze clusters of communities facing environmental injustice. Utilizing data from the National Pollutant Release Inventory (NPRI) and the Canadian Index of Multiple Deprivation (CIMD), the project employs k-means clustering to highlight the relationships between industrial pollutants and community demographics.

### Objectives:

* Integrate Environmental and Socio-Economic Data: Combining NPRI environmental data with CIMD socio-economic metrics to assess the impact of industrial activities on vulnerable communities.
* Identify and Analyze Community Clusters: Using k-means clustering to group communities by similar environmental exposure and demographic characteristics.
* Inform Policy Making: Providing data-driven insights to help policymakers create effective interventions tailored to the needs of each identified cluster.

## Data Sources:
* National Pollutant Release Inventory (NPRI): Tracks a comprehensive range of pollutants across Canada, highlighting major industrial sources of emissions.
* Canadian Index of Multiple Deprivation (CIMD): Provides detailed demographic data that illustrates the socio-economic conditions of Canadian communities.

## Methodology:

### Cluster Analysis

* K-means Clustering: Applied to identify distinct groups of communities affected by similar types and levels of pollutants, linked with specific demographic profiles.
* Silhouette Analysis: Used to determine the optimal number of clusters, ensuring meaningful segmentation of data for analysis.

### Geospatial Analysis

* Mapping Cluster Distribution: Visualizes the geographic spread of clusters across Canada, illustrating how environmental burdens are distributed regionally.

### Statistical Analysis and Interpretation

* Summary Statistics: Aggregate cluster data to highlight key environmental and socio-economic traits.
* Detailed Cluster Profiles: Each cluster is analyzed to reveal its predominant industries, geographic concentration, and unique environmental and social characteristics.

### Technologies Used
* Python: For data processing, clustering, and statistical analysis.
* R: For additional data manipulation and advanced visualizations.
* QGIS Software: To map and analyze the spatial distribution of data.

## Results

The analysis successfully delineated five distinct clusters, each characterized by specific industrial profiles and unique combinations of environmental and social factors:
* Cluster 0: Characterized by high emissions of Nitrogen Oxides and Carbon Monoxide from waste treatment and oil and gas industries, primarily found in Northern British Columbia and major urban centers.
* Cluster 1: Notable for high Sulphur Dioxide emissions from industries less concentrated in specific geographic areas.
* Cluster 2: Exhibits low financial dependency and higher social stability, despite significant environmental impacts.
* Cluster 3: Dominated by the highest levels of PM10 and VOCs, underscoring significant environmental risk.
* Cluster 4: Unique for having no emissions reported, highlighting areas with minimal direct industrial impact but potential indirect exposures.

## Conclusion:

This project utilized the National Pollutant Release Inventory (NPRI) and the Canadian Index of Multiple Deprivation (CIMD) to reveal key industries and regions contributing to environmental injustice in Canada, emphasizing the necessity for targeted policies. Through detailed clustering analysis, we identified the critical need for enhanced community resilience programs and standardized industry reporting to improve environmental monitoring and policy-making. The collaboration between environmental agencies, social services, and community organizations highlighted in this study underlines the importance of a unified approach to addressing complex environmental justice issues effectively.
