# SpinFever

## コード置き場及び詳細

- [MedalGame_SPINFEVER](https://github.com/UnknownSP/MedalGame_SPINFEVER)

## 概要

KONAMI様のスピンフィーバーのハードウェアを基にして、回路及びプログラムを作成し動作させたものです。

当初はハードウェアを一から設計して3Dプリンタ等で製作しておりましたが、実機が手に入ったため実機を用いて回路やプログラムの製作をしております。

コード内のstm32f401_SPINFEVERが制御及びI2Cのマスタであり、PIC16fが含まれているコードが指令を受けて動作します。

stm32f401_SPINFEVERはSTMマイコンを搭載した評価ボードであるNUCLEO-F401上で動作し、PIC16fが含まれているものはPIC16f1938上で動作します。