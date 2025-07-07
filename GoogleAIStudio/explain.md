# Google AI Studio
2025/07/07現在

## Settings(Chat)
Chatでの設定

### 実行設定 (Run settings)
AIの基本的な振る舞いをここで決めます。

- モデル (Gemini 2.5 Pro): どのAIモデルを使用するかを選択します。性能や得意なことが異なる様々なモデルを選べます。

- トークンカウント (Token count): モデルが一度に扱える情報量（コンテキストウィンドウ）の上限と、現在の使用量を示します。

- 温度 (Temperature): 応答の「創造性」を調整します。

    - 低い値 (0に近い): より予測可能で、事実に基づいた堅実な応答になります。

    - 高い値 (1に近い): より創造的で、多様な、時には意外な応答になります。

- メディア解像度 (Media Resolution): 画像などを入力した際の、認識・処理の精細さを設定します。

![alt text](run_settings.png)

### 思考(Thinking)

- 思考モード (Thinking mode): より複雑な推論（チェーン・オブ・ソート）をモデルに許可し、回答の質を向上させます。

- 思考の予算 (Set thinking budget): 思考モード利用時の計算量やステップの上限を設定します。

![alt text](thinking.png)

### ツール (Tools)
AIに特定の能力を与え、より高度なタスクを実行させます。

- 構造化出力 (Structured output): モデルの出力を、JSONのような特定の構造化フォーマットに強制します。

- コード実行 (Code execution): モデルが問題解決のために、Pythonコードを自ら書いて実行できるようになります。

- 関数呼び出し (Function calling): 開発者が定義した外部の関数やAPIを、モデルが呼び出せるようになります。

- Google検索によるグラウンディング (Grounding with Google Search): モデルがGoogle検索を使い、最新の情報や事実に基づいて回答を生成するようになります。

- URLコンテキスト (URL context): 指定されたURLの内容をモデルが読み取り、その情報を元に応答できるようになります。

![alt text](tools.png)

![alt text](output_code.png)

![alt text](output_visual.png)

![alt text](function.png)
