# USB-Si5351aCtrl
Si5351a control program for WindowsPC  
FT232HとSi5351aを使ったUSB式クロック発生器と制御プログラムです。マイコンとかゲーム機とかのクロック源とかに使えると思います。  
PC側のソフトはActiveBasic製でWindows専用です。

##回路
PC <--> USB <--> FT232H <--> I2C <--> Si5351a <--> クロック出力といった感じです。

![回路図](https://raw.githubusercontent.com/RGBA-CRT/USB-Si5351aCtrl/master/connection.PNG "回路図")

##動作イメージ
![ss1](https://cloud.githubusercontent.com/assets/19349443/20930352/6e49f052-bc10-11e6-937f-ef16e7ab82be.png)
![ss2](https://cloud.githubusercontent.com/assets/19349443/20931283/f5ad8ace-bc13-11e6-9368-7d7d4fc00b38.jpg)

#[Download](https://github.com/RGBA-CRT/USB-Si5351aCtrl/releases)
