<show-structure depth="2"/>

# DeviceOperate

> 设备相关操作类

## 方法

### bind

绑定设备

<code-block lang="Kotlin">
    fun bind()
</code-block>

### unbind

解绑设备

<code-block lang="Kotlin">
    fun unbind()
</code-block>

### factoryReset

恢复出厂设置

<code-block lang="Kotlin">
    fun factoryReset()
</code-block>

### findDeviceStart

控制寻找手环开始

<code-block lang="Kotlin">
    fun findDeviceStart()
</code-block>

### findDeviceStop

控制寻找手环结束

<code-block lang="Kotlin">
    fun findDeviceStop()
</code-block>

### overFindPhone

停止寻找手机

<code-block lang="Kotlin">
    fun overFindPhone()
</code-block>

### musicStart

控制音乐开始

<code-block lang="Kotlin">
    fun musicStart()
</code-block>

### musicStop

控制音乐停止

<code-block lang="Kotlin">
    fun musicStop()
</code-block>

### sendNotice

发送消息提醒

<code-block lang="Kotlin">
    fun sendNotice(model: IDONoticeMessageParamModel)
</code-block>

## todo hyr
- 实时数据交换