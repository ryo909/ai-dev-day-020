# Day020 Story — Dependency Flow Board

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day020専用にテーマをseed固定して再生成時の見た目を安定化
- devtools用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: dependency_board
- Mechanic: constrained_lane_movement
- Input/Output: card_creation -> lane_board
- Audience Promise: fewer_rework_cycles
- Publish Hook: 依存関係を守って流せるボード
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Add 2 safe enhancement components from selected_components while keeping the app single-page and stable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day020｜Dependency Flow Board
依存関係を崩さず着手順を整理するフローボード。（話題:GitHub Trending (A）
