<show-structure depth="2"/>

# DataOperateListener

> 数据相关操作结果监听

## 方法

### onGetSupportSyncRecordTypeList

支持同步的记录数据类型列表回调

<code-block lang="Kotlin">
    fun onGetSupportSyncRecordTypeList(supportList: List&lt;[[[RecordType|RecordType.md]]]&gt;, response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSyncRecordData

数据记录同步回调

<code-block lang="Kotlin">
    fun onSyncRecordData(record: [[[BaseRecord|BaseRecord.md]]])
</code-block>

- 从手环读取到的数据记录，实际类型为`BaseRecord`的某个子类

### onSyncRecordCompleted

数据记录同步完成回调

- 同步出错时也会回调此方法，此时response的code非0

<code-block lang="Kotlin">
    fun onSyncRecordCompleted(result: Boolean, response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>


