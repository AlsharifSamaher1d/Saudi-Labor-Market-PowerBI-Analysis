# Saudi Labor Market Power BI Analysis

A data visualization and labor-market analysis project focused on the **Saudi Arabian manpower sector**. The project uses Saudi government open data to explore employment, unemployment, workforce demographics, regional variation, subsidy programs, and labor-market trends in the context of **Saudi Vision 2030**.

## Live Power BI Dashboard

**[View the Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYWUyY2M2ZDQtMWI3Zi00ZmU3LWJjMGEtZjBiMWRhMzI5YzQ1IiwidCI6ImUyNmJhYjRiLTk3ZTYtNDc1NC1iMTYzLTYwZjgyMzdlODUzMSIsImMiOjl9)**

The interactive dashboard allows users to explore Saudi labor-market indicators across regions, sectors, age groups, employment categories, and support-program participation.

## Project Overview

Saudi Arabia's labor market has been undergoing major changes driven by economic diversification, Saudization policies, workforce reforms, and initiatives associated with Saudi Vision 2030. This project applies data visualization and exploratory analysis to help understand labor-market patterns and support evidence-based interpretation of employment and policy-related indicators.

The analysis focuses on:

- Employment distribution in government and private-sector jobs.
- Regional unemployment trends.
- Workforce demographics and age distributions.
- Labor-market participation and regional differences.
- Women's participation and empowerment.
- Subsidy and support programs such as **Qurrah** and **Wusool**.
- Retirement-related patterns and workforce composition.

## Objectives

- Analyze employment distribution across sectors and regions of Saudi Arabia.
- Examine unemployment-rate trends across different regions.
- Explore private-sector employment patterns and workforce characteristics.
- Evaluate labor-support initiatives such as **Qurrah** and **Wusool** in relation to women's participation in the labor market.
- Explore regional differences in employment and workforce composition.
- Investigate retirement-related patterns, including retirement age and reasons for retirement.

## Data Source

The datasets used in this project were selected from the **Saudi Open Data Platform**, provided by the Saudi government. The selected data covers employment rates, workforce demographics, sector-specific employment information, unemployment rates, and subsidy-program data.

**[Project Data and Supporting Files on Google Drive](https://drive.google.com/drive/folders/11z-pcoY_odvDhuHnorn9VafAUaehCZnx)**

Large datasets and supporting project materials are kept on Google Drive rather than duplicated in this repository.

## Data Preparation

The data-preparation workflow included:

- Handling missing data through exclusion or appropriate treatment.
- Standardizing variable names, units, and formats.
- Reviewing and addressing outliers.
- Integrating relevant datasets for analysis.
- Preparing clean datasets for Power BI visualization.

Three project notebooks are included in this repository with their original saved outputs:

- [`Unemployment_Analysis_2016_2023.ipynb`](Unemployment_Analysis_2016_2023.ipynb) — regional unemployment analysis and visualization.
- [`Qurrah_Data_Cleaning.ipynb`](Qurrah_Data_Cleaning.ipynb) — cleaning and preparation of Qurrah program data.
- [`Wusool_Data_Cleaning.ipynb`](Wusool_Data_Cleaning.ipynb) — cleaning and preparation of Wusool program data.

## Power BI Dashboard

The final analysis was presented through an interactive **Power BI dashboard** using visual elements such as bar charts, line charts, distribution charts, regional comparisons, filters, and slicers.

The dashboard supports exploration of the data by region, sector, age, employment category, program participation, and other workforce dimensions.

## Key Analyses

### Public vs. Private Sector Age Distribution

Most employees in both sectors are concentrated in the **26–40** and **41–59** age groups. The private sector contains substantially more employees than the public sector in the analyzed data, while the youngest and oldest age groups contain fewer employees.

### Qurrah and Wusool Age Distribution

The age distribution of **Qurrah** users is concentrated around age 30, while **Wusool** has a younger peak around age 25 and a broader distribution across the early-20s to mid-30s age range.

### Disability Status in Qurrah and Wusool

Both programs show similar proportions of users with and without disabilities. Because Wusool has a larger user base, the absolute number of users with disabilities is higher in Wusool.

### Regional Unemployment Trends, 2016–2023

The regional unemployment analysis shows substantial variability over time. Many regions experienced noticeable increases around **2020**, followed by stabilization or declines in several regions, while some areas continued to show stronger fluctuations.

## Tools and Technologies

- **Power BI** — interactive dashboard and visualization
- **Python** — data cleaning, preparation, and exploratory analysis
- **Pandas / NumPy** — tabular data processing
- **Matplotlib / Seaborn** — exploratory visualization
- **Jupyter Notebook** — analysis workflow
- **Microsoft Excel** — source and prepared tabular datasets
- **Saudi Open Data Platform** — primary data source

## Repository Structure

```text
Saudi-Labor-Market-PowerBI-Analysis/
├── README.md
├── Unemployment_Analysis_2016_2023.ipynb
├── Qurrah_Data_Cleaning.ipynb
└── Wusool_Data_Cleaning.ipynb
```

## Limitations

- The project depends on the scope and availability of government open datasets.
- Some research questions require broader economic or longitudinal evidence beyond descriptive visualization alone.
- Visual trends and associations shown in the dashboard should not automatically be interpreted as causal relationships.
- Differences in reporting periods and dataset structures may affect direct comparison across indicators.

## Project Significance

This project demonstrates how data visualization can support understanding of labor-market trends in Saudi Arabia and communicate complex workforce information more clearly. The analysis aligns with the broader goals of Saudi Vision 2030 by examining employment, workforce participation, regional variation, and labor-support initiatives through a data-driven approach.

## Authors

- **Hanan M. Alharthi**
- **Samaher S. Alsharif**
- **Shahd H. Altalhi**
