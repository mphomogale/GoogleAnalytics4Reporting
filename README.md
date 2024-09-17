# Google Looker Studio Project with GA4 and BigQuery

![Project Status](https://img.shields.io/badge/Project-Active-brightgreen)

## Project Overview

This project is a comprehensive marketing analytics dashboard built using **Google Analytics 4 (GA4)** data, transformed with **BigQuery**, and visualized in **Looker Studio**. It provides insights into campaign performance, including cost efficiency, user engagement, and revenue growth. 

The dashboard offers real-time tracking of critical performance indicators such as **Cost**, **Clicks**, **Impressions**, **Conversions**, and **Revenue**, helping marketers to assess the effectiveness of campaigns and optimize budget allocation.

## Key Technologies

- **Google Analytics 4 (GA4):** Source for collecting website/app data, such as clicks, impressions, and user behavior.
- **BigQuery:** Used for data transformation, enabling fast and scalable querying of large datasets.
- **Looker Studio:** Provides an interactive interface for visualizing the transformed data, offering real-time insights.

## Dashboard Features

The dashboard includes several essential sections for analyzing campaign performance:

- **Cost Analysis**: Tracks the total spending and compares it against the last period with percentage change indicators.
  
- **Clicks**: Displays the number of user interactions (clicks) with campaigns, comparing current and past periods.

- **Impressions**: Shows the number of times your ads were viewed, with a percentage decrease or increase.

- **Conversions**: Displays the total number of successful conversions, offering insights into campaign effectiveness.

- **Revenue Analysis**: This section reveals the total revenue generated from campaigns. In the example, revenue increased by a massive **395.8%** compared to the last period.

- **CPM (Cost Per Thousand Impressions)**: Tracks the efficiency of your spending by calculating the CPM metric and highlighting changes.

### Visualizing Data

Below the core metrics, the dashboard provides a **Campaign Cost of Visibility** graph, showing trends in campaign cost and impressions over time. This helps identify when campaigns were most visible to users and whether the cost was optimized.

## Dashboard Preview

![Dashboard Preview](./path_to_image.png)

> The above screenshot provides an overview of the key metrics like Cost, Clicks, Impressions, Conversions, and Revenue, along with the CPM rate. Each metric shows a comparison with the previous period, allowing for quick identification of areas needing attention.

### Interactive Filters

The dashboard offers **dynamic filters** that enable users to adjust the date range and specific campaigns being analyzed. This feature allows you to dive deep into individual campaign performance or view overall trends during specific timeframes.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/username/repo-name.git
    ```

2. **BigQuery Setup**:
    - Export your GA4 data to **BigQuery**.
    - Use the SQL queries provided in the `/bigquery_queries/` folder to process the raw GA4 data and transform it for reporting.

3. **Looker Studio Setup**:
    - Connect your **BigQuery** dataset to **Looker Studio**.
    - Import the visualization templates provided in the `/looker_studio/` folder to configure the dashboard.

4. **Configure Filters and Metrics**:
    - Customize filters (such as campaign and date range) and metrics (such as conversions and revenue) in Looker Studio to fit your specific reporting needs.

## How to Use

1. **Filter Data**: Use the interactive campaign and date range filters to narrow down your report to specific campaigns or periods.
2. **Analyze Key Metrics**: Review important metrics such as Cost, Clicks, Impressions, Conversions, and Revenue to understand the effectiveness of campaigns.
3. **Monitor Trends**: Use the line graph to track campaign costs and impressions over time for better visibility and trend analysis.

## Folder Structure

```
- /bigquery_queries/  # SQL queries for data transformation in BigQuery
- /looker_studio/     # Looker Studio templates and configuration files
- /images/            # Screenshots or preview images for the README
```

## Contributing

Contributions are welcome! If you would like to improve the dashboard or add new features, feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- **Developer**: [Your Name](mailto:youremail@example.com)
- **Repository Link**: [GitHub Repo](https://github.com/username/repo-name)

---

### Notes:

- You can replace `./path_to_image.png` with the path to the actual image file.
- I’ve added more specific details on each metric based on the screenshot you provided, such as **Clicks, Impressions, Conversions, CPM**, and **Revenue**. The filter for selecting campaigns and date ranges is also reflected in the instructions.
  
Feel free to adjust any part of this to better fit your project! Let me know if you'd like further tweaks.
