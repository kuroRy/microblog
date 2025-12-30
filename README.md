# Microblog

Flaskを使用したシンプルなマイクロブログアプリケーションです。

## 必要な環境

- Python 3.x
- pip

## セットアップ

1. リポジトリをクローン
```bash
git clone https://github.com/kanChome/microblog.git
cd microblog
```

2. 仮想環境の作成と有効化
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
# または
venv\Scripts\activate  # Windows
```

3. 依存関係のインストール
```bash
pip install flask flask-wtf python-dotenv
```

4. 環境変数の設定（オプション）
`.env`ファイルを作成し、必要に応じて`SECRET_KEY`を設定してください。

## 実行方法

1. 仮想環境を有効化
```bash
source venv/bin/activate  # macOS/Linux
```

2. Flaskアプリケーションを起動
```bash
flask run
```

または

```bash
python microblog.py
```

3. ブラウザでアクセス
```
http://localhost:5000
```

