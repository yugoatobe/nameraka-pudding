
### 前提条件

**Node.js バージョン18.x.x**が必要です。

### リポジトリのクローン

```shell
git clone https://github.com/AntonioErdeljac/notion-clone-tutorial.git
```

### パッケージのインストール

```shell
npm i
```

### .envファイルの設定

```js
# `npx convex dev`で使用されるデプロイメント
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

各環境変数に適切な値を設定してください。

### Convexのセットアップ

```shell
npx convex dev
```

### アプリケーションの起動

```shell
npm run dev
```