<show-structure depth="2"/>

[//]: # (设置右侧导航栏显示层级为2)

# QNWristPlugin

> 手环插件管理类

## 成员变量

| 名称             | 类型                           | 说明     |
|----------------|------------------------------|--------|
| logListener    | [](QNWristLogListener.md)    | 日志输出监听 |
| scanListener   | [](QNWristScanListener.md)   | 设备扫描监听 |
| statusListener | [](QNWristStatusListener.md) | 设备状态监听 |

## 方法

### getInstance

获取一个QNWristPlugin的单例对象

#### 参数

| 名称      | 类型      | 说明  |
|---------|---------|-----|
| context | Context | 上下文 |

#### 返回值类型

`QNWristPlugin`

### initPlugin

初始化QNWristPlugin

### startScan

开始扫描

### stopScan

停止扫描

### connectDevice

连接设备

#### 参数

| 名称     | 类型                   | 说明     |
|--------|----------------------|--------|
| device | [](QNWristDevice.md) | 手环设备对象 |

### cancelConnectDevice

断开设备连接

#### 参数

| 名称     | 类型                   | 说明     |
|--------|----------------------|--------|
| device | [](QNWristDevice.md) | 手环设备对象 |




