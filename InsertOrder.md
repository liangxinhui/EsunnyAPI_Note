下单

```sequence
Application->TapAPI: InsertOrder
TapAPI-->Application: OnRtnOrder
TapAPI-->Application: OnRtnOrder

Note right of Application: ......

```

 撤单：
```sequence
Application->TapAPI: CancelOrder
TapAPI-->Application: OnRtnOrder
```