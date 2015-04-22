查询合约：
```sequence
Application->TapAPI: QryExchange
TapAPI-->Application: OnRspQryExchange
Application->TapAPI: QryCommodity
TapAPI-->Application: OnRspQryCommodity
Application->TapAPI: QryContract
TapAPI-->Application:  OnRspQryContract
```

订阅行情：
```sequence
Application->TapAPI: SubscribeQuote
TapAPI-->Application: OnRspSubscribeQuote
TapAPI-->Application: OnRtnQuote
TapAPI-->Application: OnRtnQuote
Note right of Application: ......

```

退订行情：
```sequence
Application->TapAPI: UnSubscribeQuote
TapAPI-->Application: OnRspUnSubscribeQuote
```

查询历史行情：
```sequence
Application->TapAPI: QryHisQuote
TapAPI-->Application: OnRspQryHisQuote
```