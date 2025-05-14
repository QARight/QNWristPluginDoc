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

### setAlarm

设置闹钟

<code-block lang="Kotlin">
    fun setAlarm(model: [[[AlarmModel|AlarmModel.md]]])
</code-block>

### setHeartRateMode

设置心率模式

<code-block lang="Kotlin">
    fun setHeartRateMode(model: [[[HeartRateModeParamModel|HeartRateModeParamModel.md]]])
</code-block>

### setStressSwitch

设置压力开关

<code-block lang="Kotlin">
    fun setStressSwitch(model: [[[StressSwitchParamModel|StressSwitchParamModel.md]]])
</code-block>

### setRespirationRateTurn

设置呼吸频率开关

<code-block lang="Kotlin">
    fun setRespirationRateTurn(open: Boolean)
</code-block>

### setSpo2Switch

设置血氧开关

<code-block lang="Kotlin">
    fun setSpo2Switch(model: [[[Spo2SwitchParamModel|Spo2SwitchParamModel.md]]])
</code-block>

### setDrinkWaterRemind

设置喝水提醒

<code-block lang="Kotlin">
    fun setDrinkWaterRemind(model: [[[DrinkWaterRemindModel|DrinkWaterRemindModel.md]]])
</code-block>

### setHandWashingReminder

设置洗手提醒

<code-block lang="Kotlin">
    fun setHandWashingReminder(model: [[[HandWashingReminderParamModel|HandWashingReminderParamModel.md]]])
</code-block>

### setWalkRemind

设置走动提醒

<code-block lang="Kotlin">
    fun setWalkRemind(model: [[[WalkRemindModel|WalkRemindModel.md]]])
</code-block>

### setMenstruation

设置经期

<code-block lang="Kotlin">
    fun setMenstruation(model: [[[MenstruationModel|MenstruationModel.md]]])
</code-block>

### setScientificSleepSwitch

设置科学睡眠开关

<code-block lang="Kotlin">
    fun setScientificSleepSwitch(model: [[[ScientificSleepSwitchParamModel|ScientificSleepSwitchParamModel.md]]])
</code-block>

### setActivitySwitch

设置运动模式识别开关

<code-block lang="Kotlin">
    fun setActivitySwitch(model: [[[ActivitySwitchParamModel|ActivitySwitchParamModel.md]]])
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
- 所有开关的获取
- 寻找手表
- 寻找手机
- 天气设置
- 音乐控制
- 手表通知app
- APP 向手表发送信息