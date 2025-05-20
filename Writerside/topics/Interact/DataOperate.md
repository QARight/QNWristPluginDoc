<show-structure depth="2"/>

# DataOperate

> 数据相关操作类

## 方法

### getSupportSyncRecordTypeList {id="getSupportSyncRecordTypeList"}

获取支持同步的记录数据类型列表

<code-block lang="Kotlin">
    fun getSupportSyncRecordTypeList()
</code-block>

### startSyncRecord

同步数据记录
<code-block lang="Kotlin">
    fun startSyncRecord(typeList: List&lt;[[[RecordType|RecordType.md]]])
</code-block>

- typeList为想要同步的数据记录类型列表，支持的类型见[](#getSupportSyncRecordTypeList)