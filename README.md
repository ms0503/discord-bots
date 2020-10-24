# Discord Bots
DiscordのBotのソースコードの公開場所です。
## Template
下記Botの大元です。  
`npm install`をして[Discordの開発ダッシュボード](https://discord.com/developers/applications)でBotを作って  
トークンを`src/config.json`に貼り付けたら`npm start`でそのまま動きます。何もやりませんが。  
基本的な簡易データベース機能のみの搭載でシンプル。
## NGRIGlobal
[NGRI](https://projectr.ddo.jp/)のゲームに関する会話等を行うグローバルチャットBot。  
私が初めて本格的に作ったBotだったり。  
Webhookのありがたみも分かりましたが、curlを使っているのでWindowsには未対応(WSL使えばできるが)。
