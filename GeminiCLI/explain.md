# GeminiCLI

[Proは1日100回, Flash-Liteだと1000らしい(2025/07/07現在)](https://ai.google.dev/gemini-api/docs/rate-limits?hl=ja)

## GeminiCLI インストール

2025/07/05現在

node.jsのインストールをしてからGeminiCLIのインストールが必要

### node.jsのインストール

1. [https://nodejs.org/ja/download](https://nodejs.org/ja/download)に移動
2. 公式にあるコマンドをzshで入力(nvmを使うだけで、ver切り替えが容易), どのディレクトリ下でもOK
```
  # nvmをダウンロードしてインストールする：  
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash  
  # シェルを再起動する代わりに実行する  
  \. "$HOME/.nvm/nvm.sh" # 公式推奨だがうまくいかず
  . "$HOME/.nvm/nvm.sh" # こっちの方が上手くいった(.zshrcに書き込まれた)
  
  # Node.jsをダウンロードしてインストールする：  
  nvm install 22  

  # Node.jsのバージョンを確認する：  
  node -v # "v22.17.0"が表示される。  
  nvm current # "v22.17.0"が表示される。  
  # npmのバージョンを確認する：  
  npm -v # "10.9.2"が表示される。   
```

### GeminiCLIをnpmでインストール

1. このまま`npm install -g @google/gemini-cli`を入力(権限周りのエラーはなかった)
2. geminiとターミナルで入力
3. theme(見た目)と設定を選択(GithubとUserSettingsを今回選択)
4. ログイン方法の選択(Login with Googleを選択)し、ブラウザでログイン
5. クリア

## 参考文献

https://note.com/munakata_souri/n/n36c29a93d9a7

[GitHub](https://github.com/google-gemini/gemini-cli)
