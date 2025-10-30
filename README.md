# Zenn CLI

# Nodeを入れる方法
以下を参考にする
https://www.neputa-note.net/2024/04/ubuntu-nodejs-install/

# mp4をgifにする方法
zennでは3MB以上の動画を載せれない
gifならある程度行ける
6秒くらいならgifに変換で行ける
例
```bash
ffmpeg -i ahc055.mp4 output.gif
```
# Zenn CLI導入方法
```bash
# Node.jpを導入する
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash sudo apt-get install -y nodejs
nodejs -v
# Zenn CLIをダウンロードする
npm init --yes
npm install zenn-cli
```

# アップデートする場合
```bash
npm install zenn-cli@latest
```

# とりあえず環境構築が完了している場合
* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)
* 新しい記事を作成する
`npx zenn new:article`

* ブラウザで記事を見る
`npx zenn preview`