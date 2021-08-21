## 目的
標準のプロジェクトテンプレートをベースに、開発作業の効率化に役立つ便利機能を追加すること

## 目標
SCSSが使えるようにする

## 手順
### 1. プロジェクトのひな形を生成する

```
# プロジェクトのひな形生成
# ここではプロジェクト名をsvelte-try-1とする
npx degit sveltejs/temlate svelte-try-1
cd svelte-try-1
npm install
```

### 2. Typescript+Scss が使えるようにする
```
cd <プロジェクト>
node scripts/setupTypeScript.js
```
