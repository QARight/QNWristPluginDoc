<show-structure depth="2"/>

# MenstruationModel

> 经期模型

## 成员变量

| 名称                     | 类型  | 说明                                                                                           |
|------------------------|-----|----------------------------------------------------------------------------------------------|
| onOff                  | Int | 经期开关 1开 0关闭                                                                                  |
| menstrualLength        | Int | 经期长度                                                                                         |
| menstrualCycle         | Int | 经期周期                                                                                         |
| lastMenstrualYear      | Int | 最近一次经期开始时间 年                                                                                 |
| lastMenstrualMonth     | Int | 最近一次经期开始时间 月                                                                                 |
| lastMenstrualDay       | Int | 最近一次经期开始时间 日                                                                                 |
| ovulationIntervalDay   | Int | 从下一个经期开始前到排卵日的间隔,一般为14天                                                                      |
| ovulationBeforeDay     | Int | 排卵日之前易孕期的天数,一般为5                                                                             |
| ovulationAfterDay      | Int | 排卵日之后易孕期的天数,一般为5                                                                             |
| notifyFlag             | Int | 通知类型<br>0：无效<br>1：允许通知<br>2：静默通知<br>3：关闭通知<br>需要固件开启功能表支持 getMenstrualAddNotifyFlagV3        |
| menstrualReminderOnOff | Int | 经期提醒开关开关<br>1:开<br>0:关闭<br>需要固件开启功能表支持 getSupportSetMenstrualReminderOnOff 该开关无效时，功能开启就默认提醒。 |