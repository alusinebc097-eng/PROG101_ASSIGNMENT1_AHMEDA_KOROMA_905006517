# PROG101_ASSIGNMENT1_AHMEDA_KOROMA_905006517
Freetown, the capital city of Sierra Leone, experiences intense seasonal rainfall between June and September. Due to rapid urbanization, poor waste management practices blocking drainage channels, and deforestation on hillside slopes, low-lying coastal slum communities face severe and frequent flash flooding. 
# FREETOWN FLASH FLOOD ALERT NETWORK (F3-ALERT)



# 1. OVERVIEW

The Freetown Flash Flood Alert Network (F3-Alert) is a proposed technology-based early warning system designed to monitor rainfall and rising water levels in flood-prone communities in Freetown, Sierra Leone.

The project aims to reduce the risks associated with flash flooding by introducing a monitoring system that collects environmental data, evaluates flood conditions and provides early warnings to residents and emergency responders.

The proposed system uses ultrasonic water-level sensors and rainfall sensors to monitor environmental conditions. It processes the collected information and classifies the flood risk into three categories: Normal, Alert and Critical Evacuation.

When dangerous conditions are detected, the system is designed to activate warning sirens, send SMS notifications and alert relevant emergency response teams.

The project focuses on improving disaster preparedness, protecting human lives and supporting safer communities.

# 2. RATIONALE

Flooding is a recurring environmental challenge in Freetown, particularly during the rainy season. Heavy rainfall, inadequate drainage systems, blocked waterways, deforestation and rapid urbanisation can increase the risk and impact of flooding.

In some vulnerable communities, residents may have limited time to respond when water levels rise rapidly. This can result in loss of lives, destruction of properties, disruption of businesses and damage to public infrastructure.

The rationale for developing F3-Alert is to introduce a technology-based solution that can monitor environmental conditions and provide timely warnings before flooding becomes more dangerous.

The system will help identify increasing flood risks, communicate warnings and support emergency response decisions.

The project is justified by the need to:

- Improve flood monitoring and early warning.
- Reduce the risks of flood-related injuries and deaths.
- Protect homes, businesses and public infrastructure.
- Improve community awareness and preparedness.
- Support disaster management through technology.

# 3. PROBLEM DESCRIPTION

Freetown experiences seasonal flooding that affects several communities, especially areas with low-lying land and inadequate drainage infrastructure.

Some of the major factors contributing to flooding include:

**Poor drainage systems:** Inadequate or damaged drainage channels can prevent rainwater from flowing away effectively.

**Improper waste disposal:** Waste materials dumped into drains can block water channels and contribute to flooding.

**Heavy rainfall:** Intense rainfall can cause water levels to rise rapidly, particularly in areas with limited drainage capacity.

**Rapid urbanisation:** Unplanned development and construction can increase pressure on drainage systems and reduce natural areas where water can be absorbed.

**Deforestation:** The loss of vegetation can increase surface runoff and soil erosion.

The main problem addressed by this project is the lack of a proposed continuous, automated monitoring and warning process that can help vulnerable communities respond to rapidly changing flood conditions.

# 4. BACKGROUND

Freetown is the capital city of Sierra Leone and has communities located in coastal, low-lying and hilly areas. Seasonal rainfall and environmental conditions can create flooding and other disaster risks.

Flooding has affected households, roads, businesses, farmland and public infrastructure in Sierra Leone. The National Disaster Management Agency identifies Freetown among locations exposed to seasonal flooding.

Traditional flood observation may depend on residents or authorities noticing rising water levels and communicating the information manually. This approach may not always provide sufficient warning time.

Advances in technology provide opportunities to improve environmental monitoring. Sensors can collect measurements, computer programs can evaluate the information, and communication systems can distribute alerts.

F3-Alert applies these concepts to a proposed flood early warning system for Freetown. It combines sensor monitoring, decision-making algorithms and notification procedures into one organised system.

# 5. COMMUNITY IMPACT AND BENEFICIARIES

The F3-Alert project is expected to provide benefits to individuals, communities and institutions affected by flooding.

### 5.1 Primary beneficiaries

**Residents of flood-prone communities:** People living in vulnerable areas can receive warnings and have more time to prepare for possible flooding.

**Children and older persons:** Early warnings can help families, caregivers and community organisations prioritise people who may need additional assistance during evacuation.

**People with disabilities:** Accessible warning methods can support people who may face difficulties responding quickly to emergencies.

**Small business owners:** Timely warnings can help business owners protect equipment, goods and other valuable property.

### 5.2 Secondary beneficiaries

- National Disaster Management Agency.
- Freetown City Council.
- Emergency response organisations.
- Community leaders and local authorities.
- Schools, health centres and other public institutions.

### 5.3 Expected community impact

The proposed system could improve awareness of changing flood conditions, strengthen community preparedness and support faster communication between residents and emergency responders.

It may also provide recorded environmental information that can help authorities review flood patterns and improve future planning.

# 6. PROPOSED SOLUTIONS

The proposed solution is to develop the Freetown Flash Flood Alert Network as a sensor-based monitoring and early warning system.

The system will have the following features:

### 6.1 Water-level monitoring

Ultrasonic sensors will measure the distance between the sensor and the water surface. The measurements will be converted into water-level readings in metres.

### 6.2 Rainfall monitoring

A rainfall sensor will collect rainfall measurements. The system will use rainfall intensity, measured in millimetres per hour, as an additional indicator of possible flood risk.

### 6.3 Automated risk assessment

The system will compare collected readings against predefined thresholds and assign a risk category.

### 6.4 Warning notifications

The system will be designed to communicate warnings through:

- Warning sirens.
- SMS notifications.
- Emergency response notifications.
- Monitoring dashboard or status display.

### 6.5 Data recording

The system will record sensor readings, timestamps, risk classifications, system faults and response actions.

### 6.6 Continuous monitoring

The system will repeat the monitoring process every 60 seconds while it is operating.

# 7. COMPUTATIONAL THINKING PROCESS

Computational thinking is the process of solving problems by breaking them into smaller parts and developing logical steps that a computer can follow.

The F3-Alert project applies four major computational thinking concepts.

### 7.1 Decomposition

Decomposition involves dividing a complex problem into smaller and manageable components.

The flood monitoring problem is divided into:

- Water-level monitoring.
- Rainfall monitoring.
- Data validation.
- Risk evaluation.
- Warning notifications.
- Report generation.

Each component performs a specific task within the system.

### 7.2 Pattern recognition

Pattern recognition involves identifying similarities and trends in collected information.

F3-Alert uses pattern recognition to identify changes in water levels and rainfall intensity. For example, repeated increases in water levels may indicate that flooding is becoming more likely.

### 7.3 Abstraction

Abstraction involves focusing on important information while ignoring unnecessary details.

The system focuses on two main environmental measurements: water level and rainfall intensity. Other information that is not directly required for the initial risk calculation is excluded.

### 7.4 Algorithm design

Algorithm design involves developing a sequence of logical instructions to solve a problem.

F3-Alert uses conditional statements to determine whether the environmental conditions are Normal, Alert or Critical Evacuation. It then executes the appropriate response.

# 8. ALGORITHM DESIGN

The F3-Alert algorithm is designed to monitor environmental readings, evaluate flood risks and communicate warnings.

### 8.1 System inputs

- Water-level measurement in metres.
- Rainfall intensity in millimetres per hour.
- Current date and time.
- Sensor identification information.

### 8.2 System processing

The system validates the readings and compares them with the proposed risk thresholds.

The decision rules are:

1. If water level is at least 2.5 metres, classify the condition as Critical Evacuation.
2. Otherwise, if water level is at least 1.8 metres OR rainfall intensity is at least 45 mm/hr, classify the condition as Alert.
3. Otherwise, classify the condition as Normal.
4. If readings are invalid or unavailable, report a sensor fault.

### 8.3 System outputs

- Normal status message.
- Flood alert notification.
- Critical evacuation warning.
- Sensor fault notification.
- Recorded monitoring report.

### 8.4 Monitoring interval

The system will repeat its monitoring process every 60 seconds.

**Note:** The thresholds are proposed values for the academic prototype. They must be calibrated and validated using local environmental data and expert advice before operational use.

# 9. SDG ALIGNMENT

The F3-Alert project supports the United Nations Sustainable Development Goals, particularly SDG 11 and SDG 13.

### 9.1 SDG 11: Sustainable Cities and Communities

SDG 11 aims to make cities and human settlements inclusive, safe, resilient and sustainable.

F3-Alert supports this goal by proposing a system that can help protect communities from flood-related risks, improve disaster preparedness and support safer urban environments.

It is particularly relevant to Target 11.5, which focuses on reducing deaths, the number of people affected and economic losses caused by disasters.

### 9.2 SDG 13: Climate Action

SDG 13 focuses on taking urgent action to combat climate change and its impacts.

F3-Alert supports this goal by promoting preparedness for climate-related hazards through environmental monitoring and early warning.

It is particularly relevant to Target 13.1, which focuses on strengthening resilience and adaptive capacity to climate-related hazards and natural disasters.

The project also relates to Target 13.3 through awareness and improved capacity for responding to climate-related risks.

# 10. OPEN-SOURCE JUSTIFICATION

The F3-Alert project is suitable for an open-source development approach.

Open-source software allows developers and other users to access, study, modify and improve the source code according to the terms of its licence.

Making the project open source can provide the following benefits:

**Transparency:** Other developers can examine the programming logic and understand how the system makes decisions.

**Collaboration:** Students, programmers and technology organisations can contribute improvements.

**Cost effectiveness:** Reusable software can reduce the cost of developing similar monitoring systems.

**Learning opportunities:** The project can serve as an educational example for students studying programming, computer science and environmental technology.

**Community improvement:** Future developers can adapt the system to meet the needs of other flood-prone communities.

The project can be hosted on GitHub to support version control, documentation and collaboration.

A suitable licence, such as the MIT License, may be considered for the software code, subject to the project's requirements.

# 11. DIGITAL PUBLIC GOODS (DPGs)

Digital Public Goods are open-source software, open data, open AI models, open standards and open content that can contribute to sustainable development while meeting requirements relating to privacy, applicable laws and avoiding harm.

F3-Alert has the potential to contribute to the digital public goods approach because it is designed to address a public safety challenge through reusable technology.

The project relates to several Digital Public Goods principles:

### 11.1 Sustainable Development Goals relevance

The project supports disaster preparedness and safer communities, connecting it to SDG 11 and SDG 13.

### 11.2 Open licensing

The source code can be released under an approved open-source licence so that others can study and reuse it under the licence conditions.

### 11.3 Clear ownership

The project should clearly identify its author, contributors and licence.

### 11.4 Documentation

The project should provide installation instructions, system requirements, algorithms, pseudocode and user guidance.

### 11.5 Data accessibility

Non-personal environmental measurements may be stored and exported in standard formats to support analysis and reuse.

### 11.6 Privacy and security

Personal phone numbers and other identifying information used for SMS notifications must be protected. Access to administrative functions should be restricted.

### 11.7 Do no harm

Warnings must be accurate, understandable and coordinated with recognised emergency authorities. The system should not encourage residents to ignore official instructions.

F3-Alert is a proposed project and should not be described as an officially recognised Digital Public Good unless it has completed the required assessment and recognition process.

# 12. SYSTEM MODULES

The system is divided into modules to make development, testing and maintenance easier.

### 12.1 Main System Module

Controls the overall operation of F3-Alert. It initialises the sensors, collects readings and manages the repeated monitoring cycle.

### 12.2 Sensor Data Collection Module

Collects water-level and rainfall measurements from the connected sensors.

### 12.3 Data Validation Module

Checks whether readings are available, numeric and within the permitted operating range of the selected sensors.

### 12.4 Evaluate Risk Module

Processes validated readings and determines the flood risk category.

### 12.5 Risk Classification Module

Assigns one of the three risk levels: Normal, Alert or Critical Evacuation.

### 12.6 Response and Notification Module

Activates the appropriate siren and sends warning messages to residents and relevant response teams.

### 12.7 Report Generation Module

Records system activities and prepares reports showing sensor readings, risk levels, faults and notifications.

# 13. PSEUDOCODE

The following pseudocode describes the main operations of the proposed F3-Alert system.

## 13.1 System Constants

```text
CONSTANT ALERT_WATER_THRESHOLD = 1.8
CONSTANT CRITICAL_WATER_THRESHOLD = 2.5
CONSTANT HEAVY_RAIN_THRESHOLD = 45.0
CONSTANT MONITORING_INTERVAL = 60
```

## 13.2 Main System Module

```text
MODULE MainSystem()

    DECLARE waterLevel AS REAL
    DECLARE rainfallRate AS REAL
    DECLARE riskLevel AS STRING
    DECLARE systemIsRunning AS BOOLEAN

    INITIALISE waterLevelSensor
    INITIALISE rainfallSensor
    INITIALISE communicationService
    INITIALISE systemLog

    SET systemIsRunning = TRUE

    WHILE systemIsRunning = TRUE

        waterLevel = READ waterLevelSensor
        rainfallRate = READ rainfallSensor

        IF ValidateReadings(waterLevel, rainfallRate) = FALSE THEN

            riskLevel = "SENSOR FAULT"

            CALL ReportSensorFault()

        ELSE

            riskLevel = EvaluateRisk(waterLevel, rainfallRate)

            CALL ClassifyRisk(riskLevel)

            CALL ExecuteResponseActions(riskLevel)

        END IF

        CALL GenerateReport(waterLevel, rainfallRate, riskLevel)

        WAIT MONITORING_INTERVAL seconds

    END WHILE

END MODULE
```

## 13.3 Evaluate Risk Function

The Evaluate Risk Function determines the risk level using the collected water-level and rainfall measurements.

```text
FUNCTION EvaluateRisk(waterLevel, rainfallRate)

    IF waterLevel >= CRITICAL_WATER_THRESHOLD THEN

        RETURN "CRITICAL EVACUATION"

    ELSE IF waterLevel >= ALERT_WATER_THRESHOLD OR
            rainfallRate >= HEAVY_RAIN_THRESHOLD THEN

        RETURN "ALERT"

    ELSE

        RETURN "NORMAL"

    END IF

END FUNCTION
```

## 13.4 Risk Classification

The Risk Classification procedure identifies the meaning of each risk category and prepares the system for the appropriate response.

```text
MODULE ClassifyRisk(riskLevel)

    IF riskLevel = "CRITICAL EVACUATION" THEN

        PRINT "CRITICAL FLOOD RISK"
        PRINT "Immediate emergency response required"

    ELSE IF riskLevel = "ALERT" THEN

        PRINT "FLOOD ALERT"
        PRINT "Prepare for possible flooding"

    ELSE IF riskLevel = "NORMAL" THEN

        PRINT "NORMAL CONDITIONS"
        PRINT "Continue monitoring"

    ELSE

        PRINT "UNKNOWN RISK STATUS"

    END IF

END MODULE
```

## 13.5 Response Actions Module

```text
MODULE ExecuteResponseActions(riskLevel)

    IF riskLevel = "CRITICAL EVACUATION" THEN

        ACTIVATE emergencySiren

        SEND_SMS("CRITICAL FLOOD RISK.
        Follow official evacuation instructions.")

        NOTIFY emergencyResponders

    ELSE IF riskLevel = "ALERT" THEN

        ACTIVATE warningSiren

        SEND_SMS("FLOOD ALERT.
        Prepare and monitor official updates.")

        NOTIFY monitoringTeam

    ELSE

        RECORD_STATUS("NORMAL CONDITIONS")

    END IF

END MODULE
```

# 14. REPORT PROCEDURES

The Report Procedures module is responsible for recording, organising and presenting the information collected by the F3-Alert system.

The purpose is to maintain a record of environmental conditions and system activities for monitoring, evaluation and future planning.

### 14.1 Data collection

The system collects:

- Water-level readings.
- Rainfall measurements.
- Date and time of each reading.
- Sensor identification.
- Assigned risk category.

### 14.2 Risk report generation

After evaluating the readings, the system records the assigned risk category and the actions taken.

### 14.3 Sensor fault reporting

When readings are missing, invalid or outside the permitted sensor range, the system records the fault and notifies the operator.

### 14.4 Notification report

The system records the warning messages and notification attempts, including whether the communication service confirms delivery where that information is available.

### 14.5 Daily and monthly reports

The system can produce reports showing:

- Total number of monitoring records.
- Number of Normal readings.
- Number of Alert readings.
- Number of Critical Evacuation readings.
- Number of sensor faults.
- Number of notifications attempted and confirmed.
- Date and time of recorded incidents.

### 14.6 Report Procedures Pseudocode

```text
MODULE GenerateReport(waterLevel, rainfallRate, riskLevel)

    DECLARE reportDate AS STRING
    DECLARE reportTime AS STRING

    reportDate = CURRENT_DATE()
    reportTime = CURRENT_TIME()

    OPEN systemReport

    WRITE reportDate
    WRITE reportTime
    WRITE waterLevel
    WRITE rainfallRate
    WRITE riskLevel

    IF riskLevel = "CRITICAL EVACUATION" THEN

        WRITE "Emergency warning action recorded"

    ELSE IF riskLevel = "ALERT" THEN

        WRITE "Warning action recorded"

    ELSE IF riskLevel = "NORMAL" THEN

        WRITE "Normal monitoring recorded"

    ELSE

        WRITE "Sensor fault or unknown status recorded"

    END IF

    CLOSE systemReport

END MODULE
```

# CONCLUSION

The Freetown Flash Flood Alert Network (F3-Alert) is a proposed technology-based solution for improving flood monitoring and early warning in Freetown, Sierra Leone.

Through sensor monitoring, algorithm design, risk classification and notification procedures, the project demonstrates how programming logic can be applied to address a real environmental challenge.

The project aims to support community preparedness, protect lives and properties, and strengthen disaster response. With further development, testing, local calibration and cooperation with relevant authorities, F3-Alert could provide a foundation for a practical flood early warning system.

# REFERENCES

1. Government of Sierra Leone / National Disaster Management Agency. *Risk Management Policy for Sierra Leone*. Available through the National Disaster Management Agency website: https://ndma.gov.sl/

2. United Nations. *Sustainable Development Goal 11: Sustainable Cities and Communities*. https://sdgs.un.org/goals/goal11

3. United Nations. *Sustainable Development Goal 13: Climate Action*. https://sdgs.un.org/goals/goal13

4. Digital Public Goods Alliance. *Digital Public Goods Standard*. https://www.digitalpublicgoods.net/standard

5. United Nations Office for Digital and Emerging Technologies. *Digital Public Goods*. https://www.un.org/digital-emerging-technologies/content/digital-public-goods
