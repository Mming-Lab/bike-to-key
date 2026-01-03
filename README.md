# BikeToKey

日本語 | [English](README_en.md)

フィットネスバイクの運動データをキーボード入力に変換する汎用ツール

## 📖 これは何？

BikeToKeyは、BLEフィットネスバイクを漕ぐ速さに応じて、自動的にキーボード入力を行うNode-REDプロジェクトです。

バイクを漕ぐだけで、パソコン上のゲームやアプリケーションを操作できます。キーボード入力を受け付けるあらゆるソフトウェアで使用可能です。

### 特徴

- 🚴 バイクの回転数(RPM)を検出してキー入力に変換
- 🎮 キーボード操作できるアプリなら何でも使える
- 🔧 キー割り当てや速度設定を自由にカスタマイズ可能
- 📡 Bluetooth接続でワイヤレス

## 🎯 使用例

### Minecraft Education Edition（デフォルト設定）

このプロジェクトは、デフォルトでMinecraft Education Edition向けに設定されています。

**動作:**
- 速く漕ぐ (>55rpm): ダッシュ（W + Ctrl キー）
- 普通に漕ぐ (1-55rpm): 前進（W キー）
- 停止 (<1rpm): 停止（キーを離す）

**使い方:**
1. バイクの電源をON
2. Minecraftを起動してワールドに入る
3. Node-REDで [開始] ボタンをクリック
4. バイクを漕ぐ

## 🛠️ 必要なもの

### ハードウェア
- FTMS対応のBLEフィットネスバイク
- Bluetooth 4.0以上対応のPC

### ソフトウェア
- Node.js
- Node-RED

## 📚 技術情報

- **FTMS (Fitness Machine Service)**: Bluetooth標準プロトコル（UUID: 1826）
- **Indoor Bike Data**: 回転数などのデータ取得（UUID: 2ad2）
- **RobotJS**: キーボード入力シミュレーション

取得できるデータ: 速度、回転数、距離、パワー、消費カロリー、経過時間

## 🧠 動きながら集中する

ADHD特性のある子どもの中には、座ってじっとしているより、体を動かしている方が集中できる子がいます。

米国の研究で、体を動かすこと（フィジェッティング）がADHD児の集中力を高めることが報告されています（[NPR教育](https://www.npr.org/sections/ed/2015/05/14/404959284/fidgeting-may-help-concentration-for-students-with-adhd)、[UC Davis](https://health.ucdavis.edu/news/headlines/does-fidgeting-help-people-with-adhd-focus-/2024/10)）。動くことで脳が覚醒し、前頭前皮質への血流が増加します。

BikeToKeyは、この「動きながら集中できる」特性を活かして、デジタル活動に取り組みながら自然に運動できるツールです。

## 📄 ライセンス

MIT License

## 👤 作者

mming
