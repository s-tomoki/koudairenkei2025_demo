# similarity_map.ipynb

## 概要
このリポジトリは、画像ファイル間の類似度を可視化するためのJupyter Notebook（similarity_map.ipynb）を含みます
`similarity_map.ipynb` で画像間のコサイン類似度行列の計算・可視化を行います。

## 主な機能
- 画像特徴量（flatten）によるコサイン類似度計算
- 類似度行列のヒートマップ表示

## 必要な環境・依存パッケージ
`requirements.txt` を参照

## 使い方
1. このリポジトリをクローンまたはダウンロード
2. 必要に応じて仮想環境を構築
   ```bash
   python3 -m venv env
   ```
3. 必要に応じて仮想環境を有効化
   ```bash
   source env/bin/activate
   ```
4. 必要に応じてパッケージをインストール
   ```bash
   pip install -r requirements.txt
   ```
3. Jupyter Notebookを起動
   ```bash
   jupyter notebook
   ```
4. similarity_map.ipynb を開き、セルを順に実行

## 備考
- 画像ファイル（.jpg）はリポジトリ直下に配置してください。
- .gitignoreにより画像ファイルはGit管理から除外されています。

