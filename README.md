## このリポジトリの目的

pages routing で書かれたコードを app routing にリプレイスさせ、next.js13 のキャッチアップをすることを目的にしております。

## 目標

- pages routing から app routing へリプレイス
- storybook の追加

## 前提条件

```
node v18.16.1
npm v9.5.1
react v18.2.0
```

## Installation

```bash
npx create-next-app --example blog-starter blog-starter-app
```

```bash
yarn create next-app --example blog-starter blog-starter-app
```

```bash
pnpm create next-app --example blog-starter blog-starter-app
```

```
 - nodebrew use v18.16.1(anything control tool)
 - rm -rf ./package-lock.json
 - rm -rf ./node_modules
 - npm install
 - npm run dev
```

access for localhost(127.0.0.1)
