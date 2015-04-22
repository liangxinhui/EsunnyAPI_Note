持仓
```sequence
TapApplication->TapAPI: QryPosition
TapAPI-->TapApplication: OnRspQryPosition
TapAPI-->TapApplication: OnRtnPosition
TapAPI-->TapApplication: OnRtnPosition
TapAPI-->TapApplication: OnRtnPosition
Note right of TapApplication: ......

```