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

### setUserInfo

设置用户信息

<code-block lang="Kotlin">
    fun setUserInfo(userInfo: [[[UserInfo|UserInfo.md]]])
</code-block>

### factoryReset

恢复出厂设置

<code-block lang="Kotlin">
    fun factoryReset()
</code-block>

### todo hyr

封装过程中发现如果全部套壳工程太过庞大

以下的设置打算简化回调，即

1. 不二次封装IDO的数据模型
2. ~~不回调设置结果~~
3. 不提供功能是否支持查询（即内部自行判断功能表，不对外暴露相关的内容）

需先确定再决定是否如此做

- 闹钟设置
- 心率开关获取和设置
- 压力开关获取和设置
- 呼吸频率获取和设置
- 血氧饱和度获取和设置
- 喝水提醒获取和设置
- 洗手提醒获取和设置
- 走动提醒获取和设置
- 生理周期获取和设置
- 科学睡眠设置
- 勿扰模式设置
- 智能运动识别设置
- 运动类型设置和获取
- 寻找手表
- 寻找手机
- 天气设置
- 音乐控制
- 手表通知app
- APP 向手表发送信息