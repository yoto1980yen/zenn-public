# Zenn CLI

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