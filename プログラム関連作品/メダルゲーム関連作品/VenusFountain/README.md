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

#### 動作

- 抽選の一連の流れ

https://github.com/UnknownSP/Portfolio/assets/39638661/f9584d45-9051-4f80-be73-c1ab64e49cfa
https://github.com/UnknownSP/Portfolio/assets/39638661/4743d7d3-cfec-4abf-85e3-48f789edde93

- 開発時の動作

https://github.com/UnknownSP/Portfolio/assets/39638661/362802cd-6158-4ecb-8484-feba0922bdd4

#### 回路

![VENUS_cercuit](https://github.com/UnknownSP/Portfolio/assets/39638661/6f278b08-b12b-421a-83b8-5fee19b69622)

