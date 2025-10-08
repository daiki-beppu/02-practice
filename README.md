# 良いコード/悪いコードで学ぶ設計入門 - React/Next.js 版

『良いコード/悪いコードで学ぶ設計入門』の設計原則を React/Next.js で
実践的に学ぶプロジェクトです。

## 📚 学習内容

### 第 1 章: 命名規則

- コンポーネント名、Props 名の良い例・悪い例
- 状態変数の命名規則

### 第 2 章: 状態管理

- グローバル変数の問題
- Context API とカスタムフックの活用

### 第 3 章: コンポーネント設計

- 単一責任の原則
- Presentational/Container 分離

### 第 4 章: カスタムフック設計

- 再利用可能なロジックの抽出
- フックの命名規則

### 第 5 章: Props 設計

- 型安全性
- API の使いやすさ

### 第 6 章: エラーハンドリング

- Error Boundary
- try-catch の適切な使用

### 第 7 章: パフォーマンス最適化

- useMemo/useCallback の適切な使用
- コンポーネントの最適化

## 🚀 セットアップ

```bash
# 依存関係のインストール
pnpm install

# 開発サーバーの起動
pnpm dev

🛠 使用技術

- Next.js 15 - App Router
- React 19
- TypeScript
- Tailwind CSS 4
- shadcn/ui - UIコンポーネント
- Biome/ultracite - Linter/Formatter

📁 プロジェクト構造

src/
├── app/
│   ├── page.tsx                    # トップページ（目次）
│   └── examples/
│       ├── 01-naming/              # 第1章: 命名規則
│       ├── 02-state-management/    # 第2章: 状態管理
│       └── ...
├── components/
│   ├── shadcn-ui/                  # shadcn/uiコンポーネント
│   ├── ExampleCard.tsx             # 例を表示するカード
│   └── CodeBlock.tsx               # コードハイライト
└── lib/
    └── utils.ts                    # ユーティリティ関数

📖 学習の進め方

1. トップページから各章にアクセス
2. 「悪い例」と「良い例」を比較
3. 実際にコードを書いて理解を深める
```
