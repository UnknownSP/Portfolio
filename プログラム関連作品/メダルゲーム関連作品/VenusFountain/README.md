# VenusFountain

## コード置き場及び詳細

- [MedalGame_VENUSFOUNTAIN](https://github.com/UnknownSP/MedalGame_VENUSFOUNTAIN)

## 概要

KONAMI様のヴィーナスファウンテンのハードウェアを基にして、回路及びプログラムを作成し動作させたものです。

Unity上で動作しているアプリケーションから実機のような抽選機の操作(回転盤の操作)が可能です。

またサウンドも実機のように流れるようにしております。

コード内のstm32f401_VENUSFOUNTAINが制御及びI2Cのマスタであり、PIC16fが含まれているコードが指令を受けて動作します。

stm32f401_VENUSFOUNTAINはSTMマイコンを搭載した評価ボードであるNUCLEO-F401上で動作し、PIC16fが含まれているものはPIC16f1938上で動作します。

Unityからの操作はstm32f401がPCからシリアル通信でデータを受け取り実行されます。