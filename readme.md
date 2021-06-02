# Minecraft server 自動化開關

## 前置動作
* bat 檔為 windows 系統用
* Minecraft server 執行檔直接從官網下載，依照需要自己設定 ```run.bat``` 裡面指定的相對位置與檔名
* 安裝 JDK
* 設定 java path

## 設定
* ```run.bat```裡面需要設定自己可識別的 Dname，目前使用```minecraftServer```
* ```stop.bat```裡面把find的字串設定成前命自己定義的 Dname
* 使用系統的排程器設定開關時間