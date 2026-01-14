# test5

pytest テストを含む FastAPI "Hello World" アプリケーション

## インストール

必要な依存関係をインストールします：

```bash
pip install -r requirements.txt
```

## アプリケーションの実行

FastAPI サーバーを起動します：

```bash
uvicorn main:app --reload
```

アプリケーションは `http://localhost:8000/` でアクセス可能になります。

ルートエンドポイントにアクセスして "Hello World" を確認します：
- URL: `http://localhost:8000/`
- レスポンス: `{"message": "Hello World"}`

## API ドキュメント

FastAPI は自動的にインタラクティブな API ドキュメントを提供します：
- Swagger UI: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`

## テストの実行

pytest でテストスイートを実行します：

```bash
pytest
```

詳細な出力を表示する場合：

```bash
pytest -v
```