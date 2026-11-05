# PROG101_ASSIGNMENT1_AHMEDA_KOROMA_905006517
Freetown, the capital city of Sierra Leone, experiences intense seasonal rainfall between June and September. Due to rapid urbanization, poor waste management practices blocking drainage channels, and deforestation on hillside slopes, low-lying coastal slum communities face severe and frequent flash flooding. 


Function Main
    Declare String communityName
    Declare Real currentWaterLevel
    Declare Real currentRainRate
    Declare String systemStatus
    Declare Boolean keepMonitoring
    Declare Real criticalWaterThreshold
    Declare Real alertWaterThreshold
    Declare Real heavyRainThreshold

    Assign communityName = "Kroo Bay Sector A"
    Assign criticalWaterThreshold = 2.5
    Assign alertWaterThreshold = 1.8
    Assign heavyRainThreshold = 45.0
    Assign keepMonitoring = True
    Output "F3-Alert System Initialized for: " & communityName
    While keepMonitoring = True
        Output "Enter current water level (metres): "
        Input currentWaterLevel
        Output "Enter current rainfall rate (mm/hour): "
        Input currentRainRate
        Assign systemStatus = EvaluateRisk(currentWaterLevel, currentRainRate, criticalWaterThreshold, alertWaterThreshold, heavyRainThreshold)
        If systemStatus = "CRITICAL"
            Output "[ALARM TRIGGERED] Community siren: ON"
            Output "[SMS BROADCAST] Emergency! Flood imminent. Evacuate to higher ground immediately!"
        Else
            If systemStatus = "WARNING"
                Output "[SYSTEM NOTICE] Siren remains SILENT."
                Output "[SMS BROADCAST] Caution. Water levels are rising. Be on high alert."
            Else
                Output "[STATUS REPORT] System normal. Channels flowing at safe capacity."
            End
        End
        Output "Continue monitoring? Enter True or False: "
        Input keepMonitoring
    End
    Output "F3-Alert monitoring stopped."
End

Function EvaluateRisk (Real level, Real rain, Real critThresh, Real alertThresh, Real rainThresh)
    Declare String statusResult

    If level >= critThresh or (level >= alertThresh and rain >= rainThresh)
        Assign statusResult = "CRITICAL"
    Else
        If level >= alertThresh and level < critThresh
            Assign statusResult = "WARNING"
        Else
            Assign statusResult = "NORMAL"
        End
    End

    ... Unsupported shape: return
    ...  expression="statusResult"
    Return String statusResult
End
