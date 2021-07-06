
# VCIのURL
https://seed.online/products/cb77327e873cfe36e061667a69fbba10bc2eec13285aa862a05cd5b707720820

# メッセージ(INPUT)

|  概要  |  メッセージキー  | 引数 | 補足|
| ---- | ---- | ---- | ---- |
|  残り時間取得  |  REQ_lightjug/timer/v1/remindSec  | なし | TIMER_RESPONSE_REMIND_SECONDのメッセージが返ってくる|
|  時間セット  |  REQ_lightjug/timer/v1/set  | 時間(Sec) ||
|  スタート  |  REQ_lightjug/timer/v1/start  | なし ||
|  ストップ  |  REQ_lightjug/timer/v1/stop  | なし ||
|  リセット  |  REQ_lightjug/timer/v1/reset | なし ||

# メッセージ(OUTPUT)
|  概要  |  メッセージキー  | 発火条件 |戻り値| 補足|
| ---- | ---- | ---- | ---- | ---- |
|  残り時間受け取り  |  RES_lightjug/timer/v1/remindSec  | なし ||
|  タイマー開始  |  PUSH_lightjug/timer/v1/start  | 時間(Sec) ||
|  タイマー終了  |  PUSH_lightjug/timer/v1/end  | なし ||


