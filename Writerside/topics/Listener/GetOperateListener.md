<show-structure depth="2"/>

# GetOperateListener

> 获取指令操作结果监听

## 方法

### onGetHeartRateModeResult

获取心率模式结果回调

<code-block lang="Kotlin">
    fun onGetHeartRateModeResult(model: [[[HeartRateModeModel?|HeartRateModeModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetStressSwitchResult

获取压力开关结果回调

<code-block lang="Kotlin">
    fun onGetStressSwitchResult(model: [[[StressSwitchModel?|StressSwitchModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetSpo2SwitchResult

获取血氧开关结果回调

<code-block lang="Kotlin">
    fun onGetSpo2SwitchResult(model: [[[Spo2SwitchModel?|Spo2SwitchModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetWalkRemindResult

获取走动提醒结果回调

<code-block lang="Kotlin">
    fun onGetWalkRemindResult(model: [[[WalkRemindModel?|WalkRemindModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetActivitySwitchResult

获取运动模式识别开关结果回调

<code-block lang="Kotlin">
    fun onGetActivitySwitchResult(model: [[[ActivitySwitchModel?|ActivitySwitchModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetAllHealthSwitchStateResult

获取所有的健康监测开关结果回调

<code-block lang="Kotlin">
    fun onGetAllHealthSwitchStateResult(model: [[[AllHealthSwitchStateModel?|AllHealthSwitchStateModel.md]]], response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>

### onGetSportTypeV3Result

获取默认的运动类型结果回调

<code-block lang="Kotlin">
    fun onGetSportTypeV3Result(model: IDOAllHealthSwitchStateModel?, response: [[[InvokeResponse|InvokeResponse.md]]])
</code-block>