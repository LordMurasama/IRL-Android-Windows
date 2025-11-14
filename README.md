# IRL-Android-Windows (未翻訳: https://github.com/LordMurasama/IRL-Android-Windows/)
> Belabox Cloud Setup for Android and Windows OBS (翻訳用)
> Japanese Translation Branch (the following is superceded by): (https://techdump.murasama.net/belabox-cloud-guides-overview-jp/)

# General Info
このガイドでは、以下の目的のための**低コストで簡単な**解決策を説明します：
- **IRL**ストリーミングにおけるユーザー視聴体験の向上
- **Android**端末をストリーミング用スマートフォンとして活用
- **Windows**端末をホームPCとして活用

> [!NOTE]  
> 完全に「無料」の方法も存在しますが、より高度な技術的知識が必要であり、設定を誤るとホームPCのセキュリティリスクとなる可能性があります。  
> この方法では、ネットワークやシステムセキュリティに意図的に穴を開けることはありません。*(固定IP不要 | ポート転送不要 | ファイアウォール変更不要)*。  
> 追加のセキュリティ/プライバシー詳細はこちら：(https://techdump.murasama.net/belabox-cloud-guides-overview-jp/#security-and-privacy)

---
## Map

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/def6c3de-2990-44bc-a914-9ec119a27af9">

---

# 1 - ストリーミングフォン  

> [!NOTE]   
> 複数の電話機をお持ちの場合は、最新かつ最高の性能を持つものをストリーミングフォンとしてご使用ください  

1.a - Google Playストアから**[IRLPro](https://play.google.com/store/apps/details?id=app.irlpro.android)**をインストールしてください

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">

---
# 2 - SRT/SRTLA リレー

> [!注意]   
> このサーバーは2つのSRTLAストリームを受け取り、[マップ](#map)で表示されるように1つのSRTストリームに結合します

> [!重要]   
> このサービスの利用料は月額10米ドルです

2.a - [Github](https://github.com/signup) でアカウントを作成する *(既にアカウントをお持ちの場合はログインへスキップ)*
 - メールアドレスの確認後、[ログイン](https://github.com/login) してください

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">

2.b - ログイン後、[Belabox Sponsorship](https://github.com/sponsors/rationalsa) ページを開いてください  
 - 下へスクロールし、**月額10ドル**のプランを選択してください（1x SRT/SRTLA リレーサーバーが含まれます）  
 - 請求先情報を入力し、支払い方法を設定してください *(クレジットカードまたはPaypalのみ対応)*
 - または、視聴者に複数月分の[バウチャー](https://shop.belabox.net/product/belabox-cloud-voucher)を購入してもらうことも可能です。

2.c - スポンサー契約またはバウチャーを入手後、[Belabox Cloud](https://cloud.belabox.net)ページを開き
 - Githubアカウントでログイン/認証を行ってください  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">

2.d - ページ上部で**3本の線**を押し、次に**SRT(LA)リレー**を押してください

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">

2.e - **追加**をクリックし、名前を変更してください。**サーバー**を**最も近い場所**に変更してください。

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">

2.f - **IRLPro設定**が表示されるまで下にスクロールし、**IRLに自動追加**ボタンをタップすると、IRLProに正しい情報が自動的に追加されます。  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/70b33a1d-eea9-4590-86b7-2df757d14fc0" height="600">

---
# 3 - ストリーミングフォン
3.a - **IRLProアプリ**を開き、左上の**歯車アイコン**（設定）を選択  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">

3.b - **接続**に移動すると、**Belabox Cloud**が表示されます。**新規接続**をタップしてください。  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">

3.c - 上部の**TWITCH.TV**をタップし、ユーザー名と[ストリームキー](https://dashboard.twitch.tv/settings/stream)を入力して保存をタップしてください  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">

3.d - メニューに戻り、**ストリーマー**をタップしてください

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">

3.e - **Twitchユーザー名**をタップし、ユーザー名を入力してOKをタップ。下にスクロールし、[Streamlabs APIキー](https://streamlabs.com/dashboard#/settings/api-settings)を入力。*(チャット設定を変更する必要がある場合は、再度ここへアクセスしてください)*

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">

3.f - メニューに戻り、**ビデオ**をタップしてください

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">

3.g - **ビデオ**に移動し、以下の設定を行います  
 - **解像度:** 1920x1080p  
 - **FPS:** 30 固定レート  
 - **解像度に応じたビットレート:** オフ  
 - **ビットレート:** 4500 kbps  
 - **フォーマット:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">

3.h - メニューに戻り、**オーバーレイ**をタップし、次に**Webオーバーレイ**をタップします  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">

3.i - IRLProにアラートを追加します。そのためにはブラウザ経由でアラートダッシュボードにアクセスします  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox) にアクセスし、ウィジェットURLをコピーします

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">

3.j - IRLProに戻り、**新しいウェブオーバーレイ**を追加  
 - **名前:** アラート  
 - **URL:** Streamlabs Alertboxからコピーしたものを貼り付け  
 - **幅:** 600
 - **高さ:** 400  
*(アラートのサイズや位置が間違っている場合は後で変更してください)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">

3.k - 保存後、アラートがオンになっていることを確認してください。

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">

3.l - **メインビュー**に戻り、**チャット**が読み込まれていることを**確認**し、**アラート**が**正常に動作**しているかテストしてください
 - Streamlabs *(テスト用アラートは[アラートボックス](https://streamlabs.com/dashboard#/alertbox)で利用可能です)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">

---
# 4 - Windows PC
通常のPCまたはノートPCが使用可能です（より良いストリーム性能のためにはハードウェアNVENCエンコーダー/デコーダー搭載が推奨）。ホームインターネットルーターに直接有線接続するのが最適です。
> [!WARNING]  
> このPCは、ストリーム全体を通じて**安定した**インターネット接続が必要です。アップロード速度は最低6Mbit以上が必須です *[Speedtest](https://www.nperf.com)*

## 4.1 OBS
> [!NOTE]  
> このプログラムは、中継サーバーからストリームを取得し、旧式のRTMP/h.264規格に変換してTwitchに直接配信します。再接続中に視聴者を惹きつけ/楽しませるための動画、テキスト、音楽を設定する豊富なオプションが用意されています

4.1.a - **お使いのシステムに[OBS Studio](https://obsproject.com/download)をダウンロード**  
4.1.b - **OBS Studioをインストール**し、**起動**してください。  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - 自動ウィザードで
 - ストリーミング用に最適化
 - **解像度:** 1920x1080
 - **FPS:** 30
 - **サービス:** Twitch
 - アカウントを接続
 - 新しく表示されたウィンドウでログイン
 - **ビットレート推定**のチェックを外し、手動で **5900** を入力 *(Twitchパートナーの場合は7900)*
 - ウィザードを**完了**

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">

4.1.d - **OBSで**左下の**追加**をクリックし、**シーン**を選択してください
 - Start
 - Live
 - Low
 - Brb
 - End

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">

4.1.e - Liveシーンをクリックし、**メディアソース**を追加して、名前を**Belabox Cloud**とします。
 - 設定用の新しいウィンドウが開きます

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">

4.1.f - **[Belabox Cloud](https://cloud.belabox.net/#relays)** ページを開く  
 - **SRT(LA) リレー** に移動し、  
 - **OBS メディアソース設定** が表示されるまで下にスクロールする

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">

4.1.g - **OBS**に戻り、**同じ設定**を**設定**してください
 - ローカルファイルのチェックを外す
 - ネットワークバッファリングを1MBに設定
 - Belaboxクラウドページから入力をコピー
 - 再接続遅延を2秒に設定
 - 非アクティブ時にファイルを閉じるにチェックを入れる

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">

4.1.h - **Belabox Cloud**ソースを右クリックし、**変換**と**画面に合わせる**を選択 *(または選択してCtrl+Fを押す)*  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">

4.1.i - 次に、**Bellabox-Cloud**ソースを**Low**シーンにコピーします（*CTRL+C*）  
4.1.j - 右下の**設定**に移動します。新しいビデオで**オーディオ**を選択し、**すべてのグローバルオーディオデバイスを無効化**します  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">

4.1.k - 上部メニューバーで**ツール**をクリックし、次に**WebSocketサーバー設定**をクリックします。**WebSocketサーバーを有効にする**にチェックを入れ、**OK**をクリックします。  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">

---
## 4.2 NOALBS
> [!NOTE]  
> Tこれは、接続のビットレートを（統計プロセスを通じて）サンプリングし、チャットコマンドでOBSを制御し、スマートフォンからのストリームが設定された低ビットレートに達した場合や接続が切断された場合に自動的にシーンを切り替えるプログラムです。本プログラムは署名されておらず、この件に関してWindowsのUACダイアログボックスが表示されます。ご自身の責任において実行してください（オープンソースであり、多くのユーザーに利用されており、これに関連するマルウェアの報告はありません）。

4.2.a - **お使いのシステムに対応した[NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)をダウンロードし、任意の場所に解凍してください *(推奨: Streamingフォルダを作成し、その中にNOALBSサブフォルダを作成)*  
4.2.b - このフォルダ内には以下の3つのファイルが存在しているはずです
 - .env
 - config.json
 - noalbs

4.2.c - NOALBSがチャットコマンドに応答するには、Twitchアカウントへのアクセス権限が必要です（代替アカウントの作成と使用を推奨します。Twitch設定の「セキュリティとプライバシー」で「追加アカウントの作成を有効にする」をオンにすると、追加アカウントを作成できます）。 このアカウントを必ず/mod（モデレーター権限付与）してください。Twitchで希望のアカウントにログイン後、この**[リンク](https://b3ck.com/twitch/oauth)**をクリックし、**Twitchで認証**を選択。表示されたコード全体をコピーしてください。

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="300">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="130">

4.2.d - テキストエディタで **.env** ファイルを **開く**
 - 全てをコピーしたデータで置き換える

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

 - sファイルを開いて閉じる

4.2.e - ファイルをダウンロードし、**config.json** と置き換える  
[config.json](config.json)  
4.2.f - テキストエディタで **config.json** ファイルを **開く**  
 - *REPLACE_STREAMER_NAME* が3箇所あるのを、すべて自分のTwitchアカウント名に置き換える

4.2.g - **[Belabox Cloud](https://cloud.belabox.net/#relays)** ページを開き、**SRT(LA) リレー** に移動します  
 - **NOALBSv2 設定** までスクロールダウンします
 - *REPLACE_BELABOX_URL* を Belabox ページの URL で置き換える
 - *REPLACE_BELABOX_INGEST_KEY* を URL の末尾部分で置き換える

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.h - OBSに戻り、Websocket設定を開き、**接続情報を表示**をクリックします。
 - **サーバーパスワード**をコピーします
 - *REPLACE_OBS_WEBSOCKET_PASSWORD*をコピーしたデータで置き換えます
 - 注意：Websocket接続情報は安全に保管してください（配信中・配信外を問わず、決して共有または開示しないでください）

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">

4.2.i - ファイルを保存して閉じます。*詳細情報 [NOALBS Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*  
4.2.j - **noalbs** プログラムを起動します。下図のような画面が表示されます。エラーもここに表示されます。  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">

4.2.k - noalbsファイルを右クリックし、**ショートカットの作成**を選択してショートカットを作成できます。ショートカットをデスクトップなどにドラッグすると、簡単にアクセスできます。 

---
# 5 - OBSを美しくする
基本設定は完了しましたが、シーンはまだ仮置き状態です。
以下に、各シーンの用途と一般的な配置例を説明します。
> [!NOTE]  
> 以下はあくまで推奨事項です。自由にデザインしてください。

**Start**
- ストリームがこのシーンから始まるたびに、電話がライブになるまで
- 動画＋音楽は背景としてよく使われる
- シンプルなテキスト "Starting Soon ..."

**Live**
- スマートフォンからOBSへの接続が確立されるとすぐに表示されます
- オーバーレイはスマートフォン上で動作するため、追加のものは不要です

**Low**
- 電話への接続状態が悪い場合
- 単純なテキスト "low bitrate"
  
**Brb**
- Phoneとの接続が完全に切断された場合、またはIRLProで意図的にライブストリームを終了した場合 *(プライバシー保護のため)*
- 過去のVODやクリップが使用されることが多い（クリップについては、Clipsという名前のフォルダを作成し、VLCメディアソースを追加することを推奨 *[VLC Media Player](https://www.videolan.org/vlc/)が必要*） - VLCの公式サイトから手動でダウンロードを選択し、64ビット版をダウンロードしてインストールしてください。
- シンプルなテキスト "Be right back"
- トイレに行く時やプライベートな会話をする時に切り替えられます
  
**End**
- Twitchチャットで「!end」と入力すると有効化可能
- 動画+音楽の開始と同様
- シンプルなテキスト "Ending Stream"

---
# 6 - 通常操作  
> [!NOTE]  
> すべてのIRLストリームの前に、以下の手順を実行する必要があります  

6.a - 自宅のPCを起動し、インターネット接続が確立されていること、およびPCが自動でシャットダウンしないことを確認してください  
6.b - PC上でOBSとNOALBSを起動してください  
6.c - IRLストリームを開始したい場所へ**外出する**  
6.d - Twitchへのストリーム開始のため、**Twitchチャット**に`!start`と入力する  
6.e - **IRLProでライブ配信開始** -> 数秒後に**ライブシーン**に切り替わる  
6.f - スマートフォンで停止または接続が切断された場合 -> 数秒後に**Brbシーン**に切り替わります  
6.g - スマートフォンからインターネットへの接続が復旧すると -> 数秒後に**ライブシーン**に戻ります  
6.h - IRLProで手動でライブ配信を終了/開始すると、`!brb`と`!live`を切り替えられます  
6.i - 誰かをレイドした場合、またはチャットコマンド`!stop`で**自動で配信を停止**します  

> [!重要]  
> OBSでシーンを変更するたびに、チャットにテキストメッセージが表示されます  
---  
# 7 - 2つ目のインターネット接続  
> [!注意]  
> これはオプションですが、多くの場合でストリームの安定性を大幅に向上させます。ただし、山奥やトンネル内など通信不可エリアでの切断は防げません。

[マップ](#map)で確認できるように、ライブ配信の切断リスクを低減するため、携帯電話用のセカンドインターネット接続を用意できます。  
モバイルWiFiルーター、またはモバイルホットスポットを有効にしたセカンド端末のいずれかです。  

> [!重要]  
> このセカンドSIMには、異なる通信事業者を利用することを強く推奨します。
> 2枚目のSIMカードも全体のデータ使用量の約50%を消費します
---
# 8 - Twitchに直接ストリーミング  

何らかの理由でRelayまたはホームPCが動作しない場合、IRLProアプリで簡単に直接ストリーミングに戻せます。  

8.a - **設定** > **接続** に移動し、**Belaboxをオフ**、**Twitchをオン**に切り替えます  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600"> 
</details>

8.b - **設定**に戻り、次に**動画**を選択します。下にスクロールし、**ビットレートを解像度に合わせる**を再度オンにし、**形式**を**自動**に設定します。  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - Additional Help  
### IRLPro App 
Here is their [Discord](https://discord.gg/irlpro)
### OBS 
you can check their [Forum](https://obsproject.com/forum/) or just look up one of the hundreds of YouTube Tutorials
### NOALBS
Here is their Guide on [Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) and their [Discord](https://discord.gg/efWu5HWM2u)
