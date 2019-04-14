# usb-switcher

USBの接続/切断を電気的に制御できるようにする基板です。

![image](https://user-images.githubusercontent.com/1204511/56092770-08443200-5efb-11e9-827e-4df59f45ffac.png)

## IO

| ピン名 | 機能 |
|-------|------|
|5V/3.3V| 電源 5Vか3.3Vか入力|
|SIG| Low: 接続、 High: 切断 ※Highレベルは電源電圧と同じ |
|GND| GND電源 |

両サイドのUSB-Aメスコネクタに変換ケーブルを指すことによって、色んなタイプのUSBケーブルの接続/切断を制御できます。

USBラインの電流を測るためのジャンパピンがついています。

## 回路図

<img width="1145" alt="schematic" src="https://user-images.githubusercontent.com/1204511/56092751-d6cb6680-5efa-11e9-9be2-2c5320f1e932.png">
