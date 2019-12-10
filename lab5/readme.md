# LAB5 readme
## 介面
![](https://i.imgur.com/pONeTcM.png)
![](https://i.imgur.com/cFM5cU3.png)

## 介紹
lamp0 open:開啟lamp0
lamp0 close:關閉lamp0
lamp1 open:開啟lamp1
lamp1 close:關閉lamp1

all on:燈全開
all off:燈全關
update:更新現在燈泡狀況

## node red
![](https://i.imgur.com/Hh9oEER.png)
透過lsiten to post監聽由哪個按鈕發出的指令將指令傳送到GSCL更改燈泡狀態
all on/off功能由傳送2個on/off post指令完成
![](https://i.imgur.com/yl8DMbg.png)
![](https://i.imgur.com/Reqgnju.png)
訂閱各個燈泡
![](https://i.imgur.com/dkqQLOy.png)
更新各個燈泡狀態
透過OM2M get status功能取得個燈泡狀態經過處理回傳給app

