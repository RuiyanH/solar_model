# Solar Panels Project

## 🔍 Project Summary
This project trains a **polynomial regression model** to predict **solar panel output intensity** (in megawatts, MW) using a blend of:

### Input Features:

1. **Weather-based (NOAA)**:
- Temperature (*1000, inferred from values ending in 00)
- Hours of daylight
- Humidity (%, 1–2 digit integer)
- Precipitation
- Visibility (values ending in SM)
  
2. **Astronomical/Theoretical**:
- Latitude & Longitude
- Day of the year
- Time of day (5-minute intervals)
- Theoretical solar intensity (based on sun position)

### Output:
- Predicted solar intensity in MW
- Error score versus actual solar panel data

### 📊 Data Sources:
- Weather:
  NOAA ASOS 5-minute data: https://www.ncei.noaa.gov/pub/data/asos-fivemin/Inventory/

- Solar Output Ground Truth:
  NREL Solar Data: https://www.nrel.gov/grid/solar-power-data.html
