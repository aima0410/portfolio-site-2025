# かりこのポートフォリオサイト【2025年版】
お気に入りの2つのポートフォリオサイトを見て感じた「これと同じものを自分でも作ってみたい」をそのまま実現したポートフォリオサイトです。

## 使用技術
| 種別 | 名称 | バージョン |
| - | - | - | - |
| フレームワーク | Astro | ^5.1.9 |
| 言語 | TypeScript | ^5.0.0 |
| フォーマッター | Prettier |  |
| リンター | ESLint |  |
| プラグイン | @astrojs/react | ^4.2.0 |
| ライブラリ | React | ^19.0.0 |

## ディレクトリ構成
```sh
public/
src/
├── assets/
│   ├── images/
│   └── 3dcg/
├── pages/
│   └── index.astro
├── components/
│   ├── heading/
│   ├── button/
│   └── card/
├── layouts/
│   ├── container/
│   ├── contents/
│   └── items-align/
├── sections/
│   ├── hero/
│   ├── aboutme/
│   │   ├── index.astro
│   │   ├── profile/
│   │   │   ├── index.astro
│   │   │   ├── ProfileContent.astro
│   │   │   └── data.ts
│   │   ├── card-note/
│   │   ├── card-skillset/
│   │   ├── card-latest-blog/
│   │   └── card-favo-music/
│   ├── works/
│   │   ├── index.astro
│   │   ├── WorksCard.astro
│   │   └── data.ts
│   ├── toolbox/
│   │   ├── index.astro
│   │   ├── ToolBoxCard.astro
│   │   └── data.ts
│   ├── contact/
│   │   ├── index.astro
│   │   ├── ContactItem.astro
│   │   └── data.ts
│   ├── finally/
│   │   ├── index.astro
│   │   ├── IntroCard.astro
│   │   └── data.ts
│   ├── header/
│   │   ├── index.astro
│   │   ├── DarkLightModeToggleButton.tsx
│   │   └── data.ts
│   └── footer/
│       └── index.astro
├── styles/
├── types/
└── utils/
```


## インストール手順
### ◯ Astro
```sh
$ cd プロジェクトの設置ディレクトリ
$ yarn create astro
```
### ◯ Prettier
```sh
$ yarn add --dev prettier prettier-plugin-astro
```
### ◯ ESLint
```sh
$ yarn add --dev eslint eslint-plugin-astro @typescript-eslint/parser eslint-config-prettier eslint-plugin-jsx-a11y

# ESLintの警告文を消すために
$ yarn add --dev @astrojs/check typescript
```
### ◯ @astrojs/react
```sh
$ yarn astro add react
```
