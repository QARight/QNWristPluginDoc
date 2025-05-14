<show-structure depth="2"/>

# AlarmModel

> 闹钟模型

## 成员变量

| 名称          | 类型                            | 说明                               |
|-------------|-------------------------------|----------------------------------|
| alarmID     | Int                           | 报警ID，从1开始，范围1~10（最大支持10个）        |
| delayMin    | Int                           | 延迟分钟数，与`repeatTimes`组合使用实现贪睡场景   |
| hour        | Int                           | 闹钟的时钟部分（24小时制）                   |
| minute      | Int                           | 闹钟的分钟部分                          |
| name        | String                        | 报警名称，最大长度为23字节                   |
| isOpen      | Boolean                       | 开关状态（true表示开启，false表示关闭）         |
| repeats     | HashSet<[](Week.md)>          | 重复周期集合，存储`Week`枚举值（如周一、周二等）      |
| repeatTimes | Int                           | 闹钟重复次数：<br>0表示关闭延时功能，>0表示允许贪睡的次数 |
| status      | [](AlarmModel.md#AlarmStatus) | 枚举，可以选择贪睡的次数                     |
| type        | [](AlarmModel.md#AlarmType)   | 报警类型枚举，与`delayMin`配合表示贪睡时长       |

# AlarmStatus {id="AlarmStatus"}

> 枚举，可以选择贪睡的次数

| 名称        | 说明 |
|-----------|----|
| INVALID   | 无效 |
| HIDDEN    | 隐藏 |      
| DISPLAYED | 显示 |

# AlarmType {id="AlarmType"}

> 贪睡时长报警类型

| 名称         | 说明 |
|------------|----|
| WAKEUP     |    |
| SLEEP      |    |
| EXERCISE   |    |
| MEDICATION |    |
| DATE       |    |
| GATHERING  |    |
| MEETING    |    |
| OTHER      |    |