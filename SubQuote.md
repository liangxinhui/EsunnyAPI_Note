```sequence
Note right of Application: 基础数据查询
Application->TapAPI: QryExchange
TapAPI-->Application: OnRspQryExchange
Application->TapAPI: QryCommodity
TapAPI-->Application: OnRspQryCommodity
Application->TapAPI: QryContract
TapAPI-->Application:  OnRspQryContract
Note right of Application: 订阅行情
Application->TapAPI: SubscribeQuote
TapAPI-->Application: OnRspSubscribeQuote
TapAPI-->Application: OnRtnQuote
TapAPI-->Application: OnRtnQuote
Note right of Application: ......





```