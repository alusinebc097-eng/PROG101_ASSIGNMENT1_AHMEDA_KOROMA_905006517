# Freetown Flash Flood Alert Network (F3-Alert)

## 1. Overview

The Freetown Flash Flood Alert Network (F3-Alert) is a proposed technology-based system designed to monitor rising water levels and heavy rainfall in flood-prone communities in Freetown, Sierra Leone. The main purpose of the system is to provide early warnings to residents, emergency responders, and relevant authorities before flooding becomes dangerous. The system will use water-level sensors and rainfall sensors to collect environmental information and analyse it to determine the level of flood risk in a particular area.

The system will classify flood conditions into three main categories: Normal, Alert, and Critical Evacuation. When the water level or rainfall reaches a specified threshold, the system will activate warning mechanisms such as sirens and SMS notifications. It will also record sensor readings and generate reports that can help authorities understand changing flood conditions. The proposed system is intended as a prototype for educational and planning purposes and would require proper testing before real-world deployment.

## 2. Rationale

Flooding is a serious environmental challenge that affects many communities in Freetown, especially during periods of heavy rainfall. Residents in low-lying and coastal settlements may experience flooding that damages houses, destroys personal belongings, interrupts businesses, and creates dangerous living conditions. Without timely information, people may not have enough time to protect their property or move to safer locations. This project is therefore important because it explores how computer programming and sensor technology can support disaster preparedness.

The rationale for developing F3-Alert is to demonstrate how an automated warning system can improve the speed and organisation of flood monitoring. Instead of depending entirely on people observing rising water levels, sensors can collect readings at regular intervals and allow the program to analyse them automatically. The system could help residents receive warnings earlier and help emergency teams identify areas that may require attention. However, its effectiveness would depend on reliable sensors, communication networks, accurate thresholds, and cooperation with authorised disaster-management organisations.

## 3. Problem Description

Freetown experiences flooding during periods of intense rainfall, with some communities particularly exposed because of their location, drainage conditions, and settlement patterns. Floodwater can enter homes, cover roads, damage small businesses, and make movement difficult. In some areas, blocked drainage channels and poor waste management can make the situation worse by preventing rainwater from flowing away properly. These conditions create risks for people, property, public health, and local economic activities.

One major problem is that residents may not receive warnings early enough to prepare for rapidly changing conditions. Manual observation can be inconsistent, especially when rainfall occurs at night or when water levels rise quickly. F3-Alert proposes an automated monitoring process that collects water-level and rainfall information, evaluates the readings, and produces a warning when the programmed conditions indicate danger. The system is intended to reduce delays in communicating risk, rather than replace official weather forecasts or emergency instructions.

## 4. Background

Flood risk in Freetown is influenced by several environmental and human factors. These include heavy rainfall, low-lying land, coastal exposure, changing land use, settlement expansion, and drainage challenges. The World Bank's Freetown City Hazard and Risk Assessment examines flood and other natural hazards affecting the city and provides information to support disaster-risk planning. Research has also examined the relationship between rainfall, elevation, drainage density, land cover, and flood vulnerability in Freetown. These studies demonstrate why flood monitoring and preparedness are important issues for the city. 

The development of F3-Alert is based on the idea that digital technology can support existing disaster-risk management activities. Sensors can measure environmental conditions, while a computer program can process the information and identify when readings meet predefined warning conditions. The proposed system would be most useful when connected to a wider emergency communication and response plan. Its readings should be checked against local environmental data, and its warning procedures should be reviewed by technical experts and the relevant authorities before public use.

## 5. Community Impact and Beneficiaries

The proposed system could benefit residents living in flood-prone communities such as Kroo Bay, Susan's Bay, and Lumley. These communities are examples of areas where monitoring and timely warnings may be valuable. If the system detects a dangerous rise in water levels, it could communicate warnings that give residents more time to prepare, protect important belongings, and follow official evacuation instructions. Early information may also help reduce confusion during emergencies.

Other beneficiaries could include local councils, disaster-management organisations, emergency responders, health workers, schools, business owners, and community leaders. Authorities could use the system's records to identify periods of rising water, compare readings, and plan responses. Schools and businesses could use verified alerts to make decisions about safety and temporary closure. However, the system must be accessible to people who do not own smartphones, so warning sirens, community announcements, and other communication methods should complement SMS notifications.

## 6. Proposed Solutions

The proposed solution is to develop a sensor-based flood monitoring system that continuously collects water-level and rainfall information. Ultrasonic water-level sensors would measure the distance between the sensor and the water surface, while rainfall sensors would measure the intensity of rainfall. The collected readings would be transmitted to a computer system for validation and analysis. The system would check the readings at regular intervals, proposed in this prototype as every 60 seconds.

After processing the readings, the system would assign a risk category and activate the appropriate response. Normal conditions would be recorded without issuing a flood warning. Alert conditions would trigger a warning message, while Critical conditions would activate an urgent evacuation warning and notify designated emergency personnel. The system would also store information about sensor readings, dates, times, locations, and warning levels so that reports can be generated for monitoring and future planning.

## 7. Computational Thinking Process

Computational thinking is the process of solving problems by organising information and developing logical steps that a computer can follow. In this project, **decomposition** is used to divide the larger flood-monitoring problem into smaller tasks. These tasks include collecting sensor readings, validating data, evaluating flood risk, classifying the risk, sending warnings, recording information, and producing reports. Dividing the system into smaller parts makes the design easier to understand, develop, test, and maintain.

**Pattern recognition** is used to identify relationships between rainfall intensity, water levels, and possible flood conditions. **Abstraction** allows the programmer to focus on the most important information needed for the decision-making process, such as water level, rainfall intensity, location, and time. **Algorithm design** is used to create a sequence of instructions that determines how the system should operate. Together, these computational thinking techniques help transform a real-world environmental problem into a structured programming solution.

## 8. Algorithm Design

An algorithm is a step-by-step set of instructions used to solve a problem. The F3-Alert algorithm begins by starting the monitoring system and reading the information received from the water-level and rainfall sensors. The system then checks whether the readings are available and valid. If a sensor reading is missing or outside its permitted range, the system records a sensor fault and informs the operator instead of incorrectly classifying the situation as Normal.

If the readings are valid, the system compares them with the programmed thresholds. A water level of 2.5 metres or above is classified as Critical. If the water level is at least 1.8 metres or rainfall intensity is at least 45 millimetres per hour, the condition is classified as Alert, provided the Critical condition has not already been met. Otherwise, the condition is classified as Normal. The system records the result, performs the appropriate notification action, and repeats the monitoring process after the specified interval.

**Algorithm inputs:**
- Water level in metres.
- Rainfall intensity in millimetres per hour.
- Sensor identification number.
- Location of the sensor.
- Date and time of the reading.

**Algorithm processing:**
- Collect readings.
- Validate readings.
- Compare readings with thresholds.
- Determine the risk category.
- Select the appropriate response.

**Algorithm outputs:**
- Normal, Alert, or Critical Evacuation status.
- Warning messages and siren activation where configured.
- Operator notifications.
- Recorded readings and system reports.

## 9. SDG Alignment

The project supports **Sustainable Development Goal 11 (SDG 11): Sustainable Cities and Communities**. This goal focuses on making cities and human settlements inclusive, safe, resilient, and sustainable. F3-Alert contributes to this objective by exploring how technology can improve flood preparedness and provide communities with earlier information about possible danger. A reliable warning system could support safer decision-making and help local authorities identify areas that need attention.

The project also supports **Sustainable Development Goal 13 (SDG 13): Climate Action**, which focuses on taking urgent action to address climate change and its impacts. Flood monitoring is one way of improving preparedness for climate-related hazards. By collecting environmental information and communicating possible risks, F3-Alert could support local adaptation and disaster-risk reduction activities. The project does not directly prevent climate change or flooding, but it demonstrates how digital systems can help communities prepare for environmental threats.

## 10. Open Source Justification

Open-source software makes its source code available under a licence that permits users to inspect, use, modify, and redistribute it according to the licence conditions. Using an open-source approach for F3-Alert would allow students, programmers, researchers, and relevant organisations to examine how the system works. They could identify errors, suggest improvements, adapt the program to different communities, and contribute additional features.

Open-source development can also reduce dependence on expensive proprietary software licences and encourage collaboration between developers. A project repository on GitHub could contain the source code, documentation, installation instructions, and examples of system operation. However, open-source software does not mean that the entire project is free to operate. Sensors, computers, internet access, SMS services, maintenance, and staff training may still involve costs. The project should therefore use a suitable open-source licence and provide clear documentation.

## 11. Digital Public Goods (DPGs)

Digital Public Goods are digital resources that can support public benefit and sustainable development. They may include open-source software, open data, open standards, and other digital resources that meet recognised requirements. F3-Alert has the potential to contribute to public benefit because its proposed purpose is to support flood preparedness, community safety, and disaster-risk information sharing. Its design could be made available for educational use and further development by other communities.

However, an open-source project does not automatically qualify as an officially recognised Digital Public Good. It would need to meet the relevant Digital Public Goods Standard and other applicable requirements. These include appropriate licensing, clear ownership, documentation, privacy protection, security, and measures to prevent harm. If the system collects residents' telephone numbers or other personal information, those details must be protected and only the minimum necessary information should be collected. The project should be described as having potential to support digital public good objectives, not as an officially recognised DPG unless it has completed the required assessment.

## 12. System Modules

The F3-Alert system will be divided into modules so that each part performs a specific task. The **Main System Module** controls the overall operation of the program. The **Sensor Data Collection Module** receives readings from the water-level and rainfall sensors, while the **Data Validation Module** checks whether the readings are complete and within acceptable ranges. The **Evaluate Risk Module** compares the readings with the predefined thresholds and determines the appropriate risk level.

The remaining modules handle the system's response and record-keeping activities. The **Risk Classification Module** assigns the Normal, Alert, or Critical category. The **Notification Module** sends messages or activates warning devices according to the classification. The **Reporting Module** stores readings and generates daily, weekly, or monthly reports. A separate operator-notification function informs the responsible person when a sensor fault or communication problem is detected. Dividing the system into these modules makes it easier to test and update individual functions.

**Main modules:**
1. MainSystem
2. ReadSensorData
3. ValidateReadings
4. EvaluateRisk
5. RiskClassification
6. ExecuteResponseActions
7. LogAssessment
8. GenerateSystemReport
9. NotifyOperator

## 13. Pseudocode

Pseudocode is a simple way of describing the logic of a program without using the exact syntax of a programming language. It helps the programmer understand the sequence of instructions before writing the actual code. In F3-Alert, pseudocode describes how sensor readings are collected, checked, evaluated, classified, and recorded. It also shows how the program repeats the monitoring process at regular intervals.

The pseudocode uses sequence, selection, and iteration. Sequence means that instructions are performed in order. Selection means that the system chooses an action based on conditions, such as whether the water level has reached a warning threshold. Iteration means that the monitoring process repeats continuously while the system is running. These three programming structures form the foundation of the proposed system.

**Pseudocode:**

```text
BEGIN

    SET ALERT_WATER_THRESHOLD = 1.8
    SET CRITICAL_WATER_THRESHOLD = 2.5
    SET HEAVY_RAIN_THRESHOLD = 45.0
    SET MONITORING_INTERVAL = 60

    WHILE system_is_running

        READ water_level
        READ rainfall_intensity
        READ sensor_ID
        READ timestamp

        IF readings_are_missing_or_invalid THEN
            RECORD "SENSOR FAULT"
            NOTIFY operator
        ELSE
            risk_status = EvaluateRisk(
                water_level,
                rainfall_intensity
            )

            RECORD readings and risk_status

            IF risk_status = "CRITICAL" THEN
                ACTIVATE emergency warning
                SEND urgent notification
            ELSE IF risk_status = "ALERT" THEN
                ACTIVATE warning
                SEND alert notification
            ELSE
                RECORD "NORMAL"
            END IF
        END IF

        WAIT MONITORING_INTERVAL seconds

    END WHILE

END
```

## 14. Main System Module

The Main System Module is responsible for controlling the complete operation of F3-Alert. It starts the program, loads the system thresholds, collects information from the sensors, and sends the readings to the validation and risk-evaluation functions. It also ensures that the monitoring process continues until an authorised operator stops the system. This module connects the different parts of the program and ensures that they work together in the correct order.

The module must also handle errors that may occur during sensor communication. If a reading is unavailable or invalid, the system should record the problem and notify the operator. It should not assume that missing sensor information means there is no flood risk. The following Python example demonstrates the main control structure using simulated sensor readings; a real installation would require suitable hardware and communication interfaces.

**Python example:**

```python
import time
from datetime import datetime

ALERT_WATER_THRESHOLD = 1.8
CRITICAL_WATER_THRESHOLD = 2.5
HEAVY_RAIN_THRESHOLD = 45.0
MONITORING_INTERVAL = 60


def read_sensor_data():
    # Demonstration values.
    # Replace these with actual sensor readings.
    water_level = 1.9
    rainfall_intensity = 30.0

    return water_level, rainfall_intensity


def main_system():
    print("F3-Alert Flood Monitoring System Started")

    while True:
        water_level, rainfall = read_sensor_data()
        timestamp = datetime.now()

        if water_level is None or rainfall is None:
            print("SENSOR FAULT: Operator notification required.")
        else:
            status = evaluate_risk(water_level, rainfall)

            print("Time:", timestamp)
            print("Water Level:", water_level, "metres")
            print("Rainfall:", rainfall, "mm/hr")
            print("Risk Status:", status)

        time.sleep(MONITORING_INTERVAL)


if __name__ == "__main__":
    main_system()
```

## 15. Evaluate Risk Function

The Evaluate Risk Function is responsible for analysing the information collected from the sensors. It receives the water-level reading and rainfall intensity as inputs and compares them with the programmed thresholds. The function first checks whether the water level has reached the Critical threshold. This condition is checked before the Alert condition because a critical water level must receive the highest priority, even if other readings also meet lower-level warning conditions.

If the Critical condition is not met, the function checks whether the water level has reached 1.8 metres or rainfall intensity has reached 45 millimetres per hour. If either condition is true, the function returns Alert. If neither condition is true, it returns Normal. These values are proposed prototype settings for demonstrating programming logic; they are not validated public-safety thresholds and must be calibrated using local hydrological evidence and expert assessment before any operational use.

**Python example:**

```python
def evaluate_risk(water_level, rainfall_intensity):

    if water_level >= CRITICAL_WATER_THRESHOLD:
        return "CRITICAL"

    elif (
        water_level >= ALERT_WATER_THRESHOLD
        or rainfall_intensity >= HEAVY_RAIN_THRESHOLD
    ):
        return "ALERT"

    else:
        return "NORMAL"
```

## 16. Risk Classification

Risk classification is the process of grouping sensor readings into categories that describe the current flood condition. F3-Alert uses three main categories: Normal, Alert, and Critical Evacuation. The Normal category indicates that the readings are below the programmed warning thresholds. The Alert category indicates that at least one warning threshold has been reached and that residents and operators should pay attention to the situation. The Critical category indicates that the water level has reached the highest prototype threshold and requires urgent action under the approved emergency plan.

The classification process helps the system choose an appropriate response instead of sending the same message for every reading. It also makes the information easier for operators and community members to understand. The thresholds must be reviewed for each monitoring location because water conditions, sensor positions, drainage systems, and local terrain can differ. The prototype should never be used as the sole basis for evacuation decisions until its performance has been tested and approved by the responsible authorities.

| Risk Category | Prototype Condition | Suggested System Response |
|---|---|---|
| Normal | Water level below 1.8m and rainfall below 45mm/hr | Record readings and continue monitoring |
| Alert | Water level at least 1.8m but below 2.5m, or rainfall at least 45mm/hr | Send warning notification and alert operator |
| Critical Evacuation | Water level at least 2.5m | Activate urgent warning and notify emergency responders |
| Sensor Fault | Missing, invalid, or out-of-range reading | Record fault and notify operator |

**Important:** A sensor fault is an operational warning, not a Normal flood-risk classification. The system must make the operator aware that reliable information is unavailable.

## 17. Report Procedures

The Reporting Module collects and organises information generated during the monitoring process. Each record should include the sensor identification number, monitoring location, date, time, water-level reading, rainfall intensity, and assigned risk category. These records can be stored in a database or structured file for later examination. Keeping accurate records will help operators identify patterns and review how the system responded during different rainfall conditions.

The system can generate daily, weekly, and monthly reports. Daily reports can show the readings and warning events recorded during a particular day. Weekly reports can help identify repeated increases in water levels, while monthly reports can provide a broader view of monitoring activity. Reports may also identify sensor faults, communication failures, and the number of warnings issued. Personal information, including residents' telephone numbers, should not be included in general reports unless it is necessary and properly protected.

**Example reporting procedure:**

```text
PROCEDURE GenerateSystemReport

    OPEN monitoring records

    SELECT readings for requested period

    FOR each reading
        DISPLAY date and time
        DISPLAY sensor ID
        DISPLAY location
        DISPLAY water level
        DISPLAY rainfall intensity
        DISPLAY risk category
    END FOR

    COUNT Normal readings
    COUNT Alert readings
    COUNT Critical readings
    COUNT Sensor faults

    GENERATE report summary

    SAVE report

END PROCEDURE
```
6. <img width="1366" height="768" alt="flow 001" src="https://github.com/user-attachments/assets/9850a50f-9e36-4777-bee4-e3ecfb631f85" />
<img width="1366" height="768" alt="flow 002" src="https://github.com/user-attachments/assets/4020a27a-434e-45e8-b1ea-5182e0187ca5" />
<img width="1366" height="768" alt="flow 003" src="https://github.com/user-attachments/assets/760c31dd-a865-4e13-99fa-6284edf5005c" />
<img width="1366" height="768" alt="flow 004" src="https://github.com/user-attachments/assets/721157d0-29b5-4433-90a6-0378908bb0e1" />

## Prepared by

Ahmeda Koroma
Student ID: 905006517
