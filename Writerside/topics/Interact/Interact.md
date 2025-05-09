# 可交互状态的API

> 本层级下的所有API，都需要在设备已连接且处于可交互状态下方能正常调用
>
> `可交互状态` 即收到 [](QNWristStatusListener.md#onReadyInteractResult)的回调且code == 0