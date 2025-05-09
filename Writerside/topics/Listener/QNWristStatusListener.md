<show-structure depth="2"/>

# QNWristScanListener

> 设备状态监听器

## 方法

### onConnected

设备连接成功

<code-block lang="Kotlin">
    fun onConnected(device: [[[QNWristDevice|QNWristDevice.md]]])
</code-block>

### onConnectFailed

设备连接失败

<code-block lang="Kotlin">
    fun onConnectFailed(code: [[[Int|StatusCode.md]]], device: [[[QNWristDevice|QNWristDevice.md]]])
</code-block>

### onReadyInteractResult {id="onReadyInteractResult"}

设备是否允许交互的回调,当code == 0时，可以开始设置交互，否则即出现了异常

<code-block lang="Kotlin">
    fun onReadyInteractResult(code: [[[Int|StatusCode.md]]], device: [[[QNWristDevice|QNWristDevice.md]]])
</code-block>

### onDisconnected

设备断开连接

<code-block lang="Kotlin">
    fun onDisconnected(device: [[[QNWristDevice|QNWristDevice.md]]])
</code-block>
