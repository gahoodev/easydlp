# eazy-dlp / Media Downloader

![ED](https://gahoodev.gitlab.io/home/ED.png)

<details><summary>English</summary>
A simple and easy-to-use media downloader. Download videos from YouTube and other sites as MP4 or MP3 files.

## Features

- 🎬 **MP4 Download** - Choose from multiple video qualities
- 🎵 **MP3 Extraction** - Convert audio from videos to MP3
- ⚙️ **Settings Screen** - Customize default save location
- 🎨 **Colorful UI** - Beautiful interface inspired by Cwelium
- 📁 **Folder Selection** - Change save location per download

## Download (Installer Version) ※Windows Only

#### 1. Download `eazy-dlp Setup.exe` from the repository and run it

#### 2. Follow the wizard to complete installation

## Download (exe version) ※Windows only
#### Download `eazy-dlp.exe` from the repository and run it

## Download (python version)
### Required Environment

- Python 3.7 or higher
- yt-dlp
- colorama
- colorist

### Download `eazydlp-python3.zip` from the repository and extract it

### 1. Install and use automatically

#### Run `run.bat` on Windows, `run.sh` on Linux/macOS


### 2. Install and use manually


#### 1. Install dependency packages

```bash
pip install -r requirements.txt
```

#### 2. Install yt-dlp (optional)

Included in `requirements.txt`, but if installing separately:

```bash
pip install yt-dlp
```

#### Usage

```bash
python eazydlp.py
```

### Menu

- **«01» MP4 Download** - Download in MP4 format
- **«02» MP3 Download** - Download in MP3 format (audio extraction)
- **«03» Settings** - Change default save location
- **«04» Exit** - Exit the program
- **«~» Credits** - Display credit information

### Usage Example

1. Select `1` from the menu
2. Enter the URL of the video to download
3. Specify the save destination folder (Default: Downloads folder)
4. Select the desired video quality
5. Enter `y` at the confirmation prompt

## Settings

### Changing the Default Save Directory

1. Select `3` (Settings) from the menu
2. Select `1` (Default Save Directory)
3. Enter the new save path

The default save location is set to the user's **Downloads folder**.

## Troubleshooting

### Error: yt-dlp not found

```bash
pip install --upgrade yt-dlp
```

### Installation error for colorama/colorist

```bash
pip install -r requirements.txt
```

## Development Information

- **Developer**: gahoo.dev
- **Website**: https://gahoodev.gitlab.io/home

## License

This project is released under the [MIT License](https://mit-license.org/).

## Important Notes

- Use this tool in compliance with the terms of service of the target download site
- Refrain from unauthorized downloading of copyrighted content
- For using yt-dlp, refer to the [official documentation](https://github.com/yt-dlp/yt-dlp/wiki)

</details>

<details><summary>日本語</summary>
シンプルで使いやすいメディアダウンローダー。YouTube や他の動画サイトから MP4 や MP3 でダウンロードできます。

## 特徴

- 🎬 **MP4 ダウンロード** - 複数の画質から選択可能
- 🎵 **MP3 抽出** - 動画から音声を MP3 に変換
- ⚙️ **設定画面** - デフォルト保存先をカスタマイズ
- 🎨 **カラフルな UI** - Cwelium インスパイアの美しいインターフェース
- 📁 **フォルダ指定** - ダウンロードごとに保存先を変更可能

## ダウンロード(インストーラー版)※Windowsのみ

#### 1. リポジトリから`eazy-dlp Setup.exe`をダウンロードして実行

#### 2. ウィザード通りに進めてインストールを完了

## ダウンロード(exe版)※Windowsのみ
#### リポジトリから`eazy-dlp.exeをダウンロードして実行

## ダウンロード(python版)
### 必要な環境

- Python 3.7 以上
- yt-dlp
- colorama
- colorist

### リポジトリから、`eazydlp-python3.zip`をダウンロードして解凍

### 1. 自動でインストールして使う

#### Windowsは`run.bat` Linux/MacOSは`run.sh`を実行


### 2. 手動でインストールして使う


#### 1. 依存パッケージをインストール

```bash
pip install -r requirements.txt
```

#### 2. yt-dlp をインストール（オプション）

`requirements.txt` に含まれていますが、別途インストールの場合：

```bash
pip install yt-dlp
```

#### 使い方

```bash
python eazydlp.py
```

### メニュー

- **«01» MP4 Download** - MP4 形式でダウンロード
- **«02» MP3 Download** - MP3 形式でダウンロード（音声抽出）
- **«03» Settings** - デフォルト保存先を変更
- **«04» Exit** - プログラムを終了
- **«~» Credits** - クレジット情報を表示

### 使用例

1. メニューから `1` を選択
2. ダウンロードする動画の URL を入力
3. 保存先フォルダを指定（デフォルト: ダウンロードフォルダ）
4. ダウンロード対象の画質を選択
5. 確認プロンプトで `y` を入力

## 設定

### デフォルト保存先の変更

1. メニューから `3` (Settings) を選択
2. `1` (Default Save Directory) を選択
3. 新しい保存先パスを入力

デフォルト保存先はユーザーの **ダウンロードフォルダ** に設定されています。

## トラブルシューティング

### yt-dlp が見つからないエラー

```bash
pip install --upgrade yt-dlp
```

### colorama/colorist のインストールエラー

```bash
pip install -r requirements.txt
```

## 開発情報

- **開発者**: gahoo.dev
- **Webサイト**: https://gahoodev.gitlab.io/home

## ライセンス

このプロジェクトは [MIT ライセンス](https://mit-license.org/)の下で公開されています。

## 注意事項

- このツールはダウンロード対象のサイトの利用規約に準拠して使用してください
- 著作権のあるコンテンツの無許可ダウンロードはお控えください
- yt-dlp の使用に関しては、[公式ドキュメント](https://github.com/yt-dlp/yt-dlp/wiki)を参照してください
</details>
