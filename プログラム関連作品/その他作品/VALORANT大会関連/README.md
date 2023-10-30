# VALORANT大会関連作品

## コード置き場及び詳細

- [DiscordBot](https://github.com/KOSENation/discord-bot)

- [Overlay](https://github.com/UnknownSP/ValWind-Overlay)

## 概要

友人と協力し[KOSENation Gaming](https://kosenation.com/)という団体を立ち上げ、[VALORANT](https://playvalorant.com/ja-jp/)の高専生限定大会を開催した際に製作した作品になります。

### DiscordBot

大会を進行するにあたって、各対戦のマップピック及び先攻後攻を公平に決める必要があります。これをDiscord上にてじゃんけんによって決め、そのすべてを自動的に行うボットがDiscordBotになります。

Discord上で決まった内容はKOSENationGaming独自のAPIであるValwind-API(非公開)にPOSTされ、決定した情報が保存されます。 Valwind-APIのデータベースはGCPのCloudSQLを利用しております。

なお、じゃんけんの進行状況はローカルのデータベース(MySQL)に保存されるため、万が一進行が停止しても復帰することが可能となっております。

#### 動作

メインチャンネル上でのBotによるメッセージ
![image1](https://github.com/UnknownSP/Portfolio/assets/39638661/92be2fb2-8c63-4286-ba7d-ada92b50ddd6)

Botとのダイレクトメッセージにてじゃんけんの手をだし、その結果からピックを行っていく。各ピックはメッセージのリアクションボタンを押下することで決定する。
![Image2-1](https://github.com/UnknownSP/Portfolio/assets/39638661/dca27c31-d770-4304-8fe5-f61a1ba87560)
![Image2-2](https://github.com/UnknownSP/Portfolio/assets/39638661/605c387a-e178-43dd-a01b-df65c6761dd2)
![Image2-3](https://github.com/UnknownSP/Portfolio/assets/39638661/3ba6086d-df99-4396-99d3-920ed73e0ccb)

### Overlay

[VALORANT](https://playvalorant.com/ja-jp/)公式大会のようにチームメンバーの体力等の情報をオーバーレイするためのものになります。

#### 動作

https://github.com/UnknownSP/Portfolio/assets/39638661/4d4fae9d-6e7b-4994-b797-29822552650b



