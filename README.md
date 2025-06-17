# Hackstreeters
Built an AI Crisis Response System 
# JASPIQ – Judgment and Smart Prediction Intelligence for Urban Crises

Finalist – Aggie Hacks 2025, UC Davis

## Overview

**JASPIQ** is an AI-powered decision support system designed to assist smart cities during complex, cascading disaster events. It provides real-time crisis evaluation, trust scoring, and personalized evacuation planning by fusing multimodal city data through an interpretable, rule-based engine.

> [Watch the Demo] (https://drive.google.com/file/d/1pyMYtmrjpmSHs9cQeR1okU6r8kYHMLFK/view?usp=drive_link)



## Problem Statement

Modern cities face crises that don’t occur in isolation — floods, blackouts, misinformation, and infrastructure failures often occur simultaneously and amplify one another. Existing systems are:
- Siloed across departments
- Lack real-time, trustworthy decision support
- Do not model cascading risk chains
- Fail to personalize evacuation or prioritize facility access

JASPIQ was built to address these gaps.

---

## System Components

### 1. **Crisis Intelligence Pipeline**
- Ingests data from sensors, weather logs, economic activity, infrastructure maps, and city event calendars
- Aligns all inputs hourly for real-time relevance
- Performs risk scoring using rule-based logic

### 2. **Risk Engine & Trust Score**
Interpretable risk classification using:
- Flood sensor > 0.8  
- Rainfall > 20mm  
- Energy consumption drop > 40%  
- Economic anomaly (7-day rolling average)  

Scores:
- **High Risk**: 3–4 triggers  
- **Medium**: 2 triggers  
- **Low**: 1 trigger  
- **Unlikely**: 0 triggers

### 3. **Weather-Aware Evacuation Planner**
- Geolocation + timestamp used to compute personalized evacuation advice
- Maps safe facilities based on geodesic proximity
- Highlights weather risks (wind, rainfall, temp) even in the absence of sensor alerts

### 4. **Streamlit Dashboard Interface**
- Interactive UI for citizens or officials to input zone, time, and location
- Live-rendered map with:
  - Trust Score
  - Evacuation zones
  - Facility access
  - Transport options
  - Cascading risk warnings

---

##Technologies Used

- **Python** (Pandas, NumPy, GeoPandas)
- **Streamlit** – UI & dashboard rendering
- **Folium** – Live map visualizations
- **GeoJSON** – Zone infrastructure modeling
- **CSV data parsing** for timestamp-aligned analysis

---

## Impact

Interpretable & transparent  
Real-time city-wide risk prediction  
Personalized evacuation & facility access  
Designed for scalability to multi-zone or full-city deployment

---

## Future Enhancements

- Integration with live social media signals and CCTV feeds  
- Real-time citizen reporting and feedback loop  
- Emergency dispatch system API integration  
- Expansion to simulate multi-zone crises in real time


## Team Hackstreeters

- **Sonia Kashyap** – Team Lead  
- **Jihyun Seo** – Technical Head  
- **Pooja Kumari** – Functional Head  


## Demo

> **Watch JASPIQ in Action**  
> [Click here to view the demo](https://drive.google.com/file/d/1pyMYtmrjpmSHs9cQeR1okU6r8kYHMLFK/view?usp=drive_link)

## License

This project was built for educational and hackathon purposes under the Aggie Hacks 2025 rules. For reuse or contributions, please contact the team directly.

---
