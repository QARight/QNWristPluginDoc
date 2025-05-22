<show-structure depth="2"/>

# WalkRemindModel

> 走动提醒模型

## 成员变量

| 名称                   | 类型                   | 说明                                                                           |
|----------------------|----------------------|------------------------------------------------------------------------------|
| onOff                | Int                  | 开关状态<br>0：关闭<br>1：开启                                                         |
| goalStep             | Int                  | 每小时目标步数（预留功能，暂未启用）                                                           |
| startHour            | Int                  | 开始时间-小时（24小时制，0-23）                                                          |
| startMinute          | Int                  | 开始时间-分钟（0-59）                                                                |
| endHour              | Int                  | 结束时间-小时（24小时制，0-23）                                                          |
| endMinute            | Int                  | 结束时间-分钟（0-59）                                                                |
| repeats              | HashSet<[](Week.md)> | 重复周期集合，存储`Week`枚举值（如周一、周二等）                                                  |
| goalTime             | Int                  | 目标时间-小时（预留功能，暂未启用）                                                           |
| notifyFlag           | Int                  | 通知类型<br>0：无效<br>1：允许通知<br>2：静默通知<br>3：关闭通知<br>需固件支持 setWalkReminderAddNotify |
| doNotDisturbOnOff    | Int                  | 勿扰模式开关<br>0：关闭<br>1：开启<br>需固件支持 getSupportSetGetNoReminderOnWalkReminderV2   |
| noDisturbStartHour   | Int                  | 勿扰开始时间-小时（0-23）<br>需固件支持 getSupportSetGetNoReminderOnWalkReminderV2          |
| noDisturbStartMinute | Int                  | 勿扰开始时间-分钟（0-59）<br>需固件支持 getSupportSetGetNoReminderOnWalkReminderV2          |
| noDisturbEndHour     | Int                  | 勿扰结束时间-小时（0-23）<br>需固件支持 getSupportSetGetNoReminderOnWalkReminderV2          |
| noDisturbEndMinute   | Int                  | 勿扰结束时间-分钟（0-59）<br>需固件支持 getSupportSetGetNoReminderOnWalkReminderV2          |