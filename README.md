# Air-Quality-Index-of-India-2022-2025-
Data analysis and visualization of AQI in India
Dataset Overview
A comprehensive hourly dataset tracking atmospheric conditions and air quality across 29 major Indian cities (28 states + Delhi) from 2022 to 2025. This dataset provides detailed insights into India's environmental patterns, pollution trends, and meteorological conditions.

🗺️ Geographic Coverage

Cities Covered: 29 major cities representing all 28 Indian states + Delhi
Time Period: 2022 to 2025
Records: 842,160 hourly observations
Features: 63 parameters covering weather, pollution, and temporal data

📊 Dataset Specifications

    Total Records: 842,160
    Features: 63 columns
    Temporal Resolution: Hourly data
    Period: 2022-2025 (4 years)
    Memory Usage: ~405 MB

🏙️ Indian Cities Included
(Representing all 28 states + Union Territory of Delhi)

Delhi
Mumbai (Maharashtra)
Chennai (Tamil Nadu)
Kolkata (West Bengal)
Bengaluru (Karnataka)
Hyderabad (Telangana)
Ahmedabad (Gujarat)
Pune (Maharashtra)
Jaipur (Rajasthan)
Lucknow (Uttar Pradesh)
And other major state capitals…
🗂️ Data Columns
📍 Geographic & Temporal Context
Column	Description	Relevance for India
City, State	Indian city and state names	Covers all states + Delhi
Latitude, Longitude	Geographic coordinates	Indian subcontinent coverage
Datetime	Hourly timestamp (2022-2025)	Multi-year analysis
Season	Indian seasons (Winter, Summer, Monsoon, Post-Monsoon)	Seasonal pollution patterns
Festival_Period	Indian festival indicators	Diwali, Holi impacts on air quality
Crop_Burning_Season	Agricultural burning periods	Stubble burning events
🌡️ Meteorological Parameters
Temperature & Humidity

Temp_2m_C - Ambient temperature (°C)
Humidity_Percent - Relative humidity
Dew_Point_C - Dew point temperature
Humidity_Category - Comfort levels
Wind Patterns

Wind_Speed_10m_kmh - Surface wind speed
Wind_Dir_10m - Wind direction (critical for pollution dispersion)
Wind_Gusts_kmh - Wind gusts
Wind_Stagnation - Air stagnation events
Precipitation & Pressure

Precipitation_mm, Rain_mm - Monsoon rainfall tracking
Is_Raining, Heavy_Rain - Rain events
Pressure_MSL_hPa - Monsoon pressure systems
☀️ Solar & Cloud Data
Solar_Radiation_Wm2 - Total solar radiation
Direct/Diffuse_Radiation_Wm2 - Radiation components
Cloud_Cover_Percent - Total cloud cover
Cloud_Low/Mid/High_Percent - Cloud altitude distribution
Sunshine_Seconds - Bright sunshine duration
Is_Daytime - Day/night indicator
🏭 Air Quality Metrics (Critical for India)
Particulate Matter

PM2_5_ugm3 - Fine particulate matter (primary concern)
PM10_ugm3 - Coarse particulate matter
PM_Ratio - PM2.5/PM10 ratio (source identification)
Dust_ugm3 - Dust concentrations
AOD - Aerosol Optical Depth
Gaseous Pollutants

CO_ugm3 - Carbon monoxide (vehicular/industrial)
NO2_ugm3 - Nitrogen dioxide (traffic, industries)
SO2_ugm3 - Sulfur dioxide (industrial, power plants)
O3_ugm3 - Ozone (secondary pollutant)
📊 Air Quality Indices
US AQI System

US_AQI - Overall US AQI
US_AQI_PM25, US_AQI_PM10 - PM-specific indices
US_AQI_NO2, US_AQI_O3, US_AQI_CO - Gas-specific indices
EU AQI System

EU_AQI - European Air Quality Index
EU_AQI_PM25, EU_AQI_PM10 - European standards
India-Specific Categories

AQI_Category - Overall air quality category
PM25_Category_India - India-specific PM2.5 categorization
🌪️ Special Features
Temp_Inversion - Temperature inversion events (critical for winter pollution in North India)
⚠️ Data Quality Notes
High Completeness: Most columns have 842,160 non-null values
Minor Missing Values:
US/EU AQI columns: ~145 missing records
AQI_Category: 2,516 missing
US_AQI_NO2: 2 missing
US_AQI_O3: 73 missing
🎯 India-Specific Analysis Opportunities
Seasonal Patterns
Winter (Dec-Feb): Severe PM2.5 pollution in Indo-Gangetic plain
Summer (Mar-May): Dust storms, high O3 levels
Monsoon (Jun-Sep): Natural cleansing, improved AQI
Post-Monsoon (Oct-Nov): Crop burning impacts in North India
Geographic Hotspots
Northern Plains: Delhi, Lucknow - Winter smog, crop burning
Coastal Cities: Mumbai, Chennai - Marine influence, humidity
Southern Plateau: Bengaluru, Hyderabad - Moderate pollution
Eastern India: Kolkata - Industrial and vehicular pollution
Event-Based Analysis
Festival Impacts: Diwali fireworks, Holi bonfires
Agricultural Cycles: Stubble burning seasons
Meteorological Events: Western disturbances, monsoon progress
🛠️ Suggested Research Topics
Public Health
Correlation between PM2.5 and respiratory health alerts
Seasonal mortality and morbidity patterns
Vulnerable population exposure assessment
Policy Analysis
Effectiveness of pollution control measures
Graded Response Action Plan (GRAP) impact assessment
City-specific intervention strategies
Climate Studies
Urban heat island effects across Indian cities
Monsoon variability and air quality relationships
Long-term climate change impacts on pollution
Source Apportionment
Industrial vs. vehicular pollution contributions
Agricultural burning impact quantification
Dust source identification
