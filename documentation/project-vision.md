# Project Vision



## Industrial Water Pump Monitoring System
<br>

### 1. Vision Statement

---

The vision of this project is to design and develop a realistic industrial water pump monitoring system that will simulate pump behaviour, as well as generating continuous sensor data to be used for analysis.

The system will function via a state-based stochastic simulation and simplified pump equations in order to model values such as pressure, flow rate, temperature, vibration, RPM and power consumption. 

The project will then implement an ETL system that will extract, process and load the data in order to analyse pump performance and potential abnormalities that can be monitored continuously.


<br>


### 2. Problem Statement

---

Industrial water pumps are widely used across a large range of systems in order to move and circulate water where reliable flow and pressure are necessary. They play an important role for water distribution, cooling systems, manufacturing processes, wastewater treatment, fire suppression systems and power generation facilities. On a smaller scale, an all-in-one (AIO) which is used in PCs can continuously circualte coolant between the CPU and radiator in order to remove heat from the processor.

The **problem** is that industrial pumps can operate continuously for long periods of time without break, making it difficult to manually monitory their conditions at all times. The changes in pressure, flow rate, temperature, vibration or power consumption may indicate reduced efficiency, component degradation or a developing fault.

If these changes are not found in an earlier stage, faults can start to further progress into a more critical or even potentially catastrophic faliures, which can result in equipment damage, unplanned downtime, increased maintenance requirements or disruption to wider operations.


<br>


### 3. Project Purpose

---

The purpose of this project is to develop a monitoring system that can collect and analyse simulated water pump sensor data continuously in order to identify fluctuations in pump behaviour.

The system will focus on monitoring key operational values such as pressure, flow rate, temperature, vibration, RPM and power consumption. By analysing these values over time, the project aims to identify abnormal operating conditions and provide earlier indications of potential faults before they develop into more serious failures.

The project will also demonstrate how data engineering techniques can be used to process, store and analyse continuous industrial sensor data.

<br>

### 4. Requirements

#### 4.1 Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | The system must simulate continuous centrifugal pump operation. | Must |
| FR-02 | The system must generate pressure, flow, temperature, vibration, RPM and power data. | Must |
| FR-03 | The system must store historical sensor readings. | Must |
| FR-04 | The system must detect abnormal operating conditions. | Must |
| FR-05 | The system should calculate a pump health score. | Should |
| FR-06 | The system may include an interactive operator simulation mode. | Could |

#### 4.2 Non-Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| NFR-01 | The simulation should generate realistic and consistent sensor behaviour. | Must |
| NFR-02 | The system should support continuous operation without instability. | Must |
| NFR-03 | The code should be modular and maintainable. | Must |
| NFR-04 | The monitoring interface should update with low latency. | Should |
| NFR-05 | The system should be deployable using Docker. | Should |

<br>

## 5. Target Users

- **Maintenance Engineers**
  - Monitor pump condition.
  - Identify abnormal behaviour.
  - Investigate developing faults.
  - Support preventative maintenance.

- **Plant / System Operators**
  - Monitor live pump readings.
  - View pressure, flow rate, temperature, vibration, RPM and power consumption.
  - Respond to warnings or abnormal operating conditions.

- **Reliability Engineers**
  - Analyse historical pump performance.
  - Review anomaly trends and pump health scores.
  - Identify recurring faults or signs of degradation.

- **Data / Monitoring Engineers**
  - Maintain the data pipeline.
  - Ensure sensor data is processed and stored correctly.
  - Support access to reliable historical and real-time data.

- **Engineering Students / Simulation Users**
  - Explore how pump behaviour changes under different operating conditions.
  - Learn how sensor data can indicate developing faults.

- **Interactive Operator Mode Users**
  - Control the pump during simulated scenarios.
  - Respond to anomalies and faults.
  - Compare their performance against automated or AI-assisted monitoring.

<br>

### 6. User Needs

---

- View live pump operating conditions in real time.
- Monitor pressure, flow rate, temperature, vibration, RPM and power consumption.
- Quickly identify abnormal or unsafe operating conditions.
- Receive clear warnings when potential faults are detected.
- View an overall pump health score.
- Review pump health over different time periods.
- Analyse historical sensor data and operating trends.
- Investigate previous anomalies and fault events.
- Understand which sensor readings contributed to a warning or anomaly.
- Compare current pump behaviour against normal operating conditions.
- Access clear and easy-to-understand charts and visual indicators.
- Monitor the system without needing to manually inspect every individual sensor reading.
- View the current operating state of the pump, such as normal, warning or critical.
- Support maintenance decisions using historical and real-time data.
- If interactive mode is implemented, control selected pump settings and respond to simulated faults.
- If AI monitoring is implemented, view AI-detected anomalies and understand why they were flagged.

<br>

### 7. High-Level System Flow

```text

Pump Simulation
      ↓

Sensor Data
      ↓

Data Ingestion
      ↓

Data Processing / ETL
      ↓

Database
      ↓

Data Analysis
      ↓

Monitoring Interface
