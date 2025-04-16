FROM python:3.13.3-bookworm

# 作業ディレクトリの作成
WORKDIR /app

# ホストのrequirements.txtをコピーしてインストール
COPY requirements.txt .

# 必要なPythonパッケージをインストール
RUN pip install --no-cache-dir -r requirements.txt

# アプリケーションコードをコピー
# COPY ./app .

# コンテナ起動時のデフォルトコマンド（必要に応じて変更）
CMD ["python", "main.py"]
