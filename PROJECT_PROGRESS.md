# プロジェクト進捗管理

最終更新: 2025-10-09

## 📊 完了したタスク

### Phase 1: プロジェクトセットアップ ✅

#### 1.1 環境構築

- [x] Next.js 15 + React 19 + TypeScript プロジェクト作成
- [x] Tailwind CSS 4 導入
- [x] shadcn/ui セットアップ完了
- [x] Biome + Ultracite による Linter/Formatter 設定
- [x] `biome.jsonc` 設定（shadcn/ui 除外）
- [x] npm scripts 設定（`pnpm format`）

#### 1.2 プロジェクト構造

- [x] `src/lib/utils.ts` - shadcn/ui 用ユーティリティ作成
- [x] `src/components/shadcn-ui/` ディレクトリ作成
- [x] `src/app/examples/01-naming/` ディレクトリ構造準備

#### 1.3 ドキュメント

- [x] `README.md` 作成
  - プロジェクトの目的と概要
  - 全 18 章の学習内容
  - 使用技術とセットアップ手順

#### 1.4 基本ページ準備

- [x] `src/app/page.tsx` - トップページ（空）
- [x] `src/app/examples/01-naming/page.tsx` - 第 1 章ページ（空）

---

## 🎯 次回セッション: Phase 2

### 2.1 共通コンポーネント作成

#### ExampleCard コンポーネント

- [ ] ファイル作成: `src/components/ExampleCard.tsx`
- [ ] Props 定義: `title`, `type` ("bad" | "good"), `children`
- [ ] スタイル実装: Tailwind で条件付き色分け
- [ ] アイコン表示: ❌（悪い例）/ ✅（良い例）

#### CodeBlock コンポーネント

- [ ] ファイル作成: `src/components/CodeBlock.tsx`
- [ ] Props 定義: `children`, `language` (オプション)
- [ ] スタイル実装: コードブロック表示
- [ ] 言語ラベル表示機能

### 2.2 トップページ実装

- [ ] ファイル編集: `src/app/page.tsx`
- [ ] タイトルとキャッチコピー
- [ ] 各章へのナビゲーションカード（18 章分）
- [ ] shadcn/ui コンポーネント活用
- [ ] レスポンシブデザイン対応

---

## 📋 Phase 3: 第 1 章実装

### 3.1 サンプルコンポーネント作成

#### 悪い命名の例

- [ ] ファイル作成: `src/app/examples/01-naming/components/BadNamingExample.tsx`
- [ ] 実装内容:
  - `Comp1`, `Comp2` などの曖昧なコンポーネント名
  - `data`, `temp`, `x` などの不明瞭な変数名
  - `handleClick1`, `func` などの曖昧な関数名

#### 良い命名の例

- [ ] ファイル作成: `src/app/examples/01-naming/components/GoodNamingExample.tsx`
- [ ] 実装内容:
  - `UserProfileCard`, `ProductList` などの明確なコンポーネント名
  - `userData`, `productPrice`, `isLoading` などの明確な変数名
  - `handleUserSubmit`, `fetchUserData` などの明確な関数名

### 3.2 第 1 章ページ実装

- [ ] ファイル編集: `src/app/examples/01-naming/page.tsx`
- [ ] ページ構成:
  - タイトル: "第 1 章: 命名規則"
  - 概要説明
  - ExampleCard で悪い例/良い例を並列表示
  - CodeBlock でコード例を表示
  - 命名規則のベストプラクティス解説

### 3.3 第 1 章完成

- [ ] ブラウザで表示確認
- [ ] レスポンシブデザイン確認
- [ ] コードフォーマット確認
- [ ] トップページからのナビゲーション確認

---

## 📅 Phase 4 以降: 第 2 章〜第 18 章

### 第 2 章: 設計の初歩

- [ ] ディレクトリ作成: `src/app/examples/02-design-basics/`
- [ ] 意図が伝わる命名、変数の使い回しを避ける、メソッド化
- [ ] ページ実装

### 第 3 章: カプセル化の基礎

- [ ] ディレクトリ作成: `src/app/examples/03-encapsulation/`
- [ ] 完全コンストラクタ、値オブジェクト、不変性
- [ ] ページ実装

### 第 4 章: 不変の活用

- [ ] ディレクトリ作成: `src/app/examples/04-immutability/`
- [ ] 再代入防止、副作用の回避、不変と可変の使い分け
- [ ] ページ実装

### 第 5 章: データとロジックのカプセル化

- [ ] ディレクトリ作成: `src/app/examples/05-encapsulation-practice/`
- [ ] プリミティブ型執着、static メソッド誤用、多すぎる引数
- [ ] ページ実装

### 第 6 章: 関心の分離

- [ ] ディレクトリ作成: `src/app/examples/06-separation-of-concerns/`
- [ ] 関心事ごとの分割、インターフェイスと実装の分離
- [ ] ページ実装

### 第 7 章: 関心の混在を分離

- [ ] ディレクトリ作成: `src/app/examples/07-separation-practice/`
- [ ] 単一責任、継承より委譲、巨大クラスの対処
- [ ] ページ実装

### 第 8 章: 条件分岐

- [ ] ディレクトリ作成: `src/app/examples/08-conditionals/`
- [ ] 早期 return、interface/ストラテジパターン、フラグ引数
- [ ] ページ実装

### 第 9 章: コレクション

- [ ] ディレクトリ作成: `src/app/examples/09-collections/`
- [ ] ループ処理の条件分岐、コレクション処理のカプセル化
- [ ] ページ実装

### 第 10 章: 設計を損なう悪魔たち

- [ ] ディレクトリ作成: `src/app/examples/10-code-smells/`
- [ ] デッドコード、マジックナンバー、null 問題、グローバル変数
- [ ] ページ実装

### 第 11 章: 名前設計

- [ ] ディレクトリ作成: `src/app/examples/11-naming-design/`
- [ ] 目的駆動名前設計、技術駆動命名の回避
- [ ] ページ実装

### 第 12 章: コメント

- [ ] ディレクトリ作成: `src/app/examples/12-comments/`
- [ ] 退化コメント回避、目的や仕様変更の注意点を伝える
- [ ] ページ実装

### 第 13 章: メソッド（関数）

- [ ] ディレクトリ作成: `src/app/examples/13-methods/`
- [ ] コマンド・クエリ分離、引数の扱い、戻り値の設計
- [ ] ページ実装

### 第 14 章: モデリング

- [ ] ディレクトリ作成: `src/app/examples/14-modeling/`
- [ ] 目的別モデリング、単一責任と単一目的、深いモデル
- [ ] ページ実装

### 第 15 章: リファクタリング

- [ ] ディレクトリ作成: `src/app/examples/15-refactoring/`
- [ ] ネスト解消、テストコードを用いた安全なリファクタリング
- [ ] ページ実装

### 第 16 章: 設計の意義

- [ ] ディレクトリ作成: `src/app/examples/16-design-significance/`
- [ ] 設計しないと生産性低下、コード品質指標
- [ ] ページ実装

### 第 17 章: 開発プロセスとの戦い

- [ ] ディレクトリ作成: `src/app/examples/17-development-process/`
- [ ] コミュニケーション、レビュー、チームの設計力向上
- [ ] ページ実装

### 第 18 章: 設計技術の深め方

- [ ] ディレクトリ作成: `src/app/examples/18-further-learning/`
- [ ] 推薦図書紹介、設計スキル向上の学び方
- [ ] ページ実装

---

## 📁 現在のディレクトリ構造

```
practice/
├── README.md                          ✅ 完成
├── PROJECT_PROGRESS.md                ✅ 本ファイル
├── package.json                       ✅ 設定済
├── biome.jsonc                        ✅ 設定済
├── tsconfig.json                      ✅ 設定済
├── next.config.ts                     ✅ 設定済
├── tailwind.config.ts                 ✅ 設定済
│
├── src/
│   ├── app/
│   │   ├── layout.tsx                 ✅ デフォルト
│   │   ├── globals.css                ✅ デフォルト
│   │   ├── page.tsx                   🔲 Phase 2で実装
│   │   └── examples/
│   │       └── 01-bad-structure/
│   │           ├── page.tsx           🔲 Phase 3で実装
│   │           └── components/        🔲 Phase 3で作成
│   │               ├── BadNamingExample.tsx
│   │               └── GoodNamingExample.tsx
│   │
│   ├── components/
│   │   ├── shadcn-ui/                 ✅ 設定済
│   │   │   ├── button.tsx
│   │   │   └── card.tsx
│   │   ├── ExampleCard.tsx            🔲 Phase 2で作成
│   │   └── CodeBlock.tsx              🔲 Phase 2で作成
│   │
│   └── lib/
│       └── utils.ts                   ✅ 設定済
│
└── public/                            ✅ デフォルト画像
```

---

## 🛠 使用技術スタック

| カテゴリ             | 技術              | バージョン    | 用途                       |
| -------------------- | ----------------- | ------------- | -------------------------- |
| フレームワーク       | Next.js           | 15.5.4        | React フレームワーク       |
| ライブラリ           | React             | 19.1.0        | UI ライブラリ              |
| 言語                 | TypeScript        | 5.x           | 型安全性                   |
| スタイリング         | Tailwind CSS      | 4.x           | CSS フレームワーク         |
| UI コンポーネント    | shadcn/ui         | -             | 再利用可能なコンポーネント |
| Linter/Formatter     | Biome + Ultracite | 2.2.5 / 5.6.1 | コード品質管理             |
| パッケージマネージャ | pnpm              | -             | 依存関係管理               |

---

## 💡 次回作業時の確認事項

1. **環境確認**

   - `pnpm install` で依存関係が最新か確認
   - `pnpm dev` で開発サーバーが起動するか確認

2. **Phase 2 の開始**

   - `src/components/ExampleCard.tsx` の作成から開始
   - `src/components/CodeBlock.tsx` の作成
   - `src/app/page.tsx` のトップページ実装

3. **デザイン方針**
   - Tailwind CSS を活用したレスポンシブデザイン
   - shadcn/ui コンポーネントの積極活用
   - 悪い例は赤系、良い例は緑系で視覚的に区別

---

## 📝 メモ・気づき

### 設定関連

- `biome.jsonc` で `src/components/shadcn-ui/**` を除外設定済み
- Ultracite プリセットを使用してコードスタイルを統一

### ディレクトリ構造の方針

- App Router の規約に従い、各ルートは `page.tsx` で定義
- ルート固有のコンポーネントは `components/` ディレクトリにコロケーション
- 共通コンポーネントは `src/components/` に配置

### 学習コンテンツの方針

- 各章で「悪い例」→「良い例」の順で提示
- コード例は実際に動くものを用意
- 説明文は簡潔でわかりやすく
