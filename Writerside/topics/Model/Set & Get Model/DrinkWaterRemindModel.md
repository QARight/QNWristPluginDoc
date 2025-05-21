<show-structure depth="2"/>

# DrinkWaterRemindModel

> 喝水提醒模型

## 成员变量

| 名称                   | 类型                   | 说明                                                                             |
|----------------------|----------------------|--------------------------------------------------------------------------------|
| onOff                | Int                  | 开关<br>0：关闭<br>1：开启                                                             |
| startHour            | Int                  | 开始时间-小时（0-23）                                                                  |
| startMinute          | Int                  | 开始时间-分钟（0-59）                                                                  |
| endHour              | Int                  | 结束时间-小时（0-23）                                                                  |
| endMinute            | Int                  | 结束时间-分钟（0-59）                                                                  |
| repeats              | HashSet<[](Week.md)> | 重复周期集合，存储`Week`枚举值（如周一、周二等）                                                    |
| interval             | Int                  | 提醒间隔（单位：分钟）                                                                    |
| notifyFlag           | Int?                 | 通知类型<br>0：无效<br>1：允许通知<br>2：静默通知<br>3：关闭通知<br>需固件支持 setDrinkWaterAddNotifyFlag |
| doNotDisturbOnOff    | Int?                 | 免打扰开关<br>00：关闭<br>01：开启<br>需固件支持 setNoReminderOnDrinkReminder                  |
| noDisturbStartHour   | Int?                 | 免打扰开始时间-小时（0-23）<br>需固件支持 setNoReminderOnDrinkReminder                         |
| noDisturbStartMinute | Int?                 | 免打扰开始时间-分钟（0-59）<br>需固件支持 setNoReminderOnDrinkReminder                         |
| noDisturbEndHour     | Int?                 | 免打扰结束时间-小时（0-23）<br>需固件支持 setNoReminderOnDrinkReminder                         |
| noDisturbEndMinute   | Int?                 | 免打扰结束时间-分钟（0-59）<br>需固件支持 setNoReminderOnDrinkReminder                         |