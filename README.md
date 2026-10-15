# Gradient Descent Optimizer Path Visualizer

## 概要
2D損失地形（Bowl/Saddle/Valley）上でSGD・Momentum・Adamの3オプティマイザの降下経路をcanvasアニメーションで可視化する教育ツール。

## 機能
- 3種類の損失地形プリセット（Bowl・Saddle・Valley）
- SGD・Momentum・Adamの経路を色分け描画
- 学習率スライダー（0.005〜0.2）
- 最大ステップ数スライダー
- 各オプティマイザの最終損失値・座標を統計表示

## 使い方
損失地形をドロップダウンで選択し、学習率とステップ数を調整してから「Run All Optimizers」ボタンを押します。3色の軌跡が描画され、各オプティマイザがどのように損失地形を下降するか比較できます。
