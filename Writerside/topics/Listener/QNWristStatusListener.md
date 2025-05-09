<show-structure depth="2"/>

# QNWristScanListener

> 设备状态监听器

## 方法

### onConnected

设备连接成功

#### 参数

| 名称     | 类型                   | 说明     |
|--------|----------------------|--------|
| device | [](QNWristDevice.md) | 手环设备对象 |

### onConnectFailed

设备连接失败

#### 参数

| 名称     | 类型                   | 说明     |
|--------|----------------------|--------|
| code   | [](QNWristDevice.md) | 状态码    |
| device | [](QNWristDevice.md) | 手环设备对象 |

### onReadyInteractResult {id="onReadyInteractResult"}

设备是否允许交互的回调,当code == 0时，可以开始设置交互，否则即出现了异常

#### 参数

| 名称     | 类型                   | 说明     |
|--------|----------------------|--------|
| code   | [](QNWristDevice.md) | 状态码    |
| device | [](QNWristDevice.md) | 手环设备对象 |

### onDisconnected

设备断开连接

#### 参数

| 名称     | 类型                   | 说明     |
|--------|----------------------|--------|
| device | [](QNWristDevice.md) | 手环设备对象 |
