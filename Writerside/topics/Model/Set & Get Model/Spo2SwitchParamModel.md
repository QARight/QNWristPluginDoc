<show-structure depth="2"/>

# Spo2SwitchParamModel

> 血氧开关模型

## 成员变量

| 名称           | 类型  | 说明                                                                        |
|--------------|-----|---------------------------------------------------------------------------|
| onOff        | Int | SpO2全天开关<br>1：开启<br>0：关闭                                                  |
| startHour    | Int | 监测开始时间（小时，0-23）                                                           |
| startMinute  | Int | 监测开始时间（分钟，0-59）                                                           |
| endHour      | Int | 监测结束时间（小时，0-23）                                                           |
| endMinute    | Int | 监测结束时间（分钟，0-59）                                                           |
| lowSpo2OnOff | Int | 低SpO2警报开关<br>1：开启<br>0：关闭<br>需固件支持 setSpo2AllDayOnOff<br>（当onOff=1时此开关有效） |
| lowSpo2Value | Int | 低SpO2阈值<br>需固件支持 v3SupportSetSpo2LowValueRemind                           |
| notifyFlag   | Int | 通知类型<br>0：无效<br>1：允许通知<br>2：静默通知<br>3：禁用通知<br>需固件支持 getSpo2NotifyFlag     |