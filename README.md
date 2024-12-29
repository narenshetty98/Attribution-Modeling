# Attribution-Modeling
This project focuses on the in-depth analysis of advertising campaigns, examining their costs, performance, and effectiveness. The notebook utilizes large-scale campaign data to extract valuable insights through data preprocessing, visualization, and cost-per-conversion analysis.

## Project Overview
The dataset contains records of advertising campaigns, including timestamps, costs, and conversions. This project aims to identify the most and least cost-effective campaigns, examine patterns in categorical features, and calculate metrics such as cost per conversion to inform strategic decisions.

## Key Features
- **Data Handling**:
  - Efficient processing of a large dataset using chunked loading to handle memory constraints.
  - Conversion of data types and cleaning to ensure compatibility and accuracy.
- **Visualization**:
  - Analysis of campaign performance through bar charts and histograms.
  - Visualization of top and bottom campaigns by cost and cost per conversion.
- **Cost and Conversion Analysis**:
  - Calculation of average costs for campaigns.
  - Identification of top and bottom campaigns based on cost per conversion metrics.
  - Examination of campaign timelines to understand performance over time.
- **Attribution Modeling**:
  - **Linear Attribution**: Distributed conversion credit across all touchpoints equally.
  - **Time Decay Modeling**: Assigned higher weights to recent touchpoints leading to conversions.
  - **Markov Chain Analysis**: Modeled user journeys to understand the probability of conversions and identify the most influential touchpoints.
  


## Results
The project highlights:
- Campaigns with the highest and lowest costs and cost per conversion.
- Insights into campaign timelines, helping to identify periods of optimal performance.
- Patterns in cost distribution across campaigns.
- Attribution results showcasing the importance of various touchpoints in driving conversions.

