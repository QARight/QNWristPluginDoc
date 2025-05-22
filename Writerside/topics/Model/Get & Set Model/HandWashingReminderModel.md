<show-structure depth="2"/>

# HandWashingReminderModel

> 洗手提醒模型

## 成员变量

| 名称          | 类型                   | 说明                               |
|-------------|----------------------|----------------------------------|
| onOff       | Int                  | 开关状态<br>0：关闭<br>1：打开<br>（默认值：关闭） |
| startHour   | Int                  | 提醒开始时间-小时（24小时制，0-23）            |
| startMinute | Int                  | 提醒开始时间-分钟（0-59）                  |
| endHour     | Int                  | 提醒结束时间-小时（24小时制，0-23）            |
| endMinute   | Int                  | 提醒结束时间-分钟（0-59）                  |
| repeats     | HashSet<[](Week.md)> | 重复周期集合，存储`Week`枚举值（如周一、周二等）      |
| interval    | Int                  | 提醒间隔（单位：分钟）<br>默认值：60分钟          |