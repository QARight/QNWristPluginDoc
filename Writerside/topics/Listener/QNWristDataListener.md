<show-structure depth="2"/>

# QNWristDataListener

> 设备数据监听器

## 方法

### onSyncRecordData

数据记录同步回调

#### 参数

| 名称     | 类型                | 说明                                 |
|--------|-------------------|------------------------------------|
| record | [](BaseRecord.md) | 从手环读取到的数据记录，实际类型为`BaseRecord`的某个子类 |

### onSyncRecordCompleted

数据记录同步完成回调

#### 参数

| 名称     | 类型      | 说明    |
|--------|---------|-------|
| result | Boolean | 是否已结束 |


