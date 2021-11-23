# starter-next-js

## Getting Started

### 依存パッケージのインストール

```
npm install
```

### Next.js を開発モードで起動

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

`pages/index.js`を修正することで、ページの編集を開始することができます。ファイルを編集すると、ページが自動更新されます。

[API routes](https://nextjs.org/docs/api-routes/introduction)は[http://localhost:3000/api/hello](http://localhost:3000/api/hello)でアクセスできます。このエンドポイントは `pages/api/hello.js` で編集できます。

pages/api`ディレクトリは`/api/\*` にマッピングされます。このディレクトリ内のファイルは、React ページではなく、[API routes](https://nextjs.org/docs/api-routes/introduction)として扱われます。

## ビルド

Next.js を本番環境で使用するためのアプリケーションを構築

```
npm run build
```

## Storybook

UI コンポーネントツール Storybook を起動。

```
npm run storybook
```

## Lint + format

### Eslint

```
npm run lint
```

```
npm run lint:fix
```

### stylelint

```
npm run lint:stylelint
```

```
npm run lintfix:stylelint
```

### Prettier

```
format:check
```

```
format:fix
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
