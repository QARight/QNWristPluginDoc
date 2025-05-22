<show-structure depth="2"/>

# NotDisturbModel

> 勿扰模式模型

## 成员变量

| 名称                      | 类型  | 说明                                                                                  |
|-------------------------|-----|-------------------------------------------------------------------------------------|
| switchFlag              | Int | 开关<br>1 开启<br>0 关闭                                                                  |
| startHour               | Int | 开始时间<br>时                                                                           |
| startMinute             | Int | 开始时间<br>分                                                                           |
| endHour                 | Int | 结束时间<br>时                                                                           |
| endMinute               | Int | 结束时间<br>分                                                                           |
| haveTimeRange           | Int | 是否有时间范围<br>0 无效<br>1 表示无时间范围<br>2 表示有时间范围<br>功能表getSupportDisturbHaveRangRepeat开启有效 |
| noontimeRESTOnOff       | Int | 白天勿扰开关<br>1 开启<br>0 关闭                                                              |
| noontimeRESTStartHour   | Int | 开始时间<br>时                                                                           |
| noontimeRESTStartMinute | Int | 开始时间<br>分                                                                           |
| noontimeRESTEndHour     | Int | 结束时间<br>时                                                                           |
| noontimeRESTEndMinute   | Int | 结束时间<br>分                                                                           |
| allDayOnOff             | Int | 全天勿扰<br>1 开启<br>0 关闭<br>功能表setOnlyNoDisturbAllDayOnOff开启有效                          |
| intelligentOnOff        | Int | 智能勿扰开关<br>1 开启<br>0 关闭<br>功能表setOnlyNoDisturbSmartOnOff开启有效                         |