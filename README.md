# Industrial Water Pump Monitoring System


A real-time data engineering project that simulates an industrial centrifugal water pump, generates realistic time-series sensor data, and processes the data through a monitoring pipeline.

The project uses a state-based stochastic simulation with simplified pump equations to model changing operating conditions. Sensor data is then processed, stored, analysed, and visualised to monitor pump performance and identify abnormal behaviour.

---

## Project Overview

Industrial equipment produces continuous streams of sensor data that can be used to monitor performance, detect faults, and support maintenance decisions.

This project simulates an industrial water pump and generates sensor readings including:

- Pressure
- Flow rate
- Temperature
- Vibration
- RPM
- Power consumption
- Pump operating status

The generated data is processed through a data engineering pipeline before being stored and analysed.

---

## Project Architecture

```text
Pump Simulator
      ↓
Apache Kafka
      ↓
Python Consumer / ETL
      ↓
PostgreSQL
      ↓
FastAPI         -> (subject to change)
      ↓
React Dashboard -> (subject to change)
```

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | |
| Pandas | |
| Apache Kafka | |
| PostgreSQL | |
| SQL | |
| Streamlit | |
| Plotly | |
| Docker | |
| Git / GitHub | |

---

## Water Pump Simulation



### Simulation Approach



### Simulation Inputs

- 
- 
- 
- 

### Simulation Outputs

- 
- 
- 
- 
- 
- 

---

## Pump Model



### Pump Curve



### System Curve



### Pressure Calculation



### Flow Rate Calculation



### Power Calculation



### Temperature Model



### Vibration Model



---

## State-Based Simulation



### Time Steps



### Stochastic Behaviour



### Mean Reversion



---

## Sensor Simulation



### Sensor Noise



### Sensor Data Fields

| Field | Description | Unit |
|---|---|---|
| timestamp | | |
| pump_id | | |
| inlet_pressure | | |
| outlet_pressure | | |
| flow_rate | | |
| temperature | | |
| vibration | | |
| rpm | | |
| power_consumption | | |
| status | | |

---

## Fault Simulation



### Bearing Degradation



### Restricted Flow / Blockage



### Overheating



### Reduced Pump Efficiency



### Sensor Faults



---

## Data Pipeline



### Extract



### Transform



### Load



---

## Apache Kafka



### Kafka Producer



### Kafka Consumer



### Kafka Topics



---

## Data Validation

- 
- 
- 
- 
- 

---

## PostgreSQL Database



### Database Schema



### Sensor Readings Table



### Fault Events Table



### Pump Metrics Table



---

## SQL Analysis



### Example Metrics

- 
- 
- 
- 
- 
- 

### Example Queries

```sql

```

---

## Data Analysis



### Pressure Analysis



### Flow Rate Analysis



### Temperature Analysis



### Vibration Analysis



### Power Consumption Analysis



### Fault Analysis



---

## Streamlit Dashboard



### Live Pump Status



### KPI Metrics

- 
- 
- 
- 
- 

### Historical Trends



### Fault Monitoring



---

## Dashboard Screenshots



---

## Exploratory Data Analysis



### Key Findings

- 
- 
- 
- 

---

## Testing



### Pump Model Tests



### Sensor Model Tests



### ETL Tests



---

## Docker



---

## Project Structure

```text
Industrial-Water-Pump-Monitoring-System/
│
├── dashboard/
│   └── app.py
│
├── data/
│   ├── raw/
│   └── processed/
│
├── docker/
│   └── docker-compose.yml
│
├── notebooks/
│   └── exploratory_analysis.ipynb
│
├── sql/
│   ├── analysis_queries.sql
│   └── schema.sql
│
├── src/
│   ├── analytics/
│   │   ├── __init__.py
│   │   ├── fault_analysis.py
│   │   └── metrics.py
│   │
│   ├── pipeline/
│   │   ├── __init__.py
│   │   ├── consumer.py
│   │   ├── database.py
│   │   ├── producer.py
│   │   └── transform.py
│   │
│   └── simulation/
│       ├── __init__.py
│       ├── pump_model.py
│       ├── pump_simulator.py
│       ├── sensor_model.py
│       └── fault_model.py
│
├── tests/
│   ├── test_pump_model.py
│   ├── test_sensor_model.py
│   └── test_transform.py
│
├── README.md
├── requirements.txt
├── .gitignore
└── .env.example
```

---

## Installation

```bash

```

---

## Running the Project

### Run the Pump Simulator

```bash

```

### Start Kafka

```bash

```

### Start PostgreSQL

```bash

```

### Run the Kafka Consumer

```bash

```

### Run the Streamlit Dashboard

```bash

```

---

## Results



---

## Challenges

### Challenge 1



### Challenge 2



### Challenge 3



---

## What I Learned

- 
- 
- 
- 
- 

---

## Limitations



---

## Future Improvements

- 
- 
- 
- 
- 

---

## Project Status

- [x] Initial project structure
- [ ] Pump physics model
- [ ] State-based stochastic simulation
- [ ] Sensor simulation
- [ ] Raw data generation
- [ ] Fault simulation
- [ ] ETL pipeline
- [ ] PostgreSQL database
- [ ] Apache Kafka streaming
- [ ] SQL analysis
- [ ] Streamlit dashboard
- [ ] Testing
- [ ] Docker deployment

---

## Author

**Jevhan Seechurn**

GitHub:  
LinkedIn:  
Portfolio:
=======
