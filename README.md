# USB-Si5351aCtrl
- Si5351a control program for WindowsPC  
- FT232HとSi5351aを使ったUSB式クロック発生器と制御プログラムです。マイコンとかゲーム機とかのクロック源とかに使えると思います。  
- PC側のソフトはActiveBasic製でWindows専用です。
- ビルドには[こちらの[AB-FT232HLib]](https://github.com/RGBA-CRT/AB-FT232HLib)ライブラリを1階層上に配置する必要があります。

## 回路
PC <--> USB <--> FT232H <--> I2C <--> Si5351a <--> クロック出力といった感じです。

![回路図](https://raw.githubusercontent.com/RGBA-CRT/USB-Si5351aCtrl/master/connection.PNG "回路図")

## 動作イメージ
![ss](https://user-images.githubusercontent.com/19349443/27551699-6a78a64e-5adf-11e7-8d1e-12708f50e746.png)
![ss2](https://cloud.githubusercontent.com/assets/19349443/20931283/f5ad8ace-bc13-11e6-9368-7d7d4fc00b38.jpg)

# [Download](https://github.com/RGBA-CRT/USB-Si5351aCtrl/releases)
