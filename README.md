## Quick Start

私のブログテーマを使っていただきありがとうございます。以下の簡単なアクションに従うだけで、サイト/ドキュメント/ショーケースのページを素早く生成することができます～コマンドラインは不要です～。

[このページをGithubで読む](https://github.com/wu-kan/jekyll-theme-WuK)

![License](https://img.shields.io/github/license/wu-kan/jekyll-theme-WuK)![commit-activity](https://img.shields.io/github/commit-activity/m/wu-kan/jekyll-theme-WuK)![last-commit](https://img.shields.io/github/last-commit/wu-kan/jekyll-theme-WuK)![CountLanguage](https://img.shields.io/github/languages/count/wu-kan/jekyll-theme-WuK)![TopLanguage](https://img.shields.io/github/languages/top/wu-kan/jekyll-theme-WuK)![CodeSize](https://img.shields.io/github/languages/code-size/wu-kan/jekyll-theme-WuK)![RepoSize](https://img.shields.io/github/repo-size/wu-kan/jekyll-theme-WuK)![Downloads](https://img.shields.io/github/downloads/wu-kan/jekyll-theme-WuK/total)![Watchers](https://img.shields.io/github/watchers/wu-kan/jekyll-theme-WuK)![contributors](https://img.shields.io/github/contributors-anon/wu-kan/jekyll-theme-WuK)![Release](https://img.shields.io/github/v/release/wu-kan/jekyll-theme-WuK)![release-date](https://img.shields.io/github/release-date/wu-kan/jekyll-theme-WuK)

<!-- .slide vertical=true -->

### 1つ目

このリンク<https://github.com/wu-kan/wu-kan.github.io/fork>，をクリックして、[サイト例](https://wu-kan.cn)をあなたのリポジトリにフォークしてください。 フォークは例のサイトであり、フォークのテーマリポジトリは不完全であることに注意してください。

<!-- .slide vertical=true -->

### 2つ目

Fork後のリポジトリでオプション 「Setting」を選択し、リポジトリ名を`your-name.github.io`。

例えば、ここの例で使った GitHub は @Mizuno-Ai で、名前の変更は`Mizuno-Ai.github.io`となっています。

<!-- .slide vertical=true -->

![TW9GSNUkfv6lsyr8Xh1qKaRjwD](https://i.loli.net/2020/12/01/P61UlGcjqHSNXwa.png)

<!-- .slide vertical=true -->

### 3つ目

Settingをプルダウンして Github Pages 関連のオプションを見つけ、 Source を None から master branch，に変更し、 Custom domain をあなたのURLに変更します。

<!-- .slide vertical=true -->

![csFVmdQfKTP4SWApE9DOkMwhZt](https://i.loli.net/2020/12/01/zsLxQVYU2dj3yEa.png)

<!-- .slide vertical=true -->

![2t96cfb85yDwxeAn3XLPmkrI1U](https://i.loli.net/2020/12/01/yTc6mozNvGru92p.png)

<!-- .slide vertical=true -->

少し待つと、あなたのブログのアドレスがアクセス可能であることが表示されます。 半端ないって～。

<!-- .slide vertical=true -->

### 4つ目

リポジトリのルートに戻って、自分で`_config.yml`を設定し、読める範囲で変更してください。 ほとんどの設定項目にコメントを付けました。

<!-- .slide vertical=true -->

![4.1.png](https://i.loli.net/2020/12/01/t7hOkr5LVpZfEn3.png)

<!-- .slide vertical=true -->

![4.2.png](https://i.loli.net/2020/12/01/paufLrzkVhZenFJ.png)

<!-- .slide vertical=true -->

![4.3.png](https://i.loli.net/2020/12/01/7i5uEYPHS2Ljts4.png)

<!-- .slide vertical=true -->

 yaml形式でのインデントは重要で、元のインデントを崩さないようにすることが大切です。

<!-- .slide vertical=true -->

### 5つ目

リポジトリのルートに戻って、ブログの記事を格納している`/_posts/`フォルダをクリックします。 自分のブログを書くには、「新規ファイルを作成」をクリックします。 これらの投稿に使用されるフォーマットは[Markdown](https://www.runoob.com/markdown/md-tutorial.html)，これは非常にシンプルで使いやすいフォーマットされたテキストのマークアップ言語で、ファイル拡張子は `md` です。

<!-- .slide vertical=true -->

![5.1.png](https://i.loli.net/2020/12/01/Jm784WbjACLtdOP.png)

<!-- .slide vertical=true -->

ファイルの命名規則は `date-title.md` である必要があります。表示の不一致を防ぐために、ファイルの内容の前に `title: title` の yaml ヘッダーを付けるのが理想的です。

<!-- .slide vertical=true -->

![5.2.png](https://i.loli.net/2020/12/01/THowcQnNLFRJx7C.png)

<!-- .slide vertical=true -->

書き込んだら、設定変更と同じようなことをして、Commitを押してコミットします。 再びブログにアクセスすると、あなたのブログ記事がアーカイブページの一番上に表示されているのがわかります。

<!-- .slide vertical=true -->

歓迎[![Star](https://img.shields.io/github/stars/wu-kan/wu-kan.github.io)](https://github.com/wu-kan/wu-kan.github.io)、[![Fork](https://img.shields.io/github/forks/wu-kan/wu-kan.github.io)](https://github.com/wu-kan/wu-kan.github.io/fork)、[![Issue](https://img.shields.io/github/issues/wu-kan/wu-kan.github.io)](https://github.com/wu-kan/wu-kan.github.io/issues)！

<!-- .slide -->

## さらなるカスタマイズ

以上のことは、githubページで直接行うことができます。 ブログのテストをローカルで実行する場合や、ブログをより高度にカスタマイズする場合は、まず以下のブログ記事を読むことをお勧めします。

- [Jekyllをベースにした個人ブログの構築](https://wu-kan.cn/_posts/2019-01-18-%E5%9F%BA%E4%BA%8EJekyll%E6%90%AD%E5%BB%BA%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/)
- [個人的なウェブサイト最適化の旅](https://wu-kan.cn/_posts/2020-02-06-%E4%B8%AA%E4%BA%BA%E7%BD%91%E7%AB%99%E4%BC%98%E5%8C%96%E4%B9%8B%E6%97%85/)

<!-- .slide vertical=true -->

中国語のコピーの統一、タイポグラフィ関連の使い方、チームメンバー間のコミュニケーションコストの削減、ウェブサイトの倫理観の向上、おすすめの読み物。

- [中国語 コピーライティング タイポグラフィ ガイドライン](https://github.com/sparanoid/chinese-copywriting-guidelines/blob/master/README.zh-CN.md)
- [Markdownライティングのヒント](https://wu-kan.cn/_posts/2020-01-18-Markdown%E5%86%99%E4%BD%9C%E5%BF%83%E5%BE%97/)

<!-- .slide -->

## Demo

<!-- .slide vertical=true -->

![Demo](https://wu-kan.github.io/jekyll-theme-WuK/screenshot.png)

<!-- .slide -->

## ファイル構成

私のテーマでは、ページをレンダリングするための主なスタイルとして、以下のものを実装しています。

<!-- .slide vertical=true -->

### `layout: default`

[poole/lanyon](https://github.com/poole/lanyon)をベースに、サイドバーとワープを用意し、サイドバーと一緒に移動できるようにしたページ。

<!-- .slide vertical=true -->

### `layout: page`

`layout: default`をベースに、ヘッダーバー`.masthead`とテキストボックス`.content`が用意されています。。

<!-- .slide vertical=true -->

### `layout: comments`

メッセージページは`layout: page`をベースに、メッセージプラグインは[Valine](https://valine.js.org/)を使用しています。。

例：<https://wu-kan.cn/comments/>

<!-- .slide vertical=true -->

### `layout: post`

`layout: comments`をベースにしたブログ記事ページで、各ブログ記事に説明情報を追加します。

例：[Jekyllをベースにした個人ブログの構築](https://wu-kan.cn/_posts/2019-01-18-%E5%9F%BA%E4%BA%8EJekyll%E6%90%AD%E5%BB%BA%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/)

<!-- .slide vertical=true -->

### `layout: merger`

合併に伴う報酬ページ。

例：<https://wu-kan.cn/merger/>

<!-- .slide vertical=true -->

### `layout: home`

`v3.1.0`から、`layout: home`は私が書き換えて、[hakimel/reveal.js](https://github.com/hakimel/reveal.js)をベースにしたきれいなプレゼンテーションページを実装しています。プレゼンテーションを行います。

例：[マイナンバーチャート最終発表会ページ](https://wu-kan.cn/_posts/2019-12-10-%E6%95%B0%E5%9B%BE%E6%9C%9F%E6%9C%ABProject/)

<!-- .slide vertical=true -->

水平方向のページセパレータと垂直方向のページセパレータ（カスタマイズ可能）をマークダウンファイルに挿入すれば、準備完了です。 このドキュメント(https://github.com/wu-kan/jekyll-theme-WuK/blob/master/README.md)を例に挙げることができます。

推奨するセパレータは ![縦型タグ](data:image/webp;base64,UklGRswEAABXRUJQVlA4IMAEAABQHwCdASrAASAAPsVQo0unpKMhtJMt+PAYiWkAFsxLa9e8Eh/E96cqAGmyaFhk0Q5inYLCsACybyvNmNBBvQcWVFDythsQZJBVxehBlMwh1yaCph3TT2mmXBYK4xTe1NQkAXYTUqlqw5axNWj96M5T+rkKO1ITOC/HXVhXDuBiZLLWebQVjzeuOZZbVNTlj1mUAthhmVBOEZyvWrJ8MacmBcu/R1nhZXOFxgJcjRk0JUNUxVxkcJKLugO7TzsHe/ypmIXUjZkQM2B75gv0R2Il+croGEtWa9KC3jCQ50RDOiQz2gtg3d5JDES2HqfZoVXHDcmj31oyYgLAMsrs0kRz6oAAAP73mKTfMOCm35/b4Qk9coZRWF/gzyQ+AyJOWBfAGDv3SBErqzWPv1hFXtlNoLceJgqLqnLzOSUx7DiuK2wiJ4rUObsqOE+MT6+pGZhCQhIjAq7hVZOjFtXUAuXEvG0pwJn3iedUv/j455TijyrJJcdJMR4aqihWqaBMTcB4E2CcjQ1YdITOt7BzvuJ+ujCFC5gybqIFrv+7SeNt4xux7nEqq6ajkJwkXg4GutsosueU/0lBwh3UW/kFoOKFTWouPwbLGWdYI4WaIWshXeDv549gTc0PKD/FFeqPHd9aU++Hqu7JbmEMpa7CLPsaxQRgDGAHDfjva0DqroXr7gD7SHbIHeEEfGneh7wgYLGcN1wO6XpUnmZQSYhqvKZ3V9qh180B9n7/7ViGnOjPnLZHiR0DDUPN3WgNvLfdTtXrzTIIe4clZR4QBCJ98wGdOZEo3vv0y+I7HVPXcDzibfxpuyfoPCnOgMFmVLKMvwqIHgIWH4Yxzhv6efYiKAyOVNnQIosoOKsI/6mG1uzH9RjgDcJA7gTJvwpTq5ST0FKUdrVtY0F62jai3eqcWhQEg3Lp11W2z8+pOjpU/ALrHDFQB8eATgid4+lu9cquOn6D5jfkHAIOVSWNgW55QB3drAhCEqTZ2BCjIxzQeTTD50rZxGTSSv51QbMbOG6+OQp6X6mOuYlBPctjkYbTYITDV0ANyT/bH1ZYw0QN+qV9Z0FvgDMuixTGgm/WwRDroKqik4JL9Toro+xMQKUlbaftdxfIjkrmVDAALBD/bF26A3vTRtGP+KMgNDj2mqd9w3znrM/WQnqrtp2Dm7vLVmURPpLzofnbviwFz7LHSPwT7dz1tfOPPeJMunAM7Hl2bLMPJ53KZy9M0+ns7ylPJ5sYLNsrstwdy5/KgZi9nqhQ9rDGETCv9Jm01GiMBemXJa4EPD7VB1MCG2Ep+ibTIRNjQ/j3Q/HyNfUpwNQSJ4DEiG3ZKplHKFRdjwWz2jsVBl+S6T98wMG7WJKoOAv6UDHM1GJ814ICZRXKX8COWPCKvFJgPT+ohqrUYy2YxQvr/UUJoIRbX3xCmyL/Co484h4ADGRJ+pl9Dkv72GvAxR9Q9/lZzSNgkiess0mfv2ctlFaKnfQGhsE2g39w37DIR26xJi0rMtkey9YiaTl62hSm3uqrKSpidim0eDZJvLvHLTxHxoBOytnf9sZaUuEAC5/OAGcD86/cByTlWvPbvbnRPygoLSl8xEmg9IWpHnD/ETK2dClPiRsF+hfETqEtSAAA)そして![水平ラベル](data:image/webp;base64,UklGRlwCAABXRUJQVlA4IFACAACQDwCdASrgACAAPpE8m0elo6KhLbVcALASCWkAEWHcpexmUsD6ZOiu5sdWJqej30kHAWtWgzm1NokVrmXtBduqdjf69Ky/YrEfEk+DW1QmKbH58l6EwOTfIUdlpA9FItaZ+aXOqRi7Lf8XoMSwIPubKewvVC8kbFKgsiWQMmHqL7KMBE8AAP79uypAcc+TWCg0wbbnBWWODDTzqFgLrrobgfk6sOqETmoC8PIIDAt2Si73oax5KbX3SwCtGFRuRBn1uMwQStgw0dWqf5biuBby+hCRVXsg1usfCXyC2TOzsYDX89EEII6pcuI+jyvREioCmAhUHo5uHUEi05r1rckaSHFG9jYaTLNpOSC2AFItW/sUZIgBsYz1EnDk0oPG0eaWfTD3p1pwNOapL3JUK52Kqqdpwi5L/UxF+qUPS+XVX5BA2AI2FjTkJXaN75DUdEQ04xq+fCz1hDcc9po5h4AJCmNGDJ+hBKvSAKeRvRzbAi/OgVFg4ZpozCToVa+MMYslTrUGCJC3goF1f379lpSUD12xat2I4lTC3UrAkcbYE8kvpy817kSb+lg4cD80TdS06oTGhQR5jhlw9m3Shctwj5MyQ9e4dnKfbvZGsjBiB/C4OS/yJT4yN6vSFq/P3DmpiG5pQYwGVZud0Sp4fQ/hK84KYIxfEfeZSTRvrrNcS83XqziGfuD2xXXkulIjKF2Wdo9SDsZ2v2owdj9PN6xprlnXo/lEUwI/dRpY0JscfYWYrWtPdn4aznDTfsXina6MeJvfZyJ+dktjvrCfSAAA)，で行うことができます。[vscode-markdown-preview-enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/#/presentation)マーカーには互換性があり、ローカルでのプレビューが容易です。

<!-- .slide vertical=true -->

ホームページ以外のページのレンダリングに使用したい場合は、マークダウンのyamlヘッダーに`layout: home`を設定してください。 もちろん、ホームページのレンダリングに使いたくない場合は、ホームページのレイアウトを別のものに設定することができます。

特定のページでサイドバーをデフォルトでオンにするには？ yamlヘッダーで`jekyll-theme-WuK: default: sidebar: open: true`を設定するだけです。

特定のページのサイドバーを非表示にしたい。 yamlヘッダーで`jekyll-theme-WuK: default: sidebar: disable: true`を設定するだけです。 これは、`sidebar: open`の設定を上書きします。

<!-- .slide vertical=true -->

これはまだ開発中の機能です（主な理由は、素敵で洗練された[表示テーマ](https://github.com/hakimel/reveal.js/tree/master/css/theme)），が見つからなかったからです）ので、ご提案やご要望があればお気軽にお寄せください
<!-- .slide vertical=true -->

より多くの機能については、[hakimel/reveal.js](https://github.com/hakimel/reveal.js)を自由にご覧ください! ~~ 例えば、Escを押すとpptのアウトラインが生成されます～～。

<!-- .slide -->

## 初心

私は何をしたか？

私は何をしているのだろう？

自分が何をしたいのか？

どうすればいいですか？

<!-- .slide vertical=true -->

> 張飛海は、父の魂が冥界から飛行船に降り立ち、自分と一体になっているのを感じながら、オペレーターインターフェイスの最後のボタンを押し、生涯をかけて努力してきたコマンドを心の中で静かに唱えた。
>
> “‘自然淘汰’，前進する4！”

<!-- .slide vertical=true -->

目標は、可能な限りシンプルでありながら、カスタマイズ可能なコンテンツが豊富なブログを作ることです。 もっと良い提案があれば、気軽にIssueをください。

<!-- .slide -->

## 声明

<!-- .slide vertical=true -->

すべてのブログ記事は、特に明記または複製されていない限り、[表示-継承 4.0 インターナショナル](https://creativecommons.org/licenses/by-sa/4.0/deed.zh)のライセンスで提供されています。

ブログの内容は[MIT License](https://github.com/wu-kan/jekyll-theme-WuK/blob/master/LICENSE)由来[GitHub](https://github.com/wu-kan/jekyll-theme-WuK)。

<!-- .slide -->

## 謝辞

<!-- .slide vertical=true -->

Hosted at[Github Pages](https://pages.github.com/)，thanks.

[jekyll/jekyll](https://github.com/jekyll/jekyll)，からのブログエンジン、ありがとうございます。

<https://cdn.jsdelivr.net/>と<https://loli.net>，のCDNアクセラレーションサービス、ありがとうございます。

<!-- .slide vertical=true -->

[poole/lanyon](https://github.com/poole/lanyon)，をベースにしたブログテーマ、ありがとうございます。

アイコンギャラリーは[<i class="fab fa-font-awesome"></i>fontawesome-free](https://fontawesome.com/)，から、ありがとうございます。

表示ページは[hakimel/reveal.js](https://github.com/hakimel/reveal.js)，をベースにしています、ありがとうございます。

[hifocus/merger](https://github.com/hifocus/merger)，からの寄付のページ、ありがとうございます。

[penibelst/jekyll-compress-html](https://github.com/penibelst/jekyll-compress-html)，からのページ圧縮、ありがとうございます。

<!-- .slide vertical=true -->

[utterance/utterances](https://github.com/utterance/utterances)，からのコメントシステム、ありがとうございます。

ページの統計情報は[不蒜子](http://busuanzi.ibruce.info/)，からです。ありがとうございます。

[christian-fei/Simple-Jekyll-Search](https://github.com/christian-fei/Simple-Jekyll-Search)，のブログ検索プラグイン、ありがとうございます。

ブログディレクトリプラグインは[allejo/jekyll-toc](https://github.com/allejo/jekyll-toc)，のものです、ありがとうございます。

コードハイライトとプラグインは[PrismJS](https://prismjs.com/)，から、ありがとうございます。

<!-- .slide vertical=true -->

[Dreamer-Paul/Pio](https://github.com/Dreamer-Paul/Pio)，のLive2Dフロントエンド・プラグイン、ありがとうございます。
Live2Dモデル [imuncle/live2d](https://github.com/imuncle/live2d)と[xiaoski/live2d_models_collection](https://github.com/xiaoski/live2d_models_collection)，ありがとうございます。

<!-- .slide vertical=true -->

アバター、<https://www.pixiv.net/artworks/71574257>、<https://www.pixiv.net/artworks/71932901>と<https://www.pixiv.net/artworks/74559485>，ありがとうございます（侵害は削除する必要があります）。

アバターのフリップエフェクトをイメージ[leopardpan/leopardpan.github.io](https://github.com/leopardpan/leopardpan.github.io)，thanks.

<!-- .slide -->

## 旅

<!-- .slide vertical=true -->

### 2021-06-07 v4.1.0

- を削除して、テーマをスリム化します。
  - layout: archive
  - layout: tags
  - layout: page404
- 配合 jekyll-redirect-from テンプレート、追加
  - layout: redirect
- 使用[utterances](https://github.com/utterance/utterances)代替 valine

<!-- .slide vertical=true -->

### 2021-06-03 v4.0.5

- いくつかのページオプションの強化
  - 旧バージョンからのダイレクトアップグレード
<!-- .slide vertical=true -->

### 2021-05-23 v4.0.4

- バックエンドの実装を合理化し、ホームページのセクションを削除

<!-- .slide vertical=true -->

### 2021-01-10 v4.0.3

- ドキュメントのスタイルを更新すると、 $\LaTeX$ のようにレンダリングされます。

<!-- .slide vertical=true -->

### 2020-09-15 v4.0.2

- サイドバーに任意の [minivaline-counter](https://github.com/MiniValine/minivaline-counter) を追加しました。
  - ノットガーリックのサブカウンターの交換に使用でき、2つのカウンター間でカウンターの数が不一致になる問題を解決できる
<!-- .slide vertical=true -->

### 2020-07-23 v4.0.1

- [jekyll-compress-html](https://github.com/penibelst/jekyll-compress-html)でrougeを使用し、コードの行番号をオンにしたときに発生するレンダリングエラーを修正しました。
- `search.json` が動作しない問題を修正しました。
- デフォルト、ホームに設定項目を追加
- パッケージ発売

<!-- .slide vertical=true -->

### 2020-06-21 v4.0.0

- すべてのテーマ設定変数を [front-matter-defaults](https://jekyllrb.com/docs/configuration/front-matter-defaults/)，に移動し、すべてのページを設定用にカスタマイズできるようにしました。
- タブページ、アーカイブページ、ディレクトリの追加（オプション）
- プラグインをページ下部に再配置し、ページの読み込み速度を向上させる

<!-- .slide vertical=true -->

### 2020-05-29 v3.2.1

- 生成されたページサイズを圧縮するには、 [penibelst/jekyll-compress-html](https://github.com/penibelst/jekyll-compress-html) を使用します。
- アーカイブ、タグのページ生成速度の最適化
- 新しいアーカイブのカスタムグルーピングルール

<!-- .slide vertical=true -->

### 2020-05-21 v3.2.0

- バージョン4.0への自動アップデート後に発生する reveal.js のレンダリングエラーを修正!
- ドキュメントページが復活し、githubのreadmeスタイルの印刷可能なドキュメントを生成できるようになりました。
- ブログ記事にタグがない場合、タグアイコンが表示されたままになっていた不具合を修正
- 設定項目でのアラートの命名は標準化されていないので、すべてappend/prependに置き換えてください。
- ブログディレクトリプラグインを[allejo/jekyll-toc](https://github.com/allejo/jekyll-toc)，に置き換え、純粋なLiquid!
- 次のステップでは、katex、mermaid、prismの各プラグインのレンダリング速度を同様に最適化します。

<!-- .slide vertical=true -->

### 2020-04-28 v3.1.5

- ブログ記事の単語数統計で中国語が無視される問題を修正
- バリーンの読み取り統計が無効になる問題を修正

<!-- .slide vertical=true -->

### 2020-04-20 v3.1.4

- アーカイブページのブログ記事数のカウントミスを修正 年

<!-- .slide vertical=true -->

### 2020-04-20 v3.1.3

- アーカイブページ、タブで円の統計チャートを追加
  - それは醜い、あなたはそれをオフにすることができます
- アーカイブページが年別アーカイブに

<!-- .slide vertical=true -->

### 2020-04-12 v3.1.2

- [poole/lanyon](https://github.com/poole/lanyon) v1.1.0にアップデートしました。
- Live2Dのテーマ変更ボタンの追加
- ページ内で使用されている変数を`jekyll-theme-WuK`名前空間に移動しました。

<!-- .slide vertical=true -->

### 2020-03-28 v3.1.1

- ローカルテストを高速化するために壁紙を削除
- `layout: home` のブロックレンダリングで起こりうる問題を修正しました。

<!-- .slide vertical=true -->

### 2020-02-29 v3.1.0

- バンドルによるバージョン管理と依存関係の実行
- Remote_theme によるブログテーマとブログ記事の分離
- Baiduのクローラーがクロールできない問題を解決するためのgitlabミラーの導入
- [hakimel/reveal.js](https://github.com/hakimel/reveal.js)に基づいて、`layout: home`を書き換える。
- live2dプラグインを[Dreamer-Paul/Pio](https://github.com/Dreamer-Paul/Pio)に置き換える
- ライブ2Dモデルの置き換え
- live2dプロンプトのカスタマイズ
- cssスタイルの更新
  - レインボースクロールバー
  - ページ読み込み時のアニメーション
  - 縦長画面での壁紙変更

<!-- .slide vertical=true -->

このような大きなアップデートでは、バージョン番号を「4.0.0」に変更する必要があるように感じます。

ただし、このバージョンは旧バージョンとの互換性を維持しているため、実際には「3.1.0」となります。

<!-- .slide vertical=true -->

### 2020-02-14 v3.0.0

- プラグインの導入部分が完全にリファクタリングされ、htmlに直接埋め込むことができるようになりました。
- live2dのカスタマイズをサポートするために、live2dプラグインを[kooritea/live2d-helper](https://github.com/kooritea/live2d-helper)，に置き換えました。
  - Kooritea ボタンを隠す
- jQueryの削除
- カテゴリタグを削除し、タグに変更
- ブログを再構築し、`/public`ディレクトリを jekyll のデフォルト `/assets`に移動。
- merge Rewardsのページ
- サイドバーのスタイルを変更し、よりクリーンに
- 壁紙を追加して縦に表示
- グローバル検索
- $\KaTeX$ 線形式

<!-- .slide vertical=true -->

### 2020.01.31 v2.4.1

- 赞赏按钮样式修复
- 使用<https://loli.net>加速 gravatar，感谢~
- 网站字体更换为等宽字体+微软正黑体
- live2d 移动到页面右侧
- 更换爱酱壁纸

<!-- .slide vertical=true -->

### 2019.11.11 v2.4.0

- 修复`sidebar-overlay`失效的 Bug
- 修复赞助按钮点两次才出现的 Bug
- 修复 mermaid 不显示的 Bug
- 去掉正文部分的白色半透明背景
- 动态背景增加 nest 粒子动画（花里胡哨，默认关闭
- Ribbon 动态背景默认关闭，可在配置文件中去掉注释打开（花 里 胡 哨
- 博文显示信息增加 tag
- 变迁页面增加 tag、categories 图标及对应分类文章数量
- 页面显示适应宽屏显示器
- layout 增加
  - index
  - tag
  - page404

<!-- .slide vertical=true -->

### 2019-08-30 v2.3.0

- 更换 cdn 为[jsDelivr](https://www.jsdelivr.com/)
- 升级 fontaswsomev4.7.0 至 fontawesome-freev5.10.2，支持的图标数量由 675 增加至 1535
- 所有脚本和插件 JSLoader 化，增加移植性和访问速度
- 界面调整
  - 正文部分增加背景，从而减少动态 ribbon 背景影响的阅读体验
  - sidebar 微调
- layout 删除 document 页

<!-- .slide vertical=true -->

### 2019-07-06 v2.2.1

- prismjs 使用[UNPKG](https://unpkg.com)加速
- 删去 layout 中的 404 页（因为只需要引入 js 脚本）

<!-- .slide vertical=true -->

### 2019-06-28 v2.2.0

- 博客结构微调
- 将大部分博客用到的 jscdn 换成 unpkg.com，感谢其提供的加速服务~
- 留言板加入友链

<!-- .slide vertical=true -->

### 2019-05-03 v2.1.4

- valine 更新
  - 现在支持记录访问者 IP
  - 每次重新拉取评论者头像

<!-- .slide vertical=true -->

### 2019-04-29 v2.1.3

- 页面样式微调，将 masthead 调矮，将标题字号改小

<!-- .slide vertical=true -->

### 2019-03-20 v2.1.2

- 修复 sidebar 展开时回到顶部的问题

<!-- .slide vertical=true -->

### 2019-03-18 v2.1.1

- 一些界面上的小调整

<!-- .slide vertical=true -->

### 2019-03-01 v2.1.0

- 调整某些插件
- layout 新增 document 页，一个只开启$\KaTeX$而不引入任何其他样式的页面，主要是方便自己生成可打印的 ICPC 模板和一些课程报告
- layout 新增 404 页，可选择开启腾讯公益
- mermaid 支持 markdown 扩展了

<!-- .slide vertical=true -->

### 2019-02-24 v2.0.1

- sidebar 的触发按钮样式换成了 bars，原来的样式更像是菜单
- 一点页面上的小调整

<!-- .slide vertical=true -->

### 2019-02-23 v2.0.0

- 重构完成
- 正式开源

<!-- .slide vertical=true -->

### 2019-02-19

- 模块化·初步
- 博客搜索实现

<!-- .slide vertical=true -->

### 2019-02-01

- [署名-相同方式共享 4.0 国际](https://creativecommons.org/licenses/by-sa/4.0/deed.zh)。
- 社会主义核心价值观点击特效，感谢[dujin](https://www.dujin.org/9088.html)。
- 打赏。

<!-- .slide vertical=true -->

### 2019-01-31

- mathjax 换 katex
- post 访问量统计

<!-- .slide vertical=true -->

### 2019-01-24

- 代码高亮
- 选中代码按钮
- 代码语言按钮

<!-- .slide vertical=true -->

### 2019-01-23

- 加入文章目录到 SideBar

<!-- .slide vertical=true -->

### 2019-01-22

- 加入 Ribbon 动态背景

<!-- .slide vertical=true -->

### 2019-01-21

- 加入 valine 评论系统，留言页实现

<!-- .slide vertical=true -->

### 2019-01-20

- 加入归档页

<!-- .slide vertical=true -->

### 2019-01-19

- 加入标签页

<!-- .slide vertical=true -->

### 2019-01-18

- 开始用 Jekyll 重构整个博客

折腾吧，折腾是才最好玩的。

<!-- .slide vertical=true -->

### 2019-01-13

- 更换 Next.Muse 主题模板
- 少量修改页面自定义样式布局，主要是 sidebar
- 将网易云音乐 iframe 移动到 description，感觉挺有意思的

<!-- .slide vertical=true -->

### 2019-01-12

- 将 NexT 版本更新至 v6.7.0

<!-- .slide vertical=true -->

### 2018-12-23

- 页面字体修改
- 网易云音乐 iframe 加入 SideBar

<!-- .slide vertical=true -->

### 2018-12-16

- 引入 mermaid 支持
- 修复部分 Latex 渲染的 Bug

<!-- .slide vertical=true -->

### 2018-11-24

- 将 NexT 版本更新至 v6.5.0
- 用 Valine 更换失效的 Gitment 评论系统
- 加入 Leancloud 和 busuanzi 页面统计

<!-- .slide vertical=true -->

### 2018-11-20

- 谷歌，百度搜索页面提交

<!-- .slide vertical=true -->

### 2018-11-18

- 全局透明化
- 动态背景
- 页面加载动画
- Latex 支持

<!-- .slide vertical=true -->

### 2018-11-16

- 主题由默认的 Landspace 换至 NexT v5.1.4
- 使用 Next.Pisces 主题模板
- 开始对网页进行自定义样式布局
- 尝试加入 Gitment，但初始化总是不成功

<!-- .slide vertical=true -->

### 2018-11-15

- 在 Github 上成功部署博客
- 成功迁移[原 CSDN 博客](https://blog.csdn.net/w_weilan)上的所有文章
- live2d

<!-- .slide vertical=true -->
