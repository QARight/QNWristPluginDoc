<show-structure depth="2"/>

# InvokeResponse

> 指令回复

## 成员变量

| 名称     | 类型                                | 说明                                                       |
|--------|-----------------------------------|----------------------------------------------------------|
| code   | [Int](StatusCode.md)              | 状态码                                                      |
| device | [QNWristDevice](QNWristDevice.md) | 手环设备，可能为null</br>如当状态码为[3001](StatusCode.md#状态码-蓝牙公共事件)时 |