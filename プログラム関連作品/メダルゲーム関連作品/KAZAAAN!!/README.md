# KAZAAAN!!

## コード置き場及び詳細

- [KAZAAAN_組み込み部分](https://github.com/UnknownSP/MedalGame_KAZAAAN)

- [KAZAAAN_遠隔操作用サーバ](https://github.com/UnknownSP/MedalGame_RemoteControlServer)

- [KAZAAAN_遠隔操作用クライアント](https://github.com/UnknownSP/MedalGame_RemoteControlClient)

## 概要

SEGA様のKAZAAAN!!のハードウェアを基にして、回路及びハーネス、プログラムを一から作成し動作させたものです。

[KAZAAAN_組み込み部分](https://github.com/UnknownSP/MedalGame_KAZAAAN)内のKAZAAN_446_mainはメイン処理、KAZAAN_446_subは各ステーションの処理を行います。

[KAZAAAN_遠隔操作用サーバ](https://github.com/UnknownSP/MedalGame_RemoteControlServer)はWebカメラの配信及び組み込み部とのシリアル通信、クライアントへの情報送信を行います。

[KAZAAAN_遠隔操作用クライアント](https://github.com/UnknownSP/MedalGame_RemoteControlClient)はサーバからWebカメラの配信や情報を受け取り、ボール発射やテストモードの操作を行います。

赤外線リモコン操作用の[プログラム及び回路](https://github.com/UnknownSP/RemoteControl)と組み合わせることで部屋の電気も連動させることが可能です。

#### 動作

- 一連の流れ

https://github.com/UnknownSP/Portfolio/assets/39638661/82c78c0f-80a8-4e10-bc39-9b54835ed938

- 遠隔操作を用いた発射

https://github.com/UnknownSP/Portfolio/assets/39638661/dc889a22-4298-4f09-9568-091395f13bfe

- 遠隔操作を用いたテストモード

https://github.com/UnknownSP/Portfolio/assets/39638661/18d12ae6-a884-4bb5-bb96-3c09f04b766a

- 部屋の電気との連動

https://github.com/UnknownSP/Portfolio/assets/39638661/9bbcccc2-ee4a-42fe-b03c-3eeef61b8b9e

#### 回路

- 全体

![KAZAAAN_circuit1](https://github.com/UnknownSP/Portfolio/assets/39638661/5d2bc6ee-b3ee-486c-82e8-69402ba9d2ac)

- メイン基板

![KAZAAAN_circuit_main](https://github.com/UnknownSP/Portfolio/assets/39638661/16f446a2-3e45-4a39-b3b3-6e29e5edd263)

- サブ基板

![KAZAAAN_circuit_sub3](https://github.com/UnknownSP/Portfolio/assets/39638661/746acade-0e31-4b9f-bd45-7b1ddebf2303)
![KAZAAAN_circuit_sub2](https://github.com/UnknownSP/Portfolio/assets/39638661/34369acb-42aa-4157-aacc-4b136b44bb97)
![KAZAAAN_circuit_sub1](https://github.com/UnknownSP/Portfolio/assets/39638661/c9faa613-6420-4807-9ff3-b770839e802a)

