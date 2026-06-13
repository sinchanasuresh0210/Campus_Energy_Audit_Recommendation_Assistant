# ⚡ Campus Energy Audit Recommendation Assistant

An AI-powered Campus Energy Audit Recommendation Assistant developed using **Langflow** and **Google Gemini 2.5 Flash**. The system analyzes energy consumption data from classrooms and laboratories, identifies potential energy wastage patterns, and provides actionable recommendations to improve energy efficiency on campus.

---

## 📌 Project Overview

Educational institutions consume a significant amount of electricity through:

- Air Conditioners (ACs)
- Fans
- Lighting Systems
- Computer Laboratories
- Projectors and Electronic Equipment

Manual energy auditing is often time-consuming and requires expert knowledge. This project leverages Generative AI to assist campus administrators in quickly identifying inefficient energy usage and recommending sustainable energy-saving practices.

---

## 🎯 Objectives

- Analyze energy usage information provided by users.
- Estimate energy consumption based on appliance ratings and operating hours.
- Detect possible energy wastage patterns.
- Recommend practical energy-saving measures.
- Promote sustainability and energy efficiency in educational institutions.

---

## 🚀 Features

### ✅ Energy Consumption Analysis
Calculates approximate electricity usage using:

Energy (kWh) = Power (kW) × Hours × Quantity

### ✅ Wastage Detection
Identifies potential wastage scenarios such as:

- ACs running for extended periods
- Fans operating beyond working hours
- Equipment left ON in unoccupied rooms
- Excessive cooling usage

### ✅ Intelligent Recommendations
Provides campus-specific suggestions including:

- Occupancy sensor installation
- AC temperature optimization
- Scheduled equipment shutdown
- Energy awareness programs

### ✅ Natural Language Interaction
Users can describe energy usage in plain English.

Example:

> "In CSE Lab 1, there are 4 ACs (1.5 kW each) running for 10 hours and 10 Fans (75W each) running for 12 hours."

The assistant analyzes the scenario and generates recommendations.

---

## 🏗️ System Architecture

```text
+----------------+
|   User Input   |
+----------------+
        |
        v
+----------------------+
|   Prompt Template    |
+----------------------+
        |
        v
+----------------------+
| Google Gemini 2.5 AI |
+----------------------+
        |
        v
+----------------------+
| Energy Analysis      |
| Waste Detection      |
| Recommendations      |
+----------------------+
        |
        v
+----------------------+
|     Chat Output      |
+----------------------+
```

---

## 🔄 Langflow Workflow

```text
Chat Input
     ↓
Prompt Template
     ↓
Google Generative AI
     ↓
Chat Output
```


## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Langflow | Workflow orchestration |
| Google Gemini 2.5 Flash | Large Language Model |
| Prompt Engineering | AI behavior control |
| Python | Development Environment |

---

## 📊 Example Input

```text
In CSE Lab 1, there are 4 ACs (1.5 kW each) running for 10 hours today,
and 10 Fans (75W each) running for 12 hours.
Calculate the total energy consumed in kWh.
```

---

## 📈 Example Output

```text
Total Energy Consumption: 78.0 kWh

Breakdown:
ACs = 60.0 kWh
Fans = 18.0 kWh

WASTAGE PATTERN DETECTED

Possible Issues:
- ACs operating for extended durations.
- Fans running beyond typical classroom usage hours.

Recommendations:
1. Install occupancy sensors.
2. Set AC temperature to 24°C.
3. Schedule automatic shutdown during non-working hours.
```

---

## 📂 Project Structure

```text
Campus-Energy-Audit-Recommendation-Assistant/
│
├── README.md
├── screenshots/
│   ├── workflow.png
│   ├── output1.png
│   └── output2.png
│
├── langflow/
│   └── campus_energy_audit_flow.json
│
└── docs/
    └── project_report.pdf
```

---

## 💡 Use Cases

- College Campus Energy Monitoring
- Classroom Energy Audits
- Laboratory Energy Analysis
- Sustainability Awareness Programs
- Green Campus Initiatives

---

## 🌱 Benefits

- Reduces energy wastage
- Supports sustainable campus operations
- Assists facility management teams
- Encourages responsible energy usage
- Provides quick energy audit recommendations

---

## 🔮 Future Enhancements

### Real-Time Monitoring
Integration with IoT sensors for live energy tracking.

### Smart Dashboard
Visualize energy consumption trends using analytics dashboards.

### Carbon Footprint Analysis
Estimate CO₂ emissions based on electricity usage.

### Renewable Energy Suggestions
Recommend solar and other green energy alternatives.

### Automated Report Generation
Generate downloadable audit reports in PDF format.

---

## 📸 Screenshots

### Workflow

Add your Langflow workflow screenshot here.

### Sample Output

Add screenshots of generated recommendations here.

---

## 👨‍💻 Developed By

**Sinchana Suresh**

Project: Campus Energy Audit Recommendation Assistant

Built using Langflow and Google Gemini 2.5 Flash.

---

