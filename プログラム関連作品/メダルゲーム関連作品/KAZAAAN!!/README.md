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