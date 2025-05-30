# 日本地図ヒートマップ (Japan Map Heatmap)

[英語版はこちら](#english-version)

このプロジェクトは、D3.jsを使用して日本の都道府県ごとのデータを可視化するシンプルなウェブアプリケーションです。各都道府県は色分けされており、マウスオーバーで詳細情報が表示されます。

## デモ

![デモ画像](https://via.placeholder.com/800x600.png?text=Demo+Image)

ライブデモ: [http://localhost:53733](http://localhost:53733) (ローカル環境で実行中)

## 特徴

- 日本地図の可視化
- 都道府県ごとのデータ表示
- マウスオーバーで詳細情報表示
- レスポンシブデザイン

## 使用技術

- [D3.js](https://d3js.org/)
- HTML5
- CSS3

## インストール

1. リポジトリをクローンします:
   ```bash
   git clone https://github.com/kb129/japan_map_color.git
   ```

2. プロジェクトディレクトリに移動します:
   ```bash
   cd japan_map_color
   ```

3. ブラウザで `index.html` ファイルを開きます。

## アプリケーションの実行

シンプルなHTTPサーバーを使ってローカルでアプリケーションを実行できます:

```bash
# Python 3 を使用して
python3 -m http.server 8000

# そしてブラウザを開き、以下のURLにアクセスします:
# http://localhost:8000/index.html
```

## データ形式

データは `data.json` ファイルに格納されており、以下のような形式です:

```json
{
  "北海道": { "user1": 10 },
  "青森県": { "user1": 5},
  "岩手県": { "user1": 8 },
  "宮城県": { "user1": 7 }
}
```

各都道府県の名前をキーとして、データ値をオブジェクトで格納しています。

## カスタマイズ

- データを変更するには `data.json` ファイルを編集します。
- 地図のスタイルを変更するには `index.html` 内のCSSを編集します。
- インタラクションを追加するにはJavaScriptコードを修正します。

## コントリビューション

コードやドキュメントの改善にご協力いただける方は、プルリクエストをお待ちしております。バグ報告や機能要望も歓迎します。

## ライセンス

このプロジェクトは [MITライセンス](LICENSE) の下で公開されています。詳細は [LICENSE](LICENSE) ファイルを参照してください。

---

# English Version

This project is a simple web application that visualizes data for each prefecture in Japan using D3.js. Each prefecture is color-coded, and detailed information is displayed when hovering over it.

## Demo

![Demo image](https://via.placeholder.com/800x600.png?text=Demo+Image)

Live demo: [http://localhost:53733](http://localhost:53733) (running locally)

## Features

- Visualization of the map of Japan
- Display data by prefecture
- Show details on hover
- Responsive design

## Technologies Used

- [D3.js](https://d3js.org/)
- HTML5
- CSS3

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kb129/japan_map_color.git
   ```

2. Navigate to the project directory:
   ```bash
   cd japan_map_color
   ```

3. Open `index.html` in your browser.

## Running the Application

You can run this application locally by serving the files with a simple HTTP server:

```bash
# Using Python 3
python3 -m http.server 8000

# Then open your browser and go to:
# http://localhost:8000/index.html
```

## Data Format

The data is stored in the `data.json` file and has the following format:

```json
{
  "北海道": { "user1": 10 },
  "青森県": { "user1": 5},
  "岩手県": { "user1": 8 },
  "宮城県": { "user1": 7 }
}
```

Each prefecture name is used as a key, with the data value stored in an object.

## Customization

- To change the data, edit the `data.json` file.
- To modify map styles, edit the CSS within `index.html`.
- To add interactions, modify the JavaScript code.

## Contribution

We welcome contributions to improve the code or documentation. Please submit a pull request with your changes, or open an issue for bug reports and feature requests.

## License

This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.