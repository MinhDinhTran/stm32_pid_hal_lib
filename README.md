# stm32_pid_hal_lib

  ***based on https://blog.csdn.net/qq_18454025/article/details/103443771***

  ***Please check this link for supporting***

# details

***PID lib in peripheral device style, use pid in the way you use peripheral device***

name|type|brief
:--:|:--:|:--:
__PID_StatusDef|enum|show states of pid
__PID_HandleTypeDef|struct|pid struct defined in peripheral device style
GetModul|double|get modulus of a double
PID_Init|void|init all params in pid
PID_DeInit|void|deinit pid
PID_Config|void|config PID
PID_ResetRound|void|reset PID　round to 0
PID_OutputHandler|void|handle PID output
PID_ResetParam|void|reset pid related params
PID_SetAccuracy|void|set PID accuracy
PID_Model_Positional|float|positional pid
PID_Model_Incremental|float|incremental pid
PID_Model_IntegralSeparation|float|integral separation pid
PID_Model_Anti_Windup|float|trapezoidal integral pid
PID_Model_TrapezoidalIntegral|float|trapezoidal integral pid
PID_Model_VariableIntegral|float|variable integral pid

# Author
***how to contact me*** 

***by email 485210633@qq.com, but not my QQ plz***

***I will reply if I can solve the problem***


