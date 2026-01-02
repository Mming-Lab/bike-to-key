# BikeToKey

BLEフィットネスバイクでMinecraft Education Editionを操作するNode-REDプロジェクト

## 概要

バイクを漕ぐ速さに応じてMinecraftキャラクターが移動します。

- 速く漕ぐ (>55rpm): ダッシュ
- 普通に漕ぐ (1-55rpm): 通常移動
- 停止 (<1rpm): 停止

## 必要なもの

- FTMS対応BLEフィットネスバイク
- Node-RED
- Minecraft Education Edition

## 使い方

1. バイクの電源をON
2. Minecraftを起動してワールドに入る
3. Node-REDで [開始] ボタンをクリック
4. バイクを漕ぐ

### デバッグ

- **停止**: [停止] ボタンをクリック
  - データフローを停止（デバッグ用）
- **再開**: [再開] ボタンをクリック
  - データフローを再開

## ライセンス

MIT License

## 作者

mming
