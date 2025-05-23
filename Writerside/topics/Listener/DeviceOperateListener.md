<show-structure depth="2"/>

# DeviceOperateListener

> 设备相关操作结果监听

## 方法

### onBindResult {id="onBindResult"}

绑定结果回调

<code-block lang="Kotlin">
    fun onBindResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

#### 相关状态码 {collapsible="true"}

| 状态码 | 说明                                   |
|-----|--------------------------------------|
| 0   | 绑定失败                                 |
| 1   | 绑定成功                                 |
| 2   | 已经绑定                                 |
| 3   | 需要授权码绑定                              |
| 4   | 拒绝绑定                                 |
| 5   | 绑定错误设备                               |
| 6   | 授权码校验失败                              |
| 7   | 取消绑定                                 |
| 8   | 绑定失败（获取功能表失败)                        |
| 9   | 绑定失败（获取设备信息失败)                       |
| 10  | 绑定超时（支持该功能的设备专用）                     |
| 11  | 新账户绑定，用户确定删除设备数据（支持该功能的设备专用）         |
| 12  | 新账户绑定，用户不删除设备数据，绑定失败（支持该功能的设备专用）     |
| 13  | 新账户绑定，用户不选择，设备超时（支持该功能的设备专用）         |
| 14  | 设备同意配对(绑定)请求，等待APP下发配对结果（支持该功能的设备专用） |

### onUnbindResult

解绑结果回调

<code-block lang="Kotlin">
    fun onUnbindResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onFactoryResetResult

恢复出厂设置结果回调

<code-block lang="Kotlin">
    fun onFactoryResetResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onFindDeviceStartResult

寻找设备开始回调

<code-block lang="Kotlin">
    fun onFindDeviceStartResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onFindDeviceStopResult

寻找设备结束回调

<code-block lang="Kotlin">
    fun onFindDeviceStopResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onOverFindPhoneResult

停止寻找手机结果回调

<code-block lang="Kotlin">
    fun onOverFindPhoneResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onMusicStartResult

控制音乐开始结果回调

<code-block lang="Kotlin">
    fun onMusicStartResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onMusicStopResult

控制音乐停止结果回调

<code-block lang="Kotlin">
    fun onMusicStopResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSendNoticeResult

发送消息提醒结果回调

<code-block lang="Kotlin">
    fun onSendNoticeResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>