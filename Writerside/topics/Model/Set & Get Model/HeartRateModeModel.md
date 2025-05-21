<show-structure depth="2"/>

# HeartRateModeModel

> 心率模式模型

## 成员变量

| 名称                  | 类型  | 说明                                                    |
|---------------------|-----|-------------------------------------------------------|
| mode                | Int | 工作模式<br>0：关闭<br>1：自动（每5分钟监测）<br>2：连续监控（每5秒）<br>3：手动模式 |
| hasTimeRange        | Int | 时间范围开关<br>0：禁用时间范围<br>1：启用时间范围<br>（当设为1时需配置下方时间参数）    |
| startHour           | Int | 开始时间-小时（24小时制，0-23）                                   |
| startMinute         | Int | 开始时间-分钟（0-59）                                         |
| endHour             | Int | 结束时间-小时（24小时制，0-23）                                   |
| endMinute           | Int | 结束时间-分钟（0-59）                                         |
| measurementInterval | Int | 测量间隔（单位：分钟）<br>仅在手动模式下生效                              |