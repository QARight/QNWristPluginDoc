<show-structure depth="2"/>

[//]: # (设置右侧导航栏显示层级为2)

# QNWristPlugin

> 手环插件管理类

## 成员变量

| 名称             | 类型                           | 说明      |
|----------------|------------------------------|---------|
| dataListener   | [](QNWristDataListener.md)   | 设备事件监听  |
| eventListener  | [](QNWristEventListener.md)  | 设备事件监听  |
| logListener    | [](QNWristLogListener.md)    | 日志输出监听  |
| scanListener   | [](QNWristScanListener.md)   | 设备扫描监听  |
| statusListener | [](QNWristStatusListener.md) | 设备状态监听  |
| dataOperate    | [](DataOperate.md)           | 数据相关操作类 |
| deviceOperate  | [](DeviceOperate.md)         | 设备相关操作类 |

## 方法

### getInstance

`静态方法` 获取一个QNWristPlugin的单例对象

<code-block lang="Kotlin">
    fun getInstance(context: Context): QNWristPlugin
</code-block>

### initPlugin

初始化QNWristPlugin

<code-block lang="Kotlin">
    fun initPlugin(): [[[Int|StatusCode.md]]]
</code-block>

### startScan

开始扫描

<code-block lang="Kotlin">
    fun startScan(): [[[Int|StatusCode.md]]]
</code-block>

### stopScan

停止扫描

<code-block lang="Kotlin">
    fun stopScan(): [[[Int|StatusCode.md]]]
</code-block>

### connectDevice

连接设备

<code-block lang="Kotlin">
    fun connectDevice(device: [[[QNWristDevice|QNWristDevice.md]]]): [[[Int|StatusCode.md]]]
</code-block>

### cancelConnectDevice

断开设备连接

<code-block lang="Kotlin">
    fun cancelConnectDevice(device: [[[QNWristDevice|QNWristDevice.md]]]): [[[Int|StatusCode.md]]]
</code-block>



