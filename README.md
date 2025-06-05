# CarbonScope :  Paving the Way to Eco-Friendly Living
### Overview  
ClimateGuard is a cloud-based data analytics project designed to monitor, analyze, and forecast carbon emissions from US domestic flights, electricity consumption, and fossil fuel usage. By leveraging advanced data processing techniques and cloud computing, this project aims to promote sustainability by providing actionable insights into carbon footprints and advocating for eco-friendly practices.

### Features
1. Carbon Emissions Analysis:  
    - Calculated emissions from domestic flights using thrust-specific fuel consumption (TSFC) methodologies and real-time air traffic data from the OpenSky Network API.
    - Monitored electricity consumption across US states and computed emissions using carbon intensity metrics.
    - Analyzed sectoral emissions (Residential, Industrial, Commercial) based on fuel types (Coal, Natural Gas, Petroleum).

2. Cloud-Based Data Pipelines:
    - Automated data extraction, transformation, and storage using AWS Lambda, S3, and EventBridge.
    - Optimized performance with Redis caching for latency reduction and EC2 instances for dependency management.

3. Predictive Analytics:
    - Conducted time-series forecasting on historical data (1970–2021) to predict future CO2 emission trends.
    - Visualized emissions data through interactive dashboards powered by Flask backend.

### Technologies Used
- Programming Languages: Python
- Cloud Services: AWS Lambda, S3, EC2, EventBridge
- APIs: OpenSky Network API, US Energy Information Administration API
- Data Management: Redis caching, JSON storage in S3

### Future Enhancements
- Real-time streaming pipelines for hourly updates.
- Predictive models to assess environmental impacts of CO2 emissions.
- Integration of additional sectors like transportation and industrial processes into the dashboard.

This project bridges the gap between data-driven insights and actionable sustainability practices, empowering stakeholders to make informed decisions for a greener future.
