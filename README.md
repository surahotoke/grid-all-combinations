# grid-all-combinations
5×5 のマスを CSS Grid の設定パターンで敷き詰めたときの全通りレイアウトを確認できます。

## 実際に確認できるページ
https://surahotoke.github.io/grid-all-combinations

## 説明
- `grid-auto-flow`、`direction`、`writing-mode`、`order` の組み合わせによる全40通りの並びを試しています。
- 見た目上は →↓、→↑、←↓、←↑、↓→、↓←、↑→、↑← の8通りに分類できます。

※ Firefox では `sibling-index()` が未対応のため、`order` を逆にする操作が正しく反映されません。  
Chrome / Edge / Opera / Safari では正常に動作します。