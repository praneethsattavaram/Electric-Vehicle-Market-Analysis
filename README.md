# Electric Vehicle Market Analysis  

## Overview  
This project explores the market size and trends of electric vehicles (EVs) by analyzing a dataset containing EV registration data. The analysis includes EV adoption trends, geographical distribution, vehicle types, popular manufacturers and models, electric range statistics, and market growth forecasting.

---

## Dataset  
The dataset, **Electric_Vehicle_Population_Data.csv**, includes information on EV registrations, such as:  
- **Model Year**: The year the vehicle was manufactured.  
- **County**: The county where the vehicle is registered.  
- **City**: The city of registration.  
- **Electric Vehicle Type**: Type of EV (e.g., BEV, PHEV).  
- **Make and Model**: Manufacturer and model of the vehicle.  
- **Electric Range**: The vehicle's electric range in miles.  

---

## Key Analyses  

### 1. EV Adoption Over Time  
- Visualization of the number of EVs registered by model year.  
- Insights into the growth trajectory of EV registrations.  

### 2. Geographical Distribution  
- Analysis of EV registrations across counties and cities.  
- Identification of top counties and cities by EV adoption.  

### 3. Electric Vehicle Types  
- Distribution of EVs by type (e.g., BEV, PHEV).  
- Visualization of the proportion of different EV types.  

### 4. Popular Makes and Models  
- Analysis of the top EV manufacturers and their most popular models.  
- Insights into the leading players in the EV market.  

### 5. Electric Range Analysis  
- Distribution and trends of electric range over the years.  
- Comparison of average electric ranges by model year and manufacturer.  

### 6. Market Growth Forecasting  
- Use of an exponential growth model to forecast future EV registrations.  
- Visualization of current and forecasted market size trends.

---

## Installation and Usage  

### Prerequisites  
- Python 3.x  
- Required libraries: pandas, matplotlib, seaborn, numpy, scipy  

### Setup  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/praneethsattavaram/ev-market-analysis.git  
   ```  
2. Install the required libraries:  
   ```bash  
   pip install pandas matplotlib seaborn numpy scipy  
   ```  
3. Place the dataset file (`Electric_Vehicle_Population_Data.csv`) in the repository folder.  

### Run the Code  
Execute the script to generate visualizations and analyses:  
```bash  
python ev_analysis.py  
```  

---

## Outputs  

### Visualizations  
1. **EV Adoption Over Time**: Bar plot showing growth in EV registrations by model year.  
2. **Geographical Distribution**: Analysis of EV registrations by counties and cities.  
3. **Electric Vehicle Types**: Bar plot showing the proportion of EV types.  
4. **Popular Manufacturers and Models**: Insights into the most registered makes and models.  
5. **Electric Range Distribution**: Histogram showing the distribution of electric ranges.  
6. **Market Growth Forecast**: Line plot visualizing historical and forecasted EV registrations.  

### Forecasting  
- Estimated EV registrations for the next five years using an exponential growth model.  

---

## License  
This project is licensed under the [MIT License](LICENSE).  

---

## Contributing  
Contributions are welcome! Please fork this repository, make changes, and submit a pull request.  

