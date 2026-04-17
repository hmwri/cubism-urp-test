# cubism-urp-test

## 日本語

Unity 2021.3、Universal Render Pipeline、Cesium for Unity などを組み合わせた検証用 Unity プロジェクトです。Unity パッケージやシーン設定を含むため、Unity Hub からプロジェクトとして開いて確認します。

### 環境

- Unity Editor: 2021.3.14f1
- Universal Render Pipeline: 12.1.8
- Cesium for Unity: 1.2.0
- XR/Oculus 関連 package を含む

### 構成

- `Assets/`: Unity assets と scenes
- `Packages/manifest.json`: Unity package 依存関係
- `ProjectSettings/`: Unity project settings
- `a_BackUpThisFolder_ButDontShipItWithYourGame/`: Unity 生成バックアップ
- `a_BurstDebugInformation_DoNotShip/`: Unity/Burst の生成 debug 出力

### 開き方

1. Unity Hub を開く
2. このリポジトリを既存プロジェクトとして追加する
3. Unity 2021.3.14f1 または互換の 2021.3 LTS で開く
4. `Packages/manifest.json` から package を復元する

### 注意

`DoNotShip` や backup 系の生成フォルダが含まれています。公開・配布用ビルドでは、source control に残す必要があるか確認してください。

## English

A Unity 2021.3 project for testing Universal Render Pipeline with Cesium for Unity and related assets.

### Environment

- Unity Editor: 2021.3.14f1
- Universal Render Pipeline: 12.1.8
- Cesium for Unity: 1.2.0

### Structure

- `Assets/`: Unity assets and scenes
- `Packages/manifest.json`: Unity package dependencies
- `ProjectSettings/`: Unity project settings

### Open

Open the repository from Unity Hub with Unity 2021.3.14f1 or a compatible 2021.3 LTS editor.
