|Field Name|Description|
|----------------------------------:|-------------------------------------------------------------------------------------------------------:|
|Customer                           |Customer identifier                                                                                     |
|clli                               |OLT CLLI. Access layer.                                                                                 |
|year                               |Year of the measurement                                                                                 |
|month                              |Month of the measurement                                                                                |
|day                                |Day of the measurement                                                                                  |
|date                               |Date of the measurement                                                                                 |
|rack                               |Rack of the OLT                                                                                         |
|shelf                              |Shelf of the OLT                                                                                        |
|slot                               |Slot of the OLT                                                                                         |
|port                               |PON Port of the OLT                                                                                     |
|ont                                |ONT number on the PON                                                                                   |
|objectName                         |Customer network identifier                                                                             |
|berDownstream                      |Bit Error Rate towards customer                                                                         |
|berUpstream                        |Bit Error Rate towards network                                                                          |
|objectType                         |Object Type for the measurements                                                                        |
|networkRxLevel                     |Received Signal strength at the OLT                                                                     |
|modelRxLevel                       |Received Signal strength at the ONT                                                                     |
|modemTxLevel                       |Transmit Signal strength at the ONT                                                                     |
|distance                           |Estimated distance between ONT and OLT                                                                  |
|opticalTemperature                 |Optical temperature at the ONT                                                                          |
|opticalVoltage                     |Optical voltage at the ONT                                                                              |
|modemType                          |ONT type                                                                                                |
|status                             |ONT status                                                                                              |
|ranged                             |Fiber optic cable range is determined by a number of factors, the most important of which is attenuation|
|laserBiasThreshold                 |Laser bias threshold                                                                                    |
|laserBiasCurrent                   |Laser bias current                                                                                      |
|videoAniAgcModePlanned             |Video ANI planned AGC mode                                                                              |
|videoAniAgcSetting                 |Video ANI AGC setting                                                                                   |
|videoAniOpInfoOpticalSignalLevel   |Video ANI operational information for optical signal level                                              |
|videoAniOpInfoOpticalSignalLevelDbm|Video ANI operational information for optical signal level (dBm)                                        |
|videoAniOpInfoRfPowerLevel         |Video ANI operational information for Radio Frequency power level                                       |
|videoAniOperState                  |Video ANI operational status                                                                            |
|speedProfile                       |Customer's provisioned Internet speed                                                                   |
|Stops_null                         |Radius session stops with cause code NULL                                                               |
|Stops_Admin-Reset                  |Radius session stops with cause code admin_reset                                                        |
|Stops_Idle-Timeout                 |Radius session stops with cause code idle_timeout                                                       |
|Stops_Lost-Carrier                 |Radius session stops with cause code lost_carrier                                                       |
|Stops_Lost-Service                 |Radius session stops with cause code lost_service                                                       |
|Stops_NAS-Error                    |Radius session stops with cause code NAS_error                                                          |
|Stops_NAS-Request                  |Radius session stops with cause code NAS_request                                                        |
|Stops_Port-Error                   |Radius session stops with cause code port_error                                                         |
|Stops_Service-Unavailable          |Radius session stops with cause code service unavalable                                                 |
|Stops_Session-Timeout              |Radius session stops with cause code session_timeout                                                    |
|Stops_User-Error                   |Radius session stops with cause code user_error                                                         |
|Stops_User-Request                 |Radius session stops with cause code user_request                                                       |
|INTENT                             |Intent of the customer call                                                                             |
|CALLCOMPLETIONREASON               |Completion reason for the customer call                                                                 |
|alarms                             |Number of service affecting fiber alarms                                                                |
|Alarm_SECS                         |Total alarm duration in seconds                                                                         |
|Session_SECS                       |Total Radius session duration                                                                           |
|total_stops                        |Total Radius session stops (all cause codes included)                                                   |
|TSO_calls_count                    |Total number of customer calls                                                                          |
|SA_TSO                             |Total number of service affected customer calls                                                         |
|score                              |Service quality score for the customer                                                                  |
|REPORT_DATE                        |Date of the service repair                                                                              |
|service_repair                     |LABEL to be predicted. Service repair done if 1, NULL if not                                            |
|TMAX                               |Maximum Temparature in the day at the customer location                                                 |
|TMIN                               |Minimum Temparature in the day at the customer location                                                 |
|PRCP                               |Total precipitation during the day at the customer location                                             |
|SNOW                               |Total snow accumulation during the day at the customer location   