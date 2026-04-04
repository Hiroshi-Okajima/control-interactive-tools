# control-interactive-tools

制御工学のインタラクティブ教材集（HTML + JavaScript）

## 教材一覧

| # | 教材名 | 内容 | ファイル |
|---|--------|------|----------|
| 01 | 1次系の応答 | ステップ応答・インパルス応答 (K, T) | `control_1st_order.html` |
| 02 | 2次系の応答 | ステップ応答・インパルス応答 (K, ωₙ, ζ) | `control_2nd_order.html` |
| 03 | ボード線図と入出力波形 | 2次系の周波数応答と正弦波入出力 | `control_bode.html` |
| 04 | PID制御 | PIDフィードバック制御のステップ応答・ボード線図 | `control_pid.html` |
| 05 | 3次系の極配置 | 状態フィードバックによる極配置とステップ応答 | `control_poles.html` |
| 06 | 状態推定 | 観測ノイズと速応性の状態推定におけるTrade off | `control_observer.html` |

## GitHub Pages URL

有効化後、以下のURLでアクセスできます：

```
https://hiroshi-okajima.github.io/control-interactive-tools/
```

各教材への直リンク：
- [1次系](https://hiroshi-okajima.github.io/control-interactive-tools/control_1st_order.html)
- [2次系](https://hiroshi-okajima.github.io/control-interactive-tools/control_2nd_order.html)
- [ボード線図](https://hiroshi-okajima.github.io/control-interactive-tools/control_bode.html)
- [PID制御](https://hiroshi-okajima.github.io/control-interactive-tools/control_pid.html)
- [極配置](https://hiroshi-okajima.github.io/control-interactive-tools/control_poles.html)
- [状態オブザーバ](https://hiroshi-okajima.github.io/control-interactive-tools/control_observer.html)

## 使い方

### GitHub Pages で公開
1. Settings → Pages → Source を `main` ブランチ `/（root）`に設定
2. 数分後に上記URLで公開されます

### はてなブログへの埋め込み
```html
<iframe src="https://hiroshi-okajima.github.io/control-interactive-tools/control_bode.html" 
  width="100%" height="800" frameborder="0" style="border:1px solid #ddd; border-radius:8px;"></iframe>
```

### Moodle・Google Sites
- Moodle: HTMLファイルをリソースとして直接アップロード、またはURLリンク
- Google Sites: 「埋め込み」→「埋め込みコード」でiframeを貼り付け

## 技術仕様

- 単一HTMLファイル（外部依存: CDN経由の Chart.js のみ）
- JavaScript でリアルタイム計算（RK4数値シミュレーション等）
- レスポンシブデザイン（PC・タブレット・スマートフォン対応）

## Author

岡島 寛（熊本大学 工学部 情報電気工学科 准教授）
- Web: https://www.control-theory.com
- Blog: https://blog.control-theory.com
- YouTube: https://www.youtube.com/@ControlEngineeringChannel
