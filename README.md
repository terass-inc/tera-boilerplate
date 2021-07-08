# tera-boilerplate

Terass typescript project bilerplate

## `@terass-inc/tera-boilerplate`

lint, build 関連の依存 package を提供する。

```sh
yarn add -DW @terass-inc/tera-boilerplate
```

## `@terass-inc/eslint-config`

terass-inc で共通で使用する eslint の設定を提供する。

```sh
yarn add -DW @terass-inc/eslint-config
```

```js
// .eslintrc.json
{
  "root": true,
  "extends": ["@terass-inc/eslint-config"]
}
```

## `.prettierrc`

ref https://prettier.io/docs/en/option-philosophy.html

## `Brewfile`

node, yarn など開発環境に必要なコマンド・ライブラリのセットアップ方法は各自に委ねるが、依存の可視化と推奨のセットアップ方法として `Brewfile` を提供する。

```sh
cat Brewfile
brew bundle --no-lock
```

## [WIP] `packages/sample-vite`

`vite`を使った frontend のサンプル。

# links

- https://eslint.org/docs/developer-guide/shareable-configs
- https://github.com/typescript-eslint/typescript-eslint/blob/master/docs/getting-started/linting/README.md
- https://www.npmjs.com/package/@typescript-eslint/parser#user-content-configuration
- https://github.com/benmosher/eslint-plugin-import/

# memo

```sh
yarn add -D react react-dom @types/react @types/react-dom vite
```
