# Recommended Mechanical Engineering Projects Under $200

These projects are prioritized for entry-level **MEP/HVAC, energy engineering, commissioning, BAS/BMS, field engineering, and building-performance** roles.

## Priority Ranking

| Rank | Project | Est. Budget | Career value | Best target roles |
|---:|---|---:|---|---|
| 1 | Smart HVAC / Room Commissioning Data Logger | $55–$120 | Very high | Commissioning, BAS/BMS, energy, HVAC |
| 2 | Residential Heating & Cooling Load Calculation + Equipment Selection | $0–$40 | Very high | MEP/HVAC design, application engineering |
| 3 | Mini Duct-System Test Rig + Fan Curve | $90–$180 | Very high | HVAC design, TAB, commissioning, field engineering |
| 4 | BAS Sequence-of-Operations Simulator | $0–$60 | High | Controls, BAS/BMS, commissioning |
| 5 | Pump Curve / Hydronic Test Bench | $100–$190 | High | MEP, hydronics, commissioning, field engineering |
| 6 | Building Energy Audit + ECM Financial Model | $20–$100 | High | Energy engineer, auditor, RCx |
| 7 | Heat-Pump Performance Dashboard from Public Data | $0–$30 | High | Energy modeling, application engineering |
| 8 | Thermal Comfort / Envelope Investigation | $50–$160 | Medium-high | Building science, energy audits, commissioning |

---

## 1. Smart HVAC / Room Commissioning Data Logger

**Estimated cost:** $55–$120

Build a small monitoring kit that measures room temperature, relative humidity, supply/return or radiator temperatures, and optionally airflow or CO₂. Log readings over time and create plots that show how the space responds to heating/cooling operation.

### Suggested Hardware
- ESP32 or Arduino-compatible board: ~$10–$20
- 2–4 digital temperature sensors: ~$10–$25
- Temperature/RH sensor: ~$5–$15
- microSD module or Wi-Fi logging: ~$5–$15
- Breadboard, wires, enclosure, power supply: ~$15–$30
- Optional differential-pressure or CO₂ sensor: ~$20–$60

### Deliverables
- Wiring diagram
- Sensor calibration check
- CSV data logger
- Python/MATLAB plots
- Trend analysis
- Short functional-test procedure
- Findings and corrective recommendations

### Why This Is #1
It gives you a miniature version of what commissioning and BAS engineers do: **trend data, sensors, sequences, functional testing, diagnosis, and reporting**.

### Resume Bullet
Designed and built an ESP32-based HVAC commissioning data logger to trend temperature and humidity, analyzed system response in Python/MATLAB, and documented functional-test results and performance issues.

---

## 2. Residential Heating & Cooling Load Calculation + Equipment Selection

**Estimated cost:** $0–$40

Create a room-by-room heating/cooling load model for a real house or apartment using public/manual measurements. Do the calculations in Excel or Python and select a heat pump using manufacturer performance data.

### Include
- Floor plan and orientation
- Wall/window/roof areas
- Assumed R/U-values
- Outdoor/indoor design conditions
- Transmission loads
- Infiltration/ventilation loads
- Internal gains
- Sensible + latent cooling
- Room-by-room totals
- Heat-pump selection
- Comparison of calculated load vs. rule-of-thumb sizing

### Stretch Goal
Use a free tool such as CoolCalc trial/free access where available, EnergyPlus/OpenStudio, or an educational load-calculation spreadsheet to compare results.

### Resume Bullet
Performed room-by-room residential heating and cooling load calculations, evaluated envelope and infiltration loads, and selected heat-pump capacity using manufacturer performance data and design conditions.

---

## 3. Mini Duct-System Test Rig + Fan Curve

**Estimated cost:** $90–$180

Build a tabletop duct system with a small inline fan, flexible or rigid duct, dampers/restrictions, and pressure taps. Measure pressure drop and airflow at different operating points.

### Suggested Hardware
- 4-in inline duct fan: ~$30–$50
- 4-in duct/fittings: ~$25–$45
- Low-range digital manometer: ~$25–$45
- Anemometer: ~$20–$40
- Dampers / homemade restrictions / tubing: ~$10–$20

### Experiments
- Fan speed vs. airflow
- Static pressure vs. airflow
- Pressure drop across fittings
- Effect of a dirty-filter simulation
- Series/parallel resistance concept
- Estimated system curve vs. measured operating point

### Deliverables
- CAD layout
- Test procedure
- Raw data
- Fan/system curves
- Uncertainty discussion
- Commissioning-style report

### Resume Bullet
Designed and tested a tabletop duct system, measured airflow and static pressure under multiple resistance conditions, and developed fan/system curves to evaluate operating-point and pressure-drop behavior.

---

## 4. BAS Sequence-of-Operations Simulator

**Estimated cost:** $0–$60

Create a small BAS-style control sequence using Python, Node-RED, MATLAB/Simulink, or an ESP32. Simulate an AHU, fan-coil unit, or hydronic loop with occupancy, temperature setpoints, alarms, and safeties.

### Example Sequence
- Occupied/unoccupied modes
- Heating/cooling deadband
- Fan enable
- Valve/damper modulation
- High/low temperature alarm
- Sensor-failure alarm
- Freeze protection
- Trend logs

### Best Version
Use an ESP32 with LEDs/relays as mock outputs and sensors/potentiometers as inputs. Create a simple dashboard.

### Resume Bullet
Developed and tested a BAS-style HVAC sequence of operations with occupancy modes, temperature control, safeties, alarms, and trend logging using a simulated control system.

---

## 5. Pump Curve / Hydronic Test Bench

**Estimated cost:** $100–$190

Build a closed-loop water test rig with a small pump, clear tubing, valves, pressure measurement, and a flow meter. Measure flow and pressure at different valve positions.

### Experiments
- Pump head vs. flow
- Valve throttling
- System resistance curve
- Series resistance
- Estimated pump power
- Basic NPSH/cavitation discussion (theory only unless safely observable)

### Resume Bullet
Built a small closed-loop hydronic test bench and measured pump head, flow, and system resistance across multiple valve positions to compare experimental pump/system curves.

---

## 6. Building Energy Audit + ECM Financial Model

**Estimated cost:** $20–$100

Audit your home, a relative's home, or another space where you have permission. Use a plug-load meter, IR thermometer, humidity meter, utility bills, and field measurements.

### Include
- Building description
- Utility baseline and EUI
- Envelope observations
- Lighting and plug loads
- Heating/cooling equipment inventory
- Domestic hot-water estimate
- 5+ Energy Conservation Measures
- Annual kWh/therm savings
- Cost savings
- Simple payback
- CO₂ reduction
- Ranked recommendation list

### Resume Bullet
Conducted a residential energy audit using field measurements and utility data, modeled energy-conservation measures, and quantified annual energy, cost, carbon savings, and simple payback.

---

## 7. Heat-Pump Performance Dashboard

**Estimated cost:** $0–$30

Use public manufacturer performance tables or NEEP cold-climate heat-pump data to analyze how capacity and COP change with outdoor temperature.

### Deliverables
- Data cleaning script
- COP vs. outdoor temperature
- Heating capacity vs. temperature
- Balance-point estimate
- Annual operating-cost comparison vs. electric resistance / gas under stated assumptions
- Equipment-selection discussion

### Resume Bullet
Analyzed heat-pump performance data across outdoor temperatures, modeled COP/capacity degradation and balance point, and compared annual operating cost under multiple heating scenarios.

---

## 8. Thermal Comfort / Envelope Investigation

**Estimated cost:** $50–$160

Use inexpensive temperature/RH sensors and an IR thermometer to investigate comfort and envelope performance in multiple rooms.

### Test
- Temperature stratification
- Exterior wall vs. interior wall surface temperature
- Window surface temperatures
- Relative humidity by room/floor
- Heating recovery after setback
- Possible air-leakage locations using safe qualitative methods

### Important
Do not disturb suspect mold, asbestos, lead paint, or unknown building materials. Keep the project to non-invasive measurement unless a qualified professional has cleared the area.

### Resume Bullet
Performed a multi-room thermal comfort and envelope investigation using temperature, humidity, and surface-temperature measurements to identify performance differences and recommend energy-efficiency improvements.

---

# Best 3-Project Sequence

If the goal is the strongest portfolio with minimum spending, complete these in order:

1. **HVAC Commissioning Data Logger** — proves sensors, trend analysis, controls thinking, and field testing.
2. **Heating/Cooling Load Calculation** — proves MEP design fundamentals and equipment selection.
3. **Mini Duct Test Rig** — proves hands-on HVAC measurements, airflow/static pressure, and engineering experimentation.

Together, those three cover the biggest gaps between your current resume and entry-level HVAC / commissioning / BAS roles.
