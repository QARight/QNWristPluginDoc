<show-structure depth="2"/>

# QNWristDataListener

> 设备数据监听器

## 方法

### onSyncRecordData

数据记录同步回调

<code-block lang="Kotlin">
    fun onSyncRecordData(record: [[[BaseRecord|BaseRecord.md]]])
</code-block>

- 从手环读取到的数据记录，实际类型为`BaseRecord`的某个子类

### onSyncRecordCompleted

数据记录同步完成回调

<code-block lang="Kotlin">
    fun onSyncRecordCompleted(result: Boolean)
</code-block>


