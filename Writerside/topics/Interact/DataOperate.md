<show-structure depth="2"/>

# DataOperate

> 数据相关操作类

## 方法

### getSupportSyncRecordTypeList

获取支持同步的记录数据类型列表

<code-block lang="Kotlin">
    fun getSupportSyncRecordTypeList(callback: (List&lt;[[[RecordType|RecordType.md]]]&gt;) -&gt; Unit): [[[Int|StatusCode.md]]]
</code-block>

### startSyncRecord

开始同步所有数据记录
<code-block lang="Kotlin">
    fun startSyncRecord(): [[[Int|StatusCode.md]]]
</code-block>