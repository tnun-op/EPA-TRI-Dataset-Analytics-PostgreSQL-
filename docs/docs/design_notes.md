## Schema Design
- Separated data by facility, chemical usage, emissions, and parent company
- Cleaned and normalized all tables in order to remove duplications, and errors
- Incorporated a table regarding industry benchmarks using data found across all previously made tables

## Analytical View
- 'facility_vs_industry': compares individual facility performance and efficiency across differnt metrics to industry averages
- 'industry_benchmark_view': aggregates data from all tables to produce industry benchmarks
- 'industry_revenue_efficiency': allows the comparison of industries in regards to revenue per unit of emissions
- 'parent_company_efficiency': ranks parent companies based on environmental and business efficiency 

## Iterative Development
- Started with importing raw data from the TRI dataset, converting data file types to match server acceptance
- Introduced normalization by facility and industry averages
- Added revenue estimates after industry benchmarking

## Assumptions
- Revenue per facility is estimated from publicly available Census data
- Analysis is only for the year (2024) and does not portray historical trends        
- Industry benchmarks are averages, not exact financial metrics

## Future Enhancements
- Longitudinal TRI analysis for trends and patterns
- Geographic benchmarking by state or region
