# SpinFever

## コード置き場及び詳細

- [MedalGame_SPINFEVER](https://github.com/UnknownSP/MedalGame_SPINFEVER)

## 概要

KONAMI様のスピンフィーバーのハードウェアを基にして、回路及びプログラムを作成し動作させたものです。

当初はハードウェアを一から設計して3Dプリンタ等で製作しておりましたが、実機が手に入ったため実機を用いて回路やプログラムの製作をしております。

コード内のstm32f401_SPINFEVERが制御及びI2Cのマスタであり、PIC16fが含まれているコードが指令を受けて動作します。

stm32f401_SPINFEVERはSTMマイコンを搭載した評価ボードであるNUCLEO-F401上で動作し、PIC16fが含まれているものはPIC16f1938上で動作します。

#### 動作

- 一連の動作

https://github.com/UnknownSP/Portfolio/assets/39638661/bcae4cdc-1e79-4094-97d1-e0ef1ebcc978

- 試験開発をしたテストモードの動作

https://github.com/UnknownSP/Portfolio/assets/39638661/1210026e-9ce3-43ce-9359-89398bc7e321

- 試験開発をしたハードウェアの動作

https://github.com/UnknownSP/Portfolio/assets/39638661/df519fb8-c211-46d4-ba9a-287751348281

https://github.com/UnknownSP/Portfolio/assets/39638661/2a6d36d7-f666-40ae-acf6-b1403ba3ec0a

#### 試験開発時のハードウェア

![HW_Prototype1](https://github.com/UnknownSP/Portfolio/assets/39638661/cc033937-9f0d-4c2e-b91a-792b59647aab)
![HW_Prototype2](https://github.com/UnknownSP/Portfolio/assets/39638661/3a8f2b9c-ab26-4d29-9e18-2fcb5b5f191a)
![HW_CroonPrototype1](https://github.com/UnknownSP/Portfolio/assets/39638661/6468536d-ff0e-475c-abc1-ab9abd20e5c5)
![HW_CroonPrototype2](https://github.com/UnknownSP/Portfolio/assets/39638661/d381111a-e7f2-4813-a5e5-fc957e4b82f5)
![HW_CroonPrototype3](https://github.com/UnknownSP/Portfolio/assets/39638661/0530f7c5-6fec-4a6a-8dd4-a59f57f42b19)

#### 回路

![SPIN_cercuit1](https://github.com/UnknownSP/Portfolio/assets/39638661/f16a8322-26aa-4da6-8311-8b7281043db9)
![SPIN_cercuit2](https://github.com/UnknownSP/Portfolio/assets/39638661/49bd5eeb-cd8d-4269-9520-3bb71f375b5d)

