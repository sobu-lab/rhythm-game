# rhythm-game

カメラ動体検出・骨格検知を使ったリズムゲームのプロトタイプ集です。

## ページ一覧

| ページ | リンク | 説明 |
|--------|--------|------|
| ふりふりリズム！ | [game.html](https://sobu-lab.github.io/rhythm-game/game.html) | カメラで腕を振ってノーツを叩くリズムゲーム本体。キーボード（← →）でも操作可能 |
| アバターサンプル | [avatar.html](https://sobu-lab.github.io/rhythm-game/avatar.html) | タップ・キーボードで動くロブロックス風2Dアバターのデモ |
| 骨格検出デモ | [pose-demo.html](https://sobu-lab.github.io/rhythm-game/pose-demo.html) | MediaPipe Pose によるリアルタイム骨格検出。カメラ映像に骨格をオーバーレイ表示 |
| 骨格 × アバター連携（2D） | [pose-avatar.html](https://sobu-lab.github.io/rhythm-game/pose-avatar.html) | 骨格検出に連動して2Dアバターが動くデモ |
| 骨格 × アバター連携（3D） | [avatar-3d.html](https://sobu-lab.github.io/rhythm-game/avatar-3d.html) | Three.js の3Dアバターが骨格検出に連動して動くデモ。ドラッグで視点回転可能 |

## 技術スタック

- **MediaPipe Pose** — リアルタイム骨格検出（33点ランドマーク）
- **Three.js** — 3Dアバター描画
- **Web Audio API** — BGM・SE生成（外部ファイル不要）
- **Canvas 2D API** — 2Dアバター・骨格オーバーレイ描画
