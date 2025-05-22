<show-structure depth="2"/>

# StressSwitchModel

> 压力开关模型

## 成员变量

| 名称              | 类型                   | 说明                                                                            |
|-----------------|----------------------|-------------------------------------------------------------------------------|
| onOff           | Int                  | 总开关<br>1：开启<br>0：关闭                                                           |
| startHour       | Int                  | 开始时间（小时，0-23）                                                                 |
| startMinute     | Int                  | 开始时间（分钟，0-59）                                                                 |
| endHour         | Int                  | 结束时间（小时，0-23）                                                                 |
| endMinute       | Int                  | 结束时间（分钟，0-59）                                                                 |
| remindOnOff     | Int                  | 压力提醒开关<br>1：开启<br>0：关闭<br>（当onOff=0时此开关无效）                                    |
| interval        | Int                  | 提醒间隔（单位：分钟），默认值：60                                                            |
| highThreshold   | Int                  | 压力过高阈值                                                                        |
| stressThreshold | Int?                 | 压力校准阈值（默认：80）<br>需固件支持 setSendCalibrationThreshold                            |
| notifyFlag      | Int                  | 通知类型<br>0：无效<br>1：允许通知<br>2：静默通知<br>3：关闭通知<br>需固件支持 getPressureNotifyFlagMode |
| repeats         | HashSet<[](Week.md)> | 重复周期集合，存储`Week`枚举值（如周一、周二等）                                                   |