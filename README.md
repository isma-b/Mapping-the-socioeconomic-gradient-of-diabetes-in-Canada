

Diabetes Gradient in Canada





This project analyzes the prevalence of diabetes across Canadian provinces using official data from Statistics Canada (Table 13-10-0096-01). The goal is to map and understand the socioeconomic gradient of diabetes, showing how health outcomes vary regionally.

Overview


The notebook performs:
1. Loading and cleaning of Statistics Canada data
2. Filtering for diabetes prevalence indicators
3. Statistical summary of provincial rates
4. Geographic mapping of diabetes prevalence using a choropleth map
5. Discussion of regional health disparities

Key Findings
Diabetes prevalence varies noticeably across provinces.
Higher prevalence tends to align with regions facing socioeconomic challenges.
Highlights the importance of addressing structural health inequalities in Canada.

Data Source


Dataset: Health indicator statistics, annual estimates — Table 13-10-0096-01 Provider: Statistics Canada Frequency: Annual

Requirements


Python 3.10 or higher
pandas, geopandas, matplotlib, seaborn
Run the notebook directly in Google Colab for best compatibility.

Visualization


The notebook generates a choropleth map showing diabetes prevalence by province.

License


This project uses open data provided by Statistics Canada under the Open Government License – Canada.





Conclusion



This project analyzes provincial variation in diabetes prevalence across Canada using verified data from Statistics Canada’s Health Indicators, annual estimates (Table 13-10-0096-01). After cleaning and standardizing the dataset, the analysis filtered for adults aged 12 years and over, both sexes, and the most recent reference year (2022). The resulting choropleth map and statistical summary reveal clear spatial patterns: prevalence rates are higher in Atlantic Canada and Newfoundland and Labrador, moderate across the Prairies, and lower in Ontario and British Columbia.
These findings align with established evidence that diabetes prevalence follows a socioeconomic gradient, influenced by factors such as income distribution, healthcare access, and regional lifestyle patterns. The use of open national data, transparent preprocessing, and reproducible geospatial mapping demonstrates technical proficiency in data wrangling, statistical reasoning, and visualization.
While the estimates are self-reported and not age-standardized, the regional differences are robust and informative for public health and policy design. Extending this work to include socioeconomic or demographic covariates, temporal trends, and uncertainty modeling would further enhance its explanatory power. Overall, the project integrates data science methods with applied public health insight showcasing an ability to translate complex datasets into meaningful, evidence-based interpretation.


