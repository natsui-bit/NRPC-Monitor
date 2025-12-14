# NRPC Monitor

Windows用の軽量かつ高機能なシステムモニターアプリです。
タスクマネージャーのような精度で、CPU、GPU、メモリ、ディスク、ネットワーク、バッテリー情報をデスクトップにオーバーレイ表示します。

## 🖥️ 特徴 (Features)

* **リアルタイム監視:** CPU使用率・温度、メモリ、GPU (NVIDIA)、ディスク、ネットワーク、バッテリー情報を取得。
* **高画質表示:** High DPIに対応し、4Kモニターでも文字がぼやけません。
* **ヌルヌル動くグラフ:** 視認性の高い円グラフ・折れ線グラフのアニメーション表示。
* **ミニ・バーモード:** 画面の端に細長く表示する省スペースモード搭載。
* **クリックスルー:** マウス操作を透過させ、ゲーム中も邪魔になりません。
* **カスタマイズ:** パネル数（1～8個）、テーマ（Dark/Light）、透過率などを右クリックで変更可能。

## ⚙️ 動作環境 (Requirements)

* **OS:** Windows 10 / 11 (64bit)
* **Python:** 3.8 以上
* **GPU:** NVIDIA GeForce (GPU情報の取得に必要)

## 📦 依存ライブラリ (Dependencies)

以下のライブラリを使用しています。

* `tkinter` (Standard Lib)
* `psutil`
* `pynvml` (NVIDIA Management Library)
* `wmi`
* `pywin32`
* `pystray`
* `Pillow`

## 🚀 インストールと実行 (Installation & Usage)

### ソースコードから実行する場合

1. リポジトリをクローンまたはダウンロードします。
2. 依存ライブラリをインストールします。
   ```bash
   pip install -r requirements.txt