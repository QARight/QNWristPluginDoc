<show-structure depth="2"/>

# QNWristEventListener

> 设备事件监听器

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

### onSetUserInfoResult

设置用户信息结果回调

<code-block lang="Kotlin">
    fun onSetUserInfoResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onFactoryResetResult

恢复出厂设置结果回调

<code-block lang="Kotlin">
    fun onFactoryResetResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetAlarmResult

设置闹钟结果回调

<code-block lang="Kotlin">
    fun onSetAlarmResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetHeartRateModeResult

获取心率模式结果回调

<code-block lang="Kotlin">
    fun onGetHeartRateModeResult(model: [[[HeartRateModeModel?|HeartRateModeModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetHeartRateModeResult

设置心率模式结果回调

<code-block lang="Kotlin">
    fun onSetHeartRateModeResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetStressSwitchResult

获取压力开关结果回调

<code-block lang="Kotlin">
    fun onGetStressSwitchResult(model: [[[StressSwitchModel?|StressSwitchModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetStressSwitchResult

设置压力开关结果回调

<code-block lang="Kotlin">
    fun onSetStressSwitchResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetRespirationRateTurnResult

设置呼吸频率开关结果回调

<code-block lang="Kotlin">
    fun onSetRespirationRateTurnResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetSpo2SwitchResult

获取血氧开关结果回调

<code-block lang="Kotlin">
    fun onGetSpo2SwitchResult(model: [[[Spo2SwitchModel?|Spo2SwitchModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetSpo2SwitchResult

设置血氧开关结果回调

<code-block lang="Kotlin">
    fun onSetSpo2SwitchResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetDrinkWaterRemindResult

设置喝水提醒结果回调

<code-block lang="Kotlin">
    fun onSetDrinkWaterRemindResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetHandWashingReminderResult

设置洗手提醒结果回调

<code-block lang="Kotlin">
    fun onSetHandWashingReminderResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetWalkRemindResult

获取走动提醒结果回调

<code-block lang="Kotlin">
    fun onGetWalkRemindResult(model: [[[WalkRemindModel?|WalkRemindModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetWalkRemindResult

设置走动提醒结果回调

<code-block lang="Kotlin">
    fun onSetWalkRemindResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetMenstruationResult

设置经期结果回调

<code-block lang="Kotlin">
    fun onSetMenstruationResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetScientificSleepSwitchResult

设置科学睡眠开关结果回调

<code-block lang="Kotlin">
    fun onSetScientificSleepSwitchResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetActivitySwitchResult

获取运动模式识别开关结果回调

<code-block lang="Kotlin">
    fun onGetActivitySwitchResult(model: [[[ActivitySwitchModel?|ActivitySwitchModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onSetActivitySwitchResult

设置运动模式识别开关结果回调

<code-block lang="Kotlin">
    fun onSetActivitySwitchResult(response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>
