# ESP32_Faces for M5StickCPlus
ESP32_FacesをM5StickCPlus用にプログラムの書き換えを行いました。主な変更点は以下のとおりです。
*  EyeDrawer.hとESP32_Faces.inoでM5StickC.hを読み込む代わりにM5StickCPlus.hを読み込むようにした。
* 画面の解像度をM5StickCPlusに合わせ135*240にした。
M5StickCPlus.hを読み込むため、M5StickCPlusライブラリが必要です。
おそらくこの2つを変更すれば、どんなM5Stack製品でも動くと思います。(要検証。M5GOでは確認済み)
 
これはESP32_Facesからフォークしています。元のESP32_FacesはM5StickCで動作するようにできているため、M5StickCでやろうと言う方は、元のESP32_Facesをおすすめします。
 
元のESP32_Facesは[こちら](https://github.com/luisllamasbinaburo/ESP32_Faces)
