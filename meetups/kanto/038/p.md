# 038 Producers List

###### tags: `checkin-out` `038`

## ak_hina

### 担当
- ML
    - 望月杏奈
    - 七尾百合子
    - 永吉昴
    - 白石紬
- SideM
    - 姫野かのん
    - 神楽麗
    - 水嶋咲
    - 秋月涼
    - ピエール

### P業以外で普段やっていること
- スポーツ観戦
    - 野球とかサッカーとかバスケとかいろいろ見てます
- 筋トレ
    - 体型管理が主です
- SE
    - 要件定義から運用保守までなんか全部やらされてるよw
- コスプレ
    - 11/23に幕張メッセでグレイトフル・ブルー(2ndライブの衣装)な杏奈ちゃんやるよ

### 今日やること
- ラウンジ用discordの自動配信システムのメンテナンスをするよ
- ラウンジ用discordに新規導入するbotについて検討をするよ

### 今日の成果
- ミリシタアプリの強制アップデート情報の配信ができるようになりました。

## .ごっち

### 担当

久川凪など

### P業以外で普段やっていること

帰省して[初めて競馬](https://twitter.com/gggooottto/status/1584053104093585410?s=20&t=BeNRh-t6M06M2qMFaXY3LQ)をした。

### 今日やること

- [What3Idols](https://what3idols.vercel.app)開発続きをします。
    - [Nextjs v13](https://nextjs.org/blog/next-13)がリリースされたので、バージョンアップします。
    - Dependabotがyarn v3に[対応したっぽい](https://github.blog/changelog/2022-10-20-dependabot-can-now-generate-security-and-version-updates-for-yarn-v2-and-v3/)のでdependabotに移行します
        - ライブラリ・パッケージの更新を自動でやってくれるサービス
    - Nextjs v13にWebpackよりもやべぇはやくやってくれる[Turbopack](https://vercel.com/blog/turbopack)のalphaバージョンがあるので、時間があまったら導入したい。。。。。

### 今日の成果

- さらっとアップグレードしただけで動いたので助かる。
    - https://github.com/YutaGoto/what3idols/pull/225
    - `next build`でこけたので助からない。。
    - `@react-google-maps/api` をアップグレードしたら直った。
        - https://github.com/YutaGoto/what3idols/pull/232
- ついでに`Vercel/cli`のバージョンを上げたら、デプロイコマンドのオプションが変わってた。
    - `vercel --confirm` => `vercel --yes`
    - https://app.circleci.com/pipelines/github/YutaGoto/what3idols/345/workflows/3e08c552-4948-4938-9c1c-35c0150d4854/jobs/425/parallel-runs/0/steps/0-104
        - Staging環境がないと開発業で絶対にやらかすやつ
- Dependabotを有効にした。
    - https://github.com/YutaGoto/what3idols/commit/4d937649e4bdb4170dd4a72a97d9ca36c406bdf6
    - ![](https://i.imgur.com/gDxqLaf.png)

## あろー

### 担当

ほたたたた

### P業以外で普段やっていること

一人暮らしの物件を探してきました 🏠

### 今日やること

- 溜まってるシャニの新衣装のPRをim@sparqlに投げたい
- [アートワーク画像検索](https://imas-artwork-search.pages.dev/)に使ってるAPIのメンテをします
    - ライブラリのインポートに使ってる[Skypack CDN](https://www.skypack.dev/)が最近メンテされていない（らしい）のでDenoのnpmサポート機能を使う形にします

### 今日の成果

- PRを出した！
    - https://github.com/imas/imasparql/pull/519
    - 明日がガシャの更新日なのでDraftにしてる
- APIのメンテした！
    - https://github.com/arrow2nd/imas-artwork-api/pull/55
    - Denoのnpmサポート、型定義もちゃんと読み込まれててすごい… 🦕
    ![](https://i.imgur.com/cg5HKsL.png)
- [ShinyPoems](https://shiny-poems.vercel.app/)をNext.js 13にあげた！
    - `/pages`から`/app` に移行するやつは追々やりたい…
