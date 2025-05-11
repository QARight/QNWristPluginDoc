<show-structure depth="2"/>

# DeviceOperate

> 设备相关操作类

## 方法

### bind

绑定设备

<code-block lang="Kotlin">
    fun bind(): [[[Int|StatusCode.md]]]
</code-block>

### unbind

解绑设备

<code-block lang="Kotlin">
    fun unbind(): [[[Int|StatusCode.md]]]
</code-block>

### setUserInfo

设置用户信息

<code-block lang="Kotlin">
    fun setUserInfo(userInfo: [[[UserInfo|UserInfo.md]]]): [[[Int|StatusCode.md]]]
</code-block>

### factoryReset

恢复出厂设置

<code-block lang="Kotlin">
    fun factoryReset(): [[[Int|StatusCode.md]]]
</code-block>